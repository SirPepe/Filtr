Filtr
=====

Simplistic but performant filters for canvas. MIT license.

How to use
----------

    filtr(canvasElement).sepia(50).saturation(80).brightness(20).render();

API reference
-------------

* `filtr(canvasElement)` - Initialize
* `filtr.updateSource()` - Overwrite cached image data with what's currently on the canvas
* `filtr.revertSource()` - Revert to cached image data
* `filtr.brightness(amount)` - Brightness filter
* `filtr.contrast(amount)` - Contrast filter
* `filtr.saturation(amount)` - Saturation filter
* `filtr.sepia(amount)` - Sepia effect
* `filtr.render()` - Render the result of the current operation