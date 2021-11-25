gl1.js

A webGL 2D graphics library.

Designed and optimized for 2D web games where all the graphics fit into 1 PNG.

Try the example:
https://curtastic.com/gl/

Try speed test with 100,000 images:
https://curtastic.com/gl/speedtest.html?max=100000

Features:
- Real time rotation, without slowdown.
- Real time semi-transparent drawing, without slowdown.
- Real time color tinting/brightening, without slowdown.
- Renders 50,000 moving images with real time rotation, tinting, and transparency at 60FPS on an old iPhone SE 2015.
- Works like a regular canvas where you draw images in the order you want. When you want to remove something, simply stop drawing it.
- You can pass in a canvas instead of a PNG, alter the pixels of your canvas, and reload it into webGL's texture quickly.
- Supports old devices/browsers including IE11 and iOS9.
- Only 4KB minified.
- Fully commented code.

Does not include:
- No hue-shift effect, blur effects, or Skew/3D effects.
- No rotate about a point that isn't the image's center. But you can do that with your own math before passing drawX/drawY.
- No camera object. But you can offset things yourself if you want scrolling.
- No drawing other primitive shapes besides images and rectangles.
- No font or svg support.
