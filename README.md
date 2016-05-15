# node-sdl-mixer-prebuilt

Provides prebuilt versions of [SDL2_Mixer](https://www.libsdl.org/projects/SDL_mixer/). When loaded, will return the path to your platform's version of the PhysFS library.

## Usage

``` javascript
var mixer = require('node-sdl-mixer-prebuilt')
// => 'node_modules/node-sdl-mixer-prebuilt/linux/x64/SDL2_mixer'
