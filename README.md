# js13k-polyhedron

### MVP TODO ###
* X Pick a random face to remove
* X Grow a shape exponentially
* XHave a game timer manage shapes/scales/colors
* XDetect hits - Raycast self;
* XReset/New Game/Game Over states
* XGame Menu - Instructions, score, best
* XMake the intro shape float (this is important)
* XMore sounds


### BONUS TODO ###
* Wireframe - Make PNG texture, set UVs OR make another wireframe mesh
* Style - Faster shapes, but same time to find hole
* More sound/music to break monotony
* Allow full 3d rotation

# js13k-toolkit
A simple little tool for developing a JS game while keeping it under 13kb zipped

Run `gulp init` to create a simple folder structure.

Run `gulp watch --silent` (silent optional) to have gulp continuously build your project and check it's compressed zip file size. A warning will be printed if you exceed 13312 bytes (13kb) to ensure you're under the limit for the js13kgames competition.

Feel free to edit the gulpfile to suit your specific needs.
