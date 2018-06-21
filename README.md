# Spritesheet-Gif-Generator
A Node app that converts a horizontal png sprite strip into an animated gif.

## Installation
- Install [Node and npm](http://nodejs.org)
- Clone the repository
- Install the application using `npm install`

## Usage
- The source png file must be a series of evenly spaced frames horizontally.
- Run using `node script.js`
- You can either convert a single png, or all in a folder at once.
- By default, `framewidth` will be the image's height, but can be set manually if a frame's width is not the same as the height.
- Use `framerate` to set the frames-per-second of an animated gif.
