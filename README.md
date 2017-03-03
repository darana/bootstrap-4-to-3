# bootstrap-4-to-3
A few of the useful Bootstrap 4 components adapted for existing Bootstrap 3 projects

## General

The main change is to handle the new breakpoints. In order to do so I just added a new size called "-ss-" (super small!) and adjusted everything down. So the default bootstrap for SM is now SS, MD is now SM, LG is now MD, and XL is now L. This way everything just matches the current break points.

Otherwise you break ALL the things


### Flexbox

File: bootstrap-4-to-3__flexbox.css

I love you flexbox

### Spacing classes

File: bootstrap-4-to-3__spacing.css

So simple and obvious to just make a global set of standard padding and margin classes. Me like.
These lines are compressed (not .min) since I don't really need to see all of the options, but double checking what rem each number is is super helpful, and it only takes up a few lines of the css file this way.