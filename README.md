# canvas2image

Canvas2Image cannot be imported as a module and seems to no longer be maintained.

This repository contains the original code, a few changes for fileName and a export statement.

### Usage
```bash
npm install canvas-to-png
```

```js
import Canvas2image from "canvas-to-png";

Canvas2image.convertToPNG(canvas, 400, 400);
Canvas2Image.saveAsImage(canvasObj, width, height, type,fileName)
Canvas2Image.saveAsPNG(canvasObj, width, height)
Canvas2Image.saveAsJPEG(canvasObj, width, height)
Canvas2Image.saveAsGIF(canvasObj, width, height)
Canvas2Image.saveAsBMP(canvasObj, width, height)

```