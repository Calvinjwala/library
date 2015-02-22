# Sass
Our favorite CSS precompiler.

## Library
- [Alphabetical list of CSS Properties](http://ref.openweb.io/CSS/): I've never even heard of some of these.
- [Vocab](http://apps.workflower.fi/vocabs/): Explanations for everything... in French too!
- [Flexbox Cheatsheet](http://jonibologna.com/flexbox-cheatsheet/): Because this shit is confusing, damn it.
- [Shame.css](http://csswizardry.com/2013/04/shame-css/): Keep your hacks in a separate file where they're well documented. It just makes sense.
- [One, Two, Three](http://css-tricks.com/one-two-three/): How many CSS files should you have?
- [Sass Tip: The Double Ampersand Selector](http://blog.teamtreehouse.com/sass-tip-double-ampersand-selector): Fun tricks with the ampersand that I send to forget, noteably:
	```sass
	.selector {
	  .other-selector & {
	    background-color: tomato
	  }
	}

	// compiles to

	.selector { ... }
	.other-selector .selector { ... }
	```
- [All You Ever Need to Know About Sass Interpolation](http://webdesign.tutsplus.com/tutorials/all-you-ever-need-to-know-about-sass-interpolation--cms-21375): How it works and some useful examples.

## Tools
- [Shrthnd](http://shrthnd.volume7.io/): Concatenate your CSS selectors into their shorthand versions.
- [Colours](http://colours.neilorangepeel.com/): CSS colors have names and they can be pretty gorgeous.
- [UI Gradients](http://uigradients.com/#Portrait): Not sure where you could use these, but they're very pretty.
- [Flexplorer](http://bennettfeely.com/flexplorer/): Wrap your head around [Flexbox](https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Flexible_boxes).
- [Web Starter Kit](https://developers.google.com/web/starter-kit/): Google's boilerplate for multi-device development.


## Frameworks
- [Impulse](http://impulse.luster.io/): Physics animations.
