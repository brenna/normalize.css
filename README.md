# normalize.css v2.0.1 - Sassified!

A Sass version of normalize.css.

## Why did I make this?

Normalize.css is my go to browser baseline (instead of a traditional kill everything reset), but I also like writing all my css with Sass. I often found myself overwriting normalize settings in other scss files, or having to modify the normalize file without having access to my usual Sass variables. That defeated the purpose of using Sass to help organize and reduce the size of my stylsheets. So I converted several baseline values that you might want to customize into Sass variables.

## Usage

@import normalize.sccs as you see fit in your Sass project, though you'll typically do that at the beginning. If you're happy with normalize's defaults, you're done! If you'd like to customize, simply change the variable values found at the beginning of normalize.scss. If you've

## Browser Support

Same as normalize.css:

* Browser support
* Google Chrome
* Mozilla Firefox 4+
* Apple Safari 5+
* Opera 12+
* Internet Explorer 8+

## Futher Details

Check out the original [normalize.css documentation](https://github.com/necolas/normalize.css/
) for more details on how it works.
