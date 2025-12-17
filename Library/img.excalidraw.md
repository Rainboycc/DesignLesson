---
excalidraw-plugin: parsed
tags:
  - excalidraw
excalidraw-onload-script: 'icons = app.vault.getFiles() .filter(f => f.extension !== "md" && f.basename.toLowerCase().contains("img")) .sort((a, b) => a.basename.toLowerCase() < b.basename.toLowerCase() ? -1 : 1);numberOfColumns = 6;HEIGHT = 100;WIDTH = 100;PADDING = 20;ea.getExcalidrawAPI().resetScene();column = 0;row = 0;for (icon of icons) { id = await ea.addImage( column * (WIDTH + PADDING), row * (HEIGHT + PADDING), icon ); el = ea.getElement(id); ratio = el.width / WIDTH; if (el.height / ratio > HEIGHT) ratio = el.height / HEIGHT; el.width = el.width / ratio; el.height = el.height / ratio; if (++column === numberOfColumns) { row++; column = 0; }}await ea.addElementsToView();ea.getExcalidrawAPI().zoomToFit();ea.getExcalidrawAPI().updateScene({ appState: { viewModeEnabled: true }});'
---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠== You can decompress Drawing data with the command palette: 'Decompress current Excalidraw file'. For more info check in plugin settings under 'Saving'


# Excalidraw Data

## Text Elements
## Embedded Files
bc5751a874952d255762aaae21b2d0dcfe1bae9e: [[img-拖延.png]]

848cd366e9611fa342213800e4ec8cf9ac97610b: [[img-时光倒流.png]]

3dd696c89216c1331a87fff972ea9bb950bce39c: [[img-焦虑.png]]

c61c352a64d1d039300b10e81812bfe25db3ce11: [[img-航海.png]]

c8e7e9fb5602028bd9a7bbec4a19ff9fc5a2e735: [[img-踩坑.png]]

f3d14904fc198b784e996f961a5de03a8cb0e54d: [[img-迷茫.png]]

%%
## Drawing
```compressed-json
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
```
%%