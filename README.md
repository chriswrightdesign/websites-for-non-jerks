Websites for non-jerks
=======================

A checklist for friendly websites (accessible, performant, progressively enhanced, and portable device happy).

An argument buster and responsible decision primer for websites - with links to where I got the data, ideas, or followed the discussion.

##1. Accessibility

- [Why bother with accessibility?](http://24ways.org/2013/why-bother-with-accessibility/)
- Structured your markup well and in a way that makes sense? [Semantic structure and why it's important](http://webaim.org/techniques/semanticstructure/)
- Considered contrast and colour blindness?     [Colour blindness and contrast](http://www.visionaustralia.org/digital-access-cca)
- How's your tab key going? unplug your mouse, use the site.     [On basic accessibility testing](http://24ways.org/2013/coding-towards-accessibility/), [Designing for easy interaction](http://alistapart.com/article/designing-for-easy-interaction)
- Have you tested in Wave? (and are aware that this will only take you so far in acessibility) [Wave accessibility tester](http://wave.webaim.org/)
- Tested with voice control? [Apple voiceover](http://www.apple.com/au/accessibility/osx/voiceover/), [NVDA for FireFox](http://www.mozilla.org/en-US/grants/nvda.html), [JAWS](http://www.freedomscientific.com/products/fs/jaws-product-page.asp), [ChromeVox](http://www.chromevox.com/)
- Have you used WAI-Aria landmark roles correctly?          [Using WAI-Aria landmark roles](http://blog.paciellogroup.com/2013/02/using-wai-aria-landmarks-2013/)
- [Designing apps for the visually impaired](http://realmacsoftware.com/blog/designing-apps-for-the-visually-impaired)
- Be careful what you do with labels  [Labels in inputs might not be such a good idea](http://laurakalbag.com/labels-in-input-fields-arent-such-a-good-idea/)
- How are you communicating the current page? [The accessible current page link conundrum](http://www.heydonworks.com/article/the-accessible-current-page-link-conundrum)
- No one needs a carousel, but if you ignore me, here's some instructions on getting them to work accessibly [Carousels and aria tabs](http://www.webaxe.org/carousels-and-aria-tabs)
- Since very few people understand the accessibility guidelines fully, the BBC have provided us with a simplified version [Best practice accessibility guidelines](http://www.bbc.co.uk/guidelines/futuremedia/accessibility/)

##2. Content

- Have all design decisions enhanced and emphasized the content? [Interesting facts make web pages compelling](http://www.nngroup.com/articles/write-interesting-facts/)
- Are you chunking content to allow for skim reading and ease of re-use? [Don't let paper paradigms drive your digital strategy](http://blogs.hbr.org/2013/06/dont-let-paper-paradigms-drive/)
- Embraced high quality writing? [Website reading](http://www.nngroup.com/articles/website-reading/), [Blah-blah text - keep,cut or kill](http://www.nngroup.com/articles/blah-blah-text-keep-cut-or-kill/)
- Has the content driven the design decisions, or has it been visa versa?
- Have you focused on cutting down to just the important stuff on the homepage instead of trying to cram everything on the one page? [Minimize cognitive load](http://www.nngroup.com/articles/minimize-cognitive-load/)
- Have you revisited the hierarchy of important information? [Content priority guide](http://seesparkbox.com/foundry/content_priority_guide)
- Are you hiding useful content for people because you assume they won’t use it?  [Content parity](http://gomakethings.com/content-parity-on-the-web/), [State of mobile web sources](http://karenmcgrane.com/2013/06/13/state-of-the-mobile-web-sources/)
- If you’re using a CMS is it set up for multiple types of headline so the important headline doesn’t get truncated randomly?
- Do you really need that image carousel or is it just politically convenient? [Auto-Forwarding Carousels annoy users and Reduce visibility](http://www.nngroup.com/articles/auto-forwarding/), [Three ideas that convert better than a carousel](http://econsultancy.com/au/blog/62715-three-ideas-that-convert-better-than-a-standard-carousel), [Carousel interaction stats (updated)](http://weedygarden.net/2013/07/carousel-interaction-stats/), [Carousels](http://bradfrostweb.com/blog/post/carousels/), [Designing effective carousels](http://www.nngroup.com/articles/designing-effective-carousels/)
- How are you dealing with large infographics or tables?
- Have you organised tables based on how people will use the info? [Picking a responsive tables solution](http://blog.cloudfour.com/picking-responsive-tables-solution/)
- How are you dealing with video, both in scale and bandwidth? [Fitvid.js](http://fitvidsjs.com/)
- How are you dealing with maps? [Responsive maps](http://trentwalton.com/2013/04/11/responsive-maps/), [Adaptive maps](http://bradfrostweb.com/blog/post/adaptive-maps/)


##3. Usability

- Can you perform the main tasks of a site on any device? [Impact of responsive designs](http://www.lukew.com/ff/entry.asp?1691)
- Are you making assumptions about portable device usage? [When and where are people using mobile devices](http://www.lukew.com/ff/entry.asp?1263)
- Are the button hit areas large enough (min 44px) for a finger/thumb? [Apple's guidelines](http://developer.apple.com/iphone/library/documentation/UserExperience/Conceptual/MobileHIG/DesigningNativeApp/DesigningNativeApp.html#//apple_ref/doc/uid/TP40006556-CH4-SW1), [Windows guidelines](http://go.microsoft.com/?linkid=9713252), [Nokia's Guidlines](http://library.developer.nokia.com/index.jsp?topic=/S60_5th_Edition_Cpp_Developers_Library/GUID-5486EFD3-4660-4C19-A007-286DE48F6EEF.html)
- Have you got feature detection? Can your site/app tell the difference between a click and a tap? a swipe? [Modernizr](http://modernizr.com/), [Modernizr server](https://github.com/jamesgpearce/modernizr-server)
- If something required click drag, did you cover swipe?
- Are you making the visitor wait 300ms for a tap gesture? [Avoiding the 300ms click delay](http://timkadlec.com/2013/11/Avoiding-the-300ms-click-delay-accessibly/)
- Are you aware of the different quirks between iOS to Android to Windows Phones? [CanIuse](http://caniuse.com/)
- Not using unicode for hamburger menus (Android will not render)? [Unicode hamburger does not work](https://twitter.com/davatron5000/status/341646818926530560)
- Will a tap-drag (selection of text) cause a problem with your interface?
- If you used a fixed header on your site, did you try pinching your site to see if it’s still good on a smaller device? [Fixed position](http://bradfrostweb.com/blog/mobile/fixed-position/), [Mobile web problems](http://bradfrostweb.com/blog/post/mobile-web-problems/)
- How are you dealing with complex navigation? If you have a massively complex site structure have you provided in site search? [Responsive navigation patterns](http://bradfrostweb.com/blog/web/responsive-nav-patterns/)
- If you're using offscreen navigation, have you put a containing div for the overflow hidden to deal with the Android body overflow hidden issue?
- Have you designed with thumb flow in mind? [Designing for thumb flow](http://www.lukew.com/ff/entry.asp?1734)
- Are you relying on hover for anything? [Non hover](http://trentwalton.com/2010/07/05/non-hover/)
- Are you expecting the user to make discoveries without signposts? (eg. Swipe without any indication that they can swipe) [Don't make me think](http://www.sensible.com/dmmt.html), [Just in time education](http://www.lukew.com/ff/entry.asp?1786)
- Are you hijacking the experience with scroll, with modals? [Hijacking scroll](http://trentwalton.com/2013/10/23/scroll-hijacking/), [Bullshit overlays](http://bradfrostweb.com/blog/post/bullshit-overlays/)
- Are you embracing progressive enhancement for devices and browsers with less features? [Progressive enhancement](http://adactio.com/journal/1700/), [Progressive enhancement, it's about the content](http://cognition.happycog.com/article/progressive-enhancement-its-about-the-content), [A plea for progressive enhancement](http://stephanierieger.com/a-plea-for-progressive-enhancement/)
- Have you trapped visitors in iframe purgatory on tap gesture devices? [Responsive iframe](http://npr.github.io/responsiveiframe/)
- Have you trapped visitors in infinite scrolling hell? [Why infinite scrolling sucks](http://frontand.de/why-infinite-scrolling-sucks/)
- If you use pagination, do you allow users to view all? [Users' pagination preferences and 'View all'](http://www.nngroup.com/articles/item-list-view-all/)
- How have you determined what browsers and devices you've optimized for and what browsers and devices you simply support? [Support Vs. Optimization](http://bradfrostweb.com/blog/mobile/support-vs-optimization/)

##4. Forms and Form controls

- Are the requirements clear, and have you removed any unnecessary requirements? [What impacts web form conversion](http://www.lukew.com/ff/entry.asp?1416)
- Reduced the number of fields? Is all the data you’re making them input really necessary? [Case Study: Fewer input fields increases conversion](http://www.lukew.com/ff/entry.asp?910)
- Are your errors clear and in non-programmer language?
- Do you actually expect people to be able to use Captcha on a phone?
- Have inline validation? Realtime feedback? [Inline validation in web forms](http://alistapart.com/article/inline-validation-in-web-forms)
- Are you making use of the number pad on smaller phone style portable devices? [Better numerical input for mobile forms](http://bradfrostweb.com/blog/mobile/better-numerical-inputs-for-mobile-forms/)
- Are you making passwords hidden or visible for smaller devices? [Mobile design details: hide/show passwords](http://www.lukew.com/ff/entry.asp?1653=)
- How are you handling select boxes with massive amounts of options?
- If you have a number stepper (input range), is it the standard up down that’s difficult to tap?

##5. Typography

- Can you read the type clearly? [I'm sick of your tiny, tiny type](http://jxnblk.tumblr.com/post/41796724549/im-sick-of-your-tiny-tiny-type)
- On larger screens is your line length limited to (roughly) 75 chars? [The Elements of Typographic Style](http://www.amazon.com/Elements-Typographic-Style-Robert-Bringhurst/dp/0881792063)
- Is the type size an equivalent of 15-25px? [Butterick's Practical Typography Summary of key rules](http://practicaltypography.com/summary-of-key-rules.html)
- Are you creating contrast between different typographic elements? (headlines, long form copy, lists etc) [Contrast through scale](http://typecast.com/blog/contrast-through-scale)
- Are your font-sizes and line-heights em/rem based?
- Considered screen distances? [Responsive typography: the basics](http://ia.net/blog/responsive-typography-the-basics/)
- Have you chosen appropriate font families for headlines and body copy?
- Did you look at how the font family rendered in different browser and devices?
- Does the type marry with the content it communicates?

#6. Viewport Flexibility

- Gone beyond the old Phone/Tablet/Desktop mentality?  [Responsive web design: missing the point](http://bradfrostweb.com/blog/web/responsive-web-design-missing-the-point/), [Screen Sizes](http://screensiz.es/phone), [In tablets, smaller is bigger](http://www.lukew.com/ff/entry.asp?1695), [The shifting tablet market](http://www.lukew.com/ff/entry.asp?1692)
- How does your site behave ‘between’ the media queries? [7 Habits of highly effective media queries](http://bradfrostweb.com/blog/post/7-habits-of-highly-effective-media-queries/#content), [The trouble with android](http://stephanierieger.com/the-trouble-with-android/)
- Are your media queries Em-based? [http://blog.cloudfour.com/the-ems-have-it-proportional-media-queries-ftw/](The ems have it - proportional media queries)
- Not relying on screen.width? [Screen.width is useless](http://www.quirksmode.org/blog/archives/2013/11/screenwidth_is.html)
- Have you considered using grids for your layout? [On responsive layouts and grids](http://dbushell.com/2013/03/19/on-responsive-layout-and-grids/), [Five simple steps to designing grid systems](http://www.markboulton.co.uk/journal/five-simple-steps-to-designing-grid-systems-preface)
- Have you embraced the unpredictable nature of new device sizes that don’t exist yet? [Future Friendly](http://futurefriendlyweb.com/)
- Have you let concepts of ‘the fold’ rest in the historical irrelevance it deserves? (AKA the fold for what screen?) [Why the fold is a myth](http://blog.kissmetrics.com/why-the-fold-is-a-myth/), [Life below 600](http://iampaddy.com/lifebelow600/), [UX Myth: people don't scroll](http://uxmyths.com/post/654047943/myth-people-dont-scroll), [As the page scrolls](http://www.uie.com/articles/page_scrolling), [Scrolling is easier than clicking](http://bokardo.com/archives/scrolling-easier-clicking/)
- If you used [window.MatchMedia](https://developer.mozilla.org/en-US/docs/Web/API/Window.matchMedia) at all, did you consider fallback for Windows phones? (or use a polyfill)? [MatchMedia.js polyfill](https://github.com/paulirish/matchMedia.js/)
- Considered how the site is viewed in embedded browsers (such as Facebook/Twitter on handsets) [Embedded mobile browser use](http://www.lukew.com/ff/entry.asp?1801)
- Is it technically responsive? [Defining responsiveness](http://blog.cloudfour.com/author/jason-grigsby/), [Responsive web design](http://alistapart.com/article/responsive-web-design/)

##7. Responsive Imagery

- Did you weep and question your life choices when you saw the state of responsive images? [The state of responsive images](http://html5doctor.com/responsive-images-end-of-year-report/)
- Have you got a responsive image solution? Does it display an image with JS turned off? [PictureFill.js polyfill](https://github.com/scottjehl/picturefill)
- Do you have a lazy load solution for larger pages with lots of images or data that’s not immediately needed? [Echo.js, simple Javascript lazy loading solution](http://toddmotto.com/echo-js-simple-javascript-image-lazy-loading/)
- Have you used SVGs (with PNG fallback) or Webfonts where you can?
- Have you sprited to reduce HTTP requests? [CSS Sprites](http://css-tricks.com/css-sprites/)
- Have you compressed all of your PNGs and JPGs? [Grunt imagemin](https://github.com/gruntjs/grunt-contrib-imagemin), [TinyPNG](https://tinypng.com/)
- Are you serving different sized images to different devices? [Responsive images](http://blog.cloudfour.com/responsive-imgs/)
- How are you dealing with Retina devices? [Compressive images](http://filamentgroup.com/lab/rwd_img_compression/)
- Maybe combining with a server side solution might help? [Adaptive images](http://adaptive-images.com/)

##8. Performance

- Have you set a performance budget? [Setting a performance budget](http://timkadlec.com/2013/01/setting-a-performance-budget/)
- Considered page load time and how it affects your visitors? [Loading time](http://blog.kissmetrics.com/loading-time/)
- Have you minimised HTTP requests to free up memory? [Google best practices](https://developers.google.com/speed/docs/best-practices/request)
- Have you minimised the repaints and reflows? [Repaints and reflows, manipulating the DOM responsibly](http://blog.letitialew.com/post/30425074101/repaints-and-reflows-manipulating-the-dom-responsibly)
- How many kb (or meg) are people downloading on portable devices? is it reasonable to have them download that much per page? [How to lose weight in the browser](http://browserdiet.com/), [Responsive design, & web page sizes](http://www.lukew.com/ff/entry.asp?1681)
- Did you order non blocking resources first? did you use async on the JS? [Script loading](http://www.html5rocks.com/en/tutorials/speed/script-loading/)
- Do you really need a framework for that thing or can you just use pure CSS or pure JS?
- If you’ve put the media queries in elements (a technique seen more with Sass/LESS) have you used a method to reorganise media queries to reduce code bloat? [Sass and media queries](http://thesassway.com/intermediate/responsive-web-design-in-sass-using-media-queries-in-sass-32), [Grunt combine media queries](https://npmjs.org/package/grunt-combine-media-queries), [Grunt uncss](https://github.com/addyosmani/grunt-uncss)
- Are you minifying the CSS/JS? Are you concatenating multiple files into single files?
- Are you using conditional loading? [Conditional loading](http://bradfrostweb.com/blog/post/7-habits-of-highly-effective-media-queries/#conditional-loading)
- Do you have a method to test the connection speed? [Using Javascript to estimate connection speed](http://decadecity.net/blog/2013/05/08/using-javascript-to-estimate-connection-speed)
- Did you gzip?
- Did you put your resources on CDNs where relevant?
- Did you run a bandwidth restriction tool to test how the site loads at different bandwidths? [Charles Proxy](http://www.charlesproxy.com/), [Slowy app](http://slowyapp.com/)
- Run tests on mobitest? or something like it? [Akamai mobile test](http://mobitest.akamai.com/m/index.cgi)
- Have you destroyed social button sleaze? or come up with a solution to replace social button sleaze with just links? [Sweep the sleaze](http://ia.net/blog/sweep-the-sleaze/), [Social count by the filament group](http://filamentgroup.com/lab/socialcount/)
- Considered not using Wordpress/Drupal/whatever and switching to a Static site generator? [Jekyll](http://jekyllrb.com/)
- Are you loading 3rd party content asynchronously? [How to lose weight in the browser - load 3rd party content asynchronously](http://browserdiet.com/#3rd-party-async)

##9. Kinetic

- Did you use animation to provide context to the interface? [Transitional interfaces](https://medium.com/design-ux/926eb80d64e3)
- [UI Animation and UX: A not-so-secret friendship](http://alistapart.com/article/ui-animation-and-ux-a-not-so-secret-friendship)
- [Web animation at work](http://alistapart.com/article/web-animation-at-work)
- Does the easing and timing match the personality of the interface?

##10. Testing

- [Starting an open device lab without breaking the bank](https://medium.com/product-design/a3ad4da66c02)
- [Test in real devices without breaking the bank](http://bradfrostweb.com/blog/mobile/test-on-real-mobile-devices-without-breaking-the-bank/)
- [Open device lab](http://opendevicelab.com/)
- [Open device lab in a suitcase](https://medium.com/p/122f87dac737)
- [BrowserStack](http://www.browserstack.com/start)
- [Node Browserify](https://github.com/substack/node-browserify)

##11. Deliverables

- [The post PSD era](http://danielmall.com/articles/the-post-psd-era/)
- [Style prototypes](http://seesparkbox.com/foundry/our_new_responsive_design_deliverable_the_style_prototype)
- [Element collages](http://danielmall.com/articles/rif-element-collages/)
- [Style tiles](http://styletil.es/)
- [Responsive deliverables](http://daverupert.com/2013/04/responsive-deliverables/)
- [Atomic design](http://bradfrostweb.com/blog/post/atomic-web-design/)
