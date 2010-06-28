# CSS-Only Lightbox-style close buttons

I was rolling my own lightbox JavaScript and needed a close button.
I realized that I didn’t really need an image as I began replacing
the one I had temporarily "borrowed" from a Google Image search 
(I'm a professional, I couldn't leave it like that!).

*	[Check out the demo here!][demo]
*	Ready-to-use CSS
*	LESS -- ready for your mixin pleasure -- included!

### Known Issues

The shadow size and offset does not vary with each button size.
This is due to a [bug in Less][known issue]. Manually correcting this is straightforward.


[known issue]: http://github.com/cloudhead/less/issues/issue/160/ "Variables set in dynamic mixins always use default argument value for calculations"
[demo]: http://alanhogan.com/files/CSS-only-close-button/demo.html