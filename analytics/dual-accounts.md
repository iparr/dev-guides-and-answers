# Tracking two accounts with Google Analytics

This will help us track one website across two accounts.

	
	/* Google Analytics */
	    var _gaq = _gaq || [];
	        _gaq.push(['_setAccount', 
	            'UA-XXXXXXXX-X'],
	            ['_setCustomVar',
	                1,
	                'Section',
	                'Football',
	                3
	            ],
	            ['_trackPageview'],
	            ['_trackPageLoadTime'],
	            /* Global */
	            ['b._setAccount', 'UA-YYYYYYYY-Y'],
	            ['b._trackPageview'],
	            ['b._trackPageLoadTime']
	        );
	
	    (function() {
	        var ga = document.createElement('script');
	        ga.type = 'text/javascript';
	        ga.async = true;
	        ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
	        var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
	    })();


In the above case, the account 'UA-XXXXXXXX-X' is the primary GA account. The second number 'UA-YYYYYYYY-YY' is the secondary account.

This means we have two accounts on every page. Simply using the above (replacing X and Y with valid GA IDs of course!) will ensure that page views are tracked accurately.

It must be noted that when tracking events using techniques like:


	$('a[rel*="external"]', '#content').live('click', function(e) {
		_gaq.push(['_trackEvent', 'External', this.title, this.href]);
	});


…the result will be that these events are sent to the primary account. These events will not show in the secondary GA account, unless the above is modified. Remember: it is still better to track event-type actions using this technique, rather than trying to register them as a page-view, as this may give a false impression of site traffic.
