# sharp gallery
The project consist of a web-based,full featured - but still (fucking) simple - standalone photo gallery software.

## but why ? facts.
I've made intensive research and testing on the current open-source offer. Every photo gallery software around there have serious drawbacks, at least to me. Without naming those projects, here are where they fail:
- SQL backend !? Again ? :rage:
- :disappointed: Ugly and old looking
- Not responsive :rage:
- Not maintained :unamused:
- Gallery management and settings are too complex :tired_face:
- Buggy "upload" feature :expressionless:

## Philosophy
For "the best" to happen I have thought of some basic guidelines and wishes:
- Open source
- No database
- It should be simple and intuitive to install and operate
- It has to look simple and beautiful at the same time. (=minimalist)
- We wont reinvent the wheel : it means we'll try to reuse existing components if it exists and fit the need

## Must have features
- Responsiveness
- Albums and sub-albums (or collections)
- Albums password protection
- Takes a photo directory tree as source.
- EXIF metadata support, and by that I mean *full* support

## Components, ressources and inspiration
The common inspiration is https://medium.com/@jtreitz/the-algorithm-for-a-perfectly-balanced-photo-gallery-914c94a5d8af#.f51xvq11g. From there I found the following:

 - https://sitemarina.github.io/guggenheim/ - is a gallery plugin for Kirby CMS. Looks beautiful but isn't open-source.
 - it is inspired from http://www.chromatic.io/ - This is pretty much how I want the images to appear
 - https://medium.com/@jtreitz/the-algorithm-for-a-perfectly-balanced-photo-gallery-914c94a5d8af#.f51xvq11g literature about how the chromatic gallery was made, very useful

 - Another implementation of the linear gallery, still inspired by chromatic
https://medium.com/swlh/in-search-of-the-perfect-image-gallery-34f46f7615a1#.n6gwrfy9q
