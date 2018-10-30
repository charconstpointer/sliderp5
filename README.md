# slider p5.js
Canvas integrated slider
```javascript
Slider slider = new Slider(x, y, width, height, r, g, b, alpha);
```
where x and y are location on the canvas, and rgba are the color values of the slider.

#To get slider value use getRGBValue(), which returns value between 0-255, but can be easily tweaked for your needs.
```javascript
slider.getRGBValue()
```
