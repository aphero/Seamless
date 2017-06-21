# Seamless
A script that checks a pattern's edges for repeatability.

## Requirements

Requires the user to run an AMP stack to get around Cross-Site Request Forgery (CSRF).

If you're running on a Mac, I recommend MAMP.

If you're running on Windows, XAMPP should do the trick.

## Limitations

The way the image is loaded into the canvas will distort it to fit a predifined square canvas.  This causes some of the calculations to be a little off, but still gives a general idea for whether the top and bottom or left and right pixels match.  The better way would be to read the file and adjust the canvas to accomodate the full image dimensions.  The reason for the square was to have a predictable amount of pixels to read.  Lazy.  So lazy.

## Future improvements

* Fixing the aforementioned problem with canvas restrictions.
* Code is in serious need of refactoring for accuracy and DRYness.
* Drag and drop into the canvas from an OS file browser would be a cool feature.
