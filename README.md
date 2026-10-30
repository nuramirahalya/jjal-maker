# 짤 만들기 (Meme Maker)

A small web app for making Korean-style captioned images (짤).

## Features
- Upload, drag-and-drop, or paste (Ctrl+V) a background image
- Multi-line captions with 5 Korean Google Fonts
- Adjustable font size, vertical position, and outline thickness
- Colour presets
- Download the result as a PNG

## Tech
Plain HTML, CSS, and JavaScript. Text is drawn onto an HTML `<canvas>` and exported with `canvas.toBlob()`. No build step or dependencies.

## Run locally
Open `index.html` in a browser.
