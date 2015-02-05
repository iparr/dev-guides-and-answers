# On carousels in web design

A quick note: When we talk about a '***carousel***' these are also known as '*sliders*' or '*rotating banners*'. When we talk about a '***slide***' we refer to a '*pane*' or a single '*banner*' a number of which make up a complete carousel.

## Table of Contents

* Effective types of carousel
* Pros
* Cons
* Some useful resources

## Effective types of carousel

* **With 'fresh' content**, they help make the site look 'fresh'… however only when used with appropriate content - i.e. news, recent case studies, etc. They can quickly display to return visitors new content. [[example](http://www.amnesty.org.au/)]
* **Information lead carousels** can be effectively used as a story-telling device: so that all information within is related to each other slide and they must be consumed in a paricular order. [[example](http://www.zennaware.com/cornerstone/)]
* **Navigational carousels** are a great device to quickly **segment** visitors types. i.e. if we have 3 clear different customer types: "Am I a business user, a home user or a current customer looking for support"." [[example](http://www.theaa.com/)]

The following are more general 'Pros' and 'Cons' that are relevant to any type of carousel:

## Pros

* It can be possible to represent a great deal of content within a comparitively small space.
* It can be argued that having *something* moving on the homepage helps make it look more dynamic and exciting.
* Amongst many users, particularly iPhone users, a carousel-type device is often used as a primary form of navigation through the content - one that actually replaces primary navigation menus. This expectation has been set by a number of popular applications.
* When you have attractive products, a carousel can be a great way to display an individual product on one page.
* If a homepage can be split into 3-4 key items and so there are no items to be prioritised underneath the carousel, then a large, full-viewport carousel can be a generous way to display those 3-4 items - allowing plenty of space for introductory copy, clear headlines and imagery.

## Cons

* "**Banner blindness**" - visitors simply to not register advert-like moving content. It is simply ignored. [Eyetracking can prove this evidence](http://beantin.se/post/30991868949/sliding-banner-content-slider-carousel-rotator) (also, [more detailed eyetracking here](http://www.nngroup.com/articles/banner-blindness-old-and-new-findings/)).
* **They are distracting** to the point where they can slow completion of the primary goal (i.e. finding and buying the product).
* There are stats that suggest that the initial slide is clicked used far more often that the others, calling into question the need to have more than one slide. [Research by the University of Notre Dame](http://weedygarden.net/2013/01/carousel-stats/) shows that the first banners received between 40%-62% of clicks. This suggests that although you may think a carousel treats each item with equal priority, that is not the desired effect.
* Simliar [research by the University of York web team](http://yorkwebteam.blogspot.co.uk/2013/03/are-homepage-carousels-effective-aka.html) shows not only a simliar story, but that when there are less slides, overall carousel click-throughs are higher.
* **The fold is dead**. Carousels are often implemented in a misplaced effort to keep content above 'the fold'. We now know that people do scroll.  Although renowned usability expert **Jakob Nielson** did once recommend placing everything above the fold, he retracted his advice in 1997 when it became clear that users do scroll. This is even more true in 2013 now we have small-screen devices and educated users. Thus trying to squeeze everything 'above the fold' is not necessary - especially when it renders more content hidden (as it is when it is in a carousel).
* "*Carousels are effective at being able to tell people in Marketing/Senior Management that their latest idea is now on the Home Page*" - their **popularity can be attributed to poor content strategy** and strategic prioritisation. Also, the scourge of modern web-designers: herd mentality!
* Slides are expected to contain some great, strong, **SEO-friendly** headlines. If you have 4 'panes', then you are hiding 3/4 of these on load and it could be argued that this may have a negative impact on SEO potential.
* When a carousel is used one a page that follows the initial landing page (usually the homepage) where there has also been a carousel, then there may be some confusion between which page is actually the homepage that is likely to be missed by users who do not look at their url bar.
* Moving items have a negative impact on **scroll performance**, particularly on mobile/older browsers - particularly with the number of layers we use that are necessary for good RWD behaviour. **Note:** Performance can be improved to an extent by utilising different techniques for different browsers, but of course this effects build time.
* More styles, images, CSS and markup is necessary to create a carousel: even when many users probably wont see the final 2-3 sliders. This can be considered wasted bandwidth and is especially a problem on mobile devices and will have a **negative impact on page load-time**.
* Many carousels are automatic - they move without any user interaction. Users do not like surprises and like to remain in control at all times. Any action that happens without their interaction can be viewed negatively.
* I do not believe that a fully-formed visual language has been developed yet. Swiping is not a logical action for all visitors on a **touch device**, who may be left a little confused.
* "*Moving UI elements usually reduce accessibility, particularly for users with motor skill issues who have difficulty clicking something before it's taken away*" - quote, [via Nielsen](http://www.nngroup.com/articles/auto-forwarding/).


## Some useful resources

* "[Don’t Use Automatic Image Sliders or Carousels, Ignore the Fad](http://conversionxl.com/dont-use-automatic-image-sliders-or-carousels-ignore-the-fad/)": Conversion XL - Some great examples of websites that previously had carousels but have since returned to static banners.
* [Auto-Forwarding Carousels and Accordions Annoy Users and Reduce Visibility](http://www.nngroup.com/articles/auto-forwarding/): Jackob Nielsen - User research by the UX expert shows: "*The user's target was at the top of the page in 98-point font. But she failed to find it because the panel auto-rotated instead of staying still.*"
* [Rotating Offers – the Scourge of Home Page Design](http://www.widerfunnel.com/conversion-rate-optimization/rotating-offers-the-scourge-of-home-page-design): Widerfunnel marketing optimisation - Some great insight into the "Politics of Home Page Design"
* [Mårten Angner presentation on carousels](http://prezi.com/e9-zaikclehn/will-front-page-carousels-improve-your-conversion-rate/) - Although in Dutch, this presentation shows that removal of the carousel lead to a **6% increase in conversion**, further benefits of this [are discussed here in english](http://angner.se/blog/will-front-page-carousells-improve-your-conversion-rate/), evidence of "banner blindness" shown by eyetracking.
* [A Stack Exchange thread where people working in UX discuss carousels](http://ux.stackexchange.com/questions/10312/are-carousels-effective) - generally highlights a negative view of carousels after testing.
* [Brad Frost on Carousels](http://bradfrostweb.com/blog/post/carousels/) - the politics and how to make them slightly less awful.
* [Jakob Nielsen’s Alertbox: September 14, 2013 - Designing Effective Carousels: Create a Fanciful Amusement, Not a House of Horrors](http://www.nngroup.com/articles/designing-effective-carousels/) -  The benefits to using 'Heros' instead and tips on navigation and auto-fowarding.
* [8 UX Requirements for Designing a User-Friendly Homepage Carousel](http://baymard.com/blog/homepage-carousel): Baymard Institute - More advice on making carousels work in those cases where they are recommended (2015).