This OpenSeadragon ( http://openseadragon.github.io/ ) plugin add a method
to the viewer to get the color of a pixel.

A demo is available here: http://nistdeepzoom.github.io/OpenSeadragonPixelColor/

It can be used like this:
`````javascript
var viewer = new OpenSeadragon.Viewer(...);
var color = viewer.getPixelColor(myPixel);
var red = color[0];
var green = color[1];
var blue = color[2];
`````

The pixel coordinates must be relative to the viewer element.

Disclaimer:

This software was developed at the National Institute of Standards and
Technology by employees of the Federal Government in the course of
their official duties. Pursuant to title 17 Section 105 of the United
States Code this software is not subject to copyright protection and is
in the public domain. This software is an experimental system. NIST assumes
no responsibility whatsoever for its use by other parties, and makes no
guarantees, expressed or implied, about its quality, reliability, or
any other characteristic. We would appreciate acknowledgement if the
software is used.
