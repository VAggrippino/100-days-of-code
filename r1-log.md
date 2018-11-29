# 100 Days Of Code - Log

## R1D1: 28 November 2018

### Today's Progress:
  * Forked original 100-days-of-code repository and created new repo not linked to the original so that my work shows up on GitHub's activity chart.
  * Started to implement the [Auto-Expanding Textarea](https://codepen.io/VAggrippino/pen/YRaeya) for [donot-link-this](https://github.com/VAggrippino/donot-link-this)

### Thoughts:
  * My alternate version of 100 Days Of Code should be a good thing for me, but we'll see if anyone gets upset.
  * The autoExpand code is triggering too early. I can't figure why right now. It should only trigger a change when the height of the `textarea` content changes

### Links to work:
  * [VAggrippino/100-days-of-code](https://github.com/VAggrippino/100-days-of-code)
  * (not committing broken code to donot-link-this)


## R1D2: 29 November 2018

### Today's Progress:
  * Figured out a way to debug a webpack bundle for the textarea auto-expand code in [donot-link-this](https://github.com/VAggrippino/donot-link-this)
  * Identified source of problem in textarea auto-expand code and corrected it in [donot-link-this](https://github.com/VAggrippino/donot-link-this) and [on CodePen](https://codepen.io/VAggrippino/pen/YRaeya)
  * Fully implemented Auto-Expanding textarea in [donot-link-this](https://github.com/VAggrippino/donot-link-this) and corrected a few other minor problems in both this project and the Auto-Expanding textarea code.
  * Implemented [Lodash's `debounce`](https://lodash.com/docs/4.17.11#debounce) ([via npm](https://www.npmjs.com/package/lodash.debounce)) for updating the automatically linked output in [donot-link-this](https://github.com/VAggrippino/donot-link-this).

### Thoughts:
  * Debugging the webpack bundle was easier than I thought, but there's still a lot to figure out and probably a better way to do it.
  * CSS defaults can be a pain in the butt.
  * I need to move the textarea auto-expand code to a GitHub repo of its own. Even though it's a very small utility, it's definitely reusable and changes should be tracked properly.

### Links to work:
  * [donot-link-this](https://github.com/VAggrippino/donot-link-this) - GitHub
  * [Auto-Expanding textarea](https://codepen.io/VAggrippino/pen/YRaeya) - GitHub