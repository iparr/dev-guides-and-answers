# SEO amateurs, liars and thieves

Here are some consistant moans and complaints about site SEO quality, which SEO _experts_ frequently miss completely. This can be recycled 9/10 times I'm faced with rebuilding an old site.

* There is no h1. No h2.

* Lovely headings like are used as images, not text.
	* Accessibility concerns
		Elements being displayed using elements, rather than text, means that they are inaccessible to those with disabilities. Much of the Castrol.com websites could arguably be in violation of the 2010 Equality Act (which replaced the old, but still good practice, Disability Discrimination Act).

* Inefficient use of headings
	* The element which should be `<h1>` on the page in the example is instead `<span class="page_text_heading1">`. Not leveraging heading tags correctly is incredibly poor practice as you will be missing out on a big SEO benefit.
	* Underused headlines - News items, for example, may not be header tags. These make really great headers.

* Incorrectly used h-tags
	H1 comes before H2. H2 comes before H3. This is not the case on many websites.

* Low content
	At under 100 words, a page has no real value and should arguably be incorporated into another part of the site. This is more of an architectural issue, but the concern is that this methodology for rolling out pages means that it's not possible to take a better approach.

* urls like 'http://example.com/shop/page-article/article.show/id-3' are not very helpful (this page would be better as /our-clothing-design-history/

* Poorly chosen urls: E.g. pitchreaction.aspx
	Pitchreaction isn't a word. Google would see "pitch-reaction" as two words. Two potentially useful words to a search engine.

* Writing 'headings' in capitals does not make them headings. This does not help SEO at all, unlike an h2.

* With javascript off, the tabs are inaccessible. This may point to it being inaccessible to a search engine too, which is a shame when there is where some nice readable content. Also it screws with the disabled.

* I hate it when people put in meta keywords (which Google ignores) but don't put any content on the page! Aside from the navigation menus, there is bugger all descriptive, naturally written text.

* A meta keyword tag with the content 'keyword' and a meta description tag with the content 'description' isn't terribly helpful.

* There is no 404 page, you're simply directed to the front-page. This is better than an ugly IIS error page but I'm worried that many clients don't have the analytics set up to discover why people go to the wrong link. Always worth investigation. A 404 would make this easier (and is arguably 'proper form').

* No sitemap.xml specified in robots.txt

* No robots.txt, period.

* Often the sitemap.xml does not include content from the 'news' section. This is due to lazily combining two websites together.

* I'm not convinced that changing every item in the sitemap.xml to 'daily' makes things any better, if you're not actually updating daily (which most of these pages won't be), then i wouldn't cry wolf to Google. They may bite.

* Use some local terms if you have any local element to your business.

* Duplicate content

* The name of the site isn't available as a heading level element

* Blank title tags.
	`<title></title>` is very bad SEO practice. A descriptive title is a lot stronger. Are these easy to implement by copywriters? They should be. If not, your CMS is not serving your needs.

* Page weight
	* Code generally bloated and ugly. Google run 'pagespeed' for a reason.
	* If pages look odd as they slowly load, they may cause a user on a slower connection to simply give up and leave. Concentrate on actual content rather than chrome and fluff.

* Ability to update the site quickly
	* Speed of deployment
		The EDGE site (and any site we'd build in the future) is built on a solid CMS system (that has passed BP security testing). We are confident that using similar techniques will result in a page that 2020 can modify or roll-out much quicker than any other GIP-based page, whilst maintaining a higher level of quality.
	* Non-developer access
		The bulk of the content should be easily modified by those who are not web developers. EDGE has this ability, does GIP?

* Duplicate pages
	Is example.com and www.example.com the same page? Choose one, and redirect to the other!

## Some handy SEO content:

My [Delicious bookmarks tagged 'SEO'](http://delicious.com/devolute/seo).