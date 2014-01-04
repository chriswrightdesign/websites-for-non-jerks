happy-website-checklist
=======================

A checklist for friendly websites (accessible, performant,  and portable device happy). Where possible I will provide a link to where I got the information/idea from.

#Accessibility

- Structured your markup well and in a way that makes sense?  [Semantic structure and why it's important](http://webaim.org/techniques/semanticstructure/)
- Considered contrast and colour blindness? [Colour blindness and contrast](http://www.visionaustralia.org/digital-access-cca)
- Hows your tab key going? unplug your mouse, use the site. [On basic accessibility testing](http://24ways.org/2013/coding-towards-accessibility/)
- Have you tested in Wave? [Wave accessibility tester](http://wave.webaim.org/)
- Tested with ChromeVox? (or JAWS if you have the moneys). [ChromeVox](http://www.chromevox.com/), [JAWS](http://www.freedomscientific.com/products/fs/jaws-product-page.asp)
- Have you used WAI-Aria landmark roles correctly? [Using WAI-Aria landmark roles](http://blog.paciellogroup.com/2013/02/using-wai-aria-landmarks-2013/)

#Content

- Have all decisions enhanced and emphasized the content?
- Are you chunking content to allow for skim reading and ease of re-use?
- Has the content driven the design decisions, or has it been visa versa?

#Usability

- Can you perform the main tasks of a site on any device?
- Are the button hit areas large enough (min 44px) for a finger/thumb? [Apple's guidelines](http://developer.apple.com/iphone/library/documentation/UserExperience/Conceptual/MobileHIG/DesigningNativeApp/DesigningNativeApp.html#//apple_ref/doc/uid/TP40006556-CH4-SW1), [Windows guidelines](http://go.microsoft.com/?linkid=9713252), [Nokia's Guidlines](http://library.developer.nokia.com/index.jsp?topic=/S60_5th_Edition_Cpp_Developers_Library/GUID-5486EFD3-4660-4C19-A007-286DE48F6EEF.html)
- Have you got feature detection? Can your site/app tell the difference between a click and a tap? a swipe? [Modernizr](http://modernizr.com/)
- If something required click drag, did you cover swipe?
- Are you making the visitor wait 300ms for a tap gesture? [Avoiding the 300ms click delay](http://timkadlec.com/2013/11/Avoiding-the-300ms-click-delay-accessibly/)
- Are you aware of the different quirks between iOS to Android to Windows Phones? [CanIuse](http://caniuse.com/)
- Not using unicode for hamburger menus (Android will not render)? [Unicode hamburger does not work](https://twitter.com/davatron5000/status/341646818926530560)
- Will a tap-drag (selection of text) cause a problem with your interface?
- If you used a fixed header on your site, did you try pinching your site to see if it’s still good on a smaller device? [Fixed position](http://bradfrostweb.com/blog/mobile/fixed-position/)
- How are you dealing with complex navigation? If you have a massively complex site structure have you provided in site search?
- If you're using offscreen navigation, have you put a containing div for the overflow hidden to deal with the Android body overflow hidden issue?
- Are you relying on hover for anything? [Non hover](http://trentwalton.com/2010/07/05/non-hover/)
- Are you expecting the user to make discoveries without signposts? (eg. Swipe without any indication that they can swipe) [Don't make me think](http://www.sensible.com/dmmt.html)
- Are you hijacking scroll, or hijacking the screen with modals? [Hijacking scroll](http://trentwalton.com/2013/10/23/scroll-hijacking/)
- Are you embracing progressive enhancement for devices and browsers with less features? [Progressive enhancement](http://adactio.com/journal/1700/)

#Forms and Form controls

- Reduced the number of fields? Is all the data you’re making them input really necessary?
- Are your errors clear and in non-programmer language?
- Do you actually expect people to be able to use Captcha on a phone?
- Have inline validation? Realtime feedback?
- Are you making use of the number pad on smaller phone style portable devices?
- Are you making passwords hidden or visible for smaller devices?
- How are you handling select boxes with massive amounts of options?
- If you have a number stepper, is it the standard up down that’s difficult to tap?

#Typography 

- Can you read the type clearly? on larger screens is your line length limited to (roughly) 75 chars?
- Are your font-sizes and line-heights em/rem based?

#Screen Size

- How does your site behave ‘between’ the media queries?
- Are your media queries Em-based?
- Have you considered using grids for your layout?
- Have you embraced the unpredictable nature of new device sizes that don’t exist yet?
- Have you let concepts of ‘the fold’ rest in the historical irrelevance it deserves? (AKA the fold for what screen?)
- If you used window.MatchMedia at all, did you consider fallback for Windows phones? (or use a polyfill)?

#Responsive Imagery

- Did you weep and question your life choices when you saw the state of responsive images?
- Have you got a responsive image solution? Does it display an image with JS turned off?
- Do you have a lazy load solution for larger pages with lots of images or data that’s not immediately needed?
- Have you used SVGs (with PNG fallback) or Webfonts where you can?
- Have you sprited to reduce HTTP requests?
- Have you compressed all of your PNGs and JPGs?
- Are you serving different sized images to different devices?
- How are you dealing with Retina devices?

#Performance

- Have you set a performance budget?
- Considered page load time and its effects on your visitors?
- Have you minimised HTTP requests to free up memory?
- Have you minimised the repaints and reflows?
- How many kb (or meg) are people downloading on portable devices? is it reasonable to have them download that much per page?
- Did you order non blocking resources first? did you use async on the JS?
- Do you really need a framework for that thing or can you just use pure CSS or pure JS?
- If you’ve put the media queries in elements (a technique seen more with Sass/LESS) have you used a method to reorganise media queries to reduce code bloat?
- Are you minifying the CSS/JS? Are you concatenating multiple files into single files?
- Are you using conditional loading?
- Did you gzip?
- Did you put your resources on CDNs where relevant?
- Did you run a bandwidth restriction tool to test how the site loads at different bandwidths?
- Run tests on mobitest? or something like it?
- Have you destroyed social button sleaze? or come up with a solution to replace social button sleaze with just links?
- Considered not using Wordpress/Drupal/whatever and switching to a Static site generator?

#Kinetic


