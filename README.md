# Seamless
A script that checks a pattern's edges for repeatability.

## Requirements

Requires the user to run an AMP stack to get around Cross-Site Request Forgery (CSRF).

If you're running on a Mac, I recommend MAMP.

If you're running on Windows, XAMPP should do the trick.

## Limitations

The way that the image is loaded into the canvas, it distorts to fit a predifined square.  
This causes some of the calculations to be a little off, but still gives a general idea 
for whether the top and bottom or left and right pixels match.

## Future improvements

Fixing the aforementioned problem with canvas restrictions.
Code is in serious need of refactoring for accuracy and DRYness.
Drag and drop into the canvas from an OS file browser would be a cool feature.
