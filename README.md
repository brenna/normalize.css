
# normalize.scss v3

A Sass version of normalize.css with customizable variables.

# About normalize.css

Normalize.css is a customisable CSS file that makes browsers render all
elements more consistently and in line with modern standards.

The project relies on researching the differences between default browser
styles in order to precisely target only the styles that need or benefit from
normalizing.

[View the test file](http://necolas.github.io/normalize.css/latest/test.html)

## Usage

Place `_normalize.sccs` in your styles directory and import at the top of your main 
.scss style sheet:

```
@import normalize;
```

##Customization

Customize your baseline styles by changing the variable values found at the beginning of `_normalize.scss`. 

## Browser Support

Same as the current version (v3) of normalize.css:

* Google Chrome (latest)
* Mozilla Firefox (latest)
* Mozilla Firefox 4
* Opera (latest)
* Apple Safari 6+
* Internet Explorer 8+


## Further Details

Check out the original [normalize.css documentation](https://github.com/necolas/normalize.css/
) for more details on how it works.

## Why did I make this?
Normalize.css is my go to browser baseline (instead of a traditional kill everything reset), but I also like writing all my css with Sass. I often found myself overwriting normalize settings in other scss files, or having to modify the normalize file without having access to my usual Sass variables. That defeated the purpose of using Sass to help organize and reduce the size of my stylsheets. So I converted most of nomalize's baseline values into Sass variables for easy editing and re-use.
