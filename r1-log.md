# 100 Days Of Code - Log

## R1D1: 28 November 2018

### Today's Progress
  * Forked original 100-days-of-code repository and created new repo not linked to the original so that my work shows up on GitHub's activity chart.
  * Started to implement the [Auto-Expanding Textarea](https://codepen.io/VAggrippino/pen/YRaeya) for [donot-link-this](https://github.com/VAggrippino/donot-link-this)

### Thoughts
  * My alternate version of 100 Days Of Code should be a good thing for me, but we'll see if anyone gets upset.
  * The autoExpand code is triggering too early. I can't figure why right now. It should only trigger a change when the height of the `textarea` content changes

### Links to work
  * [VAggrippino/100-days-of-code](https://github.com/VAggrippino/100-days-of-code)
  * (not committing broken code to donot-link-this)


## R1D2: 29 November 2018

### Today's Progress
  * Figured out a way to debug a webpack bundle for the textarea auto-expand code in [donot-link-this](https://github.com/VAggrippino/donot-link-this)
  * Identified source of problem in textarea auto-expand code and corrected it in [donot-link-this](https://github.com/VAggrippino/donot-link-this) and [on CodePen](https://codepen.io/VAggrippino/pen/YRaeya)
  * Fully implemented Auto-Expanding textarea in [donot-link-this](https://github.com/VAggrippino/donot-link-this) and corrected a few other minor problems in both this project and the Auto-Expanding textarea code.
  * Implemented [Lodash's `debounce`](https://lodash.com/docs/4.17.11#debounce) ([via npm](https://www.npmjs.com/package/lodash.debounce)) for updating the automatically linked output in [donot-link-this](https://github.com/VAggrippino/donot-link-this).

### Thoughts
  * Debugging the webpack bundle was easier than I thought, but there's still a lot to figure out and probably a better way to do it.
  * CSS defaults can be a pain in the butt.
  * I need to move the textarea auto-expand code to a GitHub repo of its own. Even though it's a very small utility, it's definitely reusable and changes should be tracked properly.

### Links to work
  * [donot-link-this](https://github.com/VAggrippino/donot-link-this) - GitHub
  * [Auto-Expanding textarea](https://codepen.io/VAggrippino/pen/YRaeya) - GitHub


## R1D3: 30 Nov 2018

### Today's Progress:
  * Finished Hashes section of App Academy Introduction to Programming
  * [Don't Link This](https://github.com/VAggrippino/donot-link-this) - Committed first draft of bookmarklet implementation with the help of babeljs.io minifier.

### Thoughts:
  * Although App Academy is well regarded, I have very little confidence that completing this curriculum will, by itself, help in the job search process. I'm doing it just for the community involvement.
  * There's gotta be a way to minify the JS and insert it into the HTML as a bookmarklet as part of the build process. Copy/paste from the output of the online tool isn't a long-term solution.
  * The bookmarklet works perfectly on Twitter, but not at all on Facebook.
  * On Fb it weirdly duplicates some blocks of text instead of replacing them.
  * What looks like a contiguous block of text on Fb is actually a complicated mess of `div`s and `span`s.
  * Even if I wrote code to accommodate the current Fb post structure, they could change it at any time. I may have to implement some simple interface even for the bookmarklet version of the code and require manual copy / pasting.

### Links to Work:
  * [App Academy Open](https://open.appacademy.io/) (There's no way to publicly link to my profile)
  * [[donot-link-this] commit 114207c](https://github.com/VAggrippino/donot-link-this/commit/114207c3824ed42ce9ba6489d83cee71e7931409)


## R1D4: 01 Dec 2018

### Today's Progress:
  * Halfway through the last section of App Academy's "Introduction to Programming" course.
  * Finished a rudimentary UI for the  [Don't Link This](https://github.com/VAggrippino/donot-link-this) bookmarklet. Now it will work on Facebook, but the user has to manually copy/paste from this UI's textarea.

### Thoughts:
  * Maybe App Academy will get more interesting after I finish the Introduction course.
  * Do I need to worry about the size of the bookmarklet? It's currently over 800 bytes.
  * I should probably add a button to the Don't Link This bookmarklet UI that will allow it to automatically replace the highlighted text. This won't work on Fb, but it'll work on other services.

### Links to Work:
  * [Add a UI to the bookmarklet to allow manual copy/paste](https://github.com/VAggrippino/donot-link-this/commit/97f782f7c0ea4cb96c0cc6e0a5c977ae980fc54f)


## R1D5: 04 Dec 2018

### Today's Progress:
  * A lot of reading about Chrome extension implementation.
  * Completed functional first alpha of the Chrome extension.

### Thoughts:
  * A few days have passed without being able to work on a real project... family. I've still been making steady progress on AppAcademy, though.
  * I need to look closely at other Chrome extensions. What I've created here feels very rough.

### Links to Work:
  * [Add first draft of chrome extension](https://github.com/VAggrippino/donot-link-this/commit/cbea8946a407fc5c3abab829602eecce46366a87) 


## R1D6: 06 Dec 2018

### Today's Progress:
  * A lot of reading about Firefox extension development only to find out that the [WebExtensions](https://wiki.mozilla.org/WebExtensions) API allows me to use the same code for both Chrome and Firefox.
  * Changed [Don't Link This!](https://github.com/VAggrippino/donot-link-this) Chrome extension slightly to make it compatible with Firefox as well. Now the same extension code works with both Google Chrome and Mozilla Firefox.
  * Updated Don't Link This logo and generated favicons using [realfavicongenerator.net](https://realfavicongenerator.net).
  * Did a [subtree push](https://gist.github.com/cobyism/4730490) to host the [Don't Link This! site](https://vaggrippino.github.io/donot-link-this/) from the `dist` folder.

### Thoughts:
  * The Don't Link This page still needs design... badly.
  * I need to use the extensions for a while before I attempt to publish the extensions. It wouldn't be good to publish the extensions only to get a bunch of 1-star reviews because I missed something stupid.

### Links to Work:
  * [Make minor change to manifest.json for Firefox compatibility](https://github.com/VAggrippino/donot-link-this/commit/4ddb7055b70d85d51ab0e30fd50298409d0f1ec1)
  * [Update logo and add generated favicons](https://github.com/VAggrippino/donot-link-this/commit/b523578b6a8323794472fef50a7e84436bcc295e)
    ![Don't Link This! logo](https://gitcdn.link/repo/VAggrippino/donot-link-this/master/src/images/logo.svg)
  * [Don't Link This!](https://vaggrippino.github.io/donot-link-this/) - the site
