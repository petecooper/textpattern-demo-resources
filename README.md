# Textpattern CMS demo site resources

Work in progress.

## Images
Images are sourced from [Pixabay](https://pixabay.com) and are public domain, [CC0](https://creativecommons.org/share-your-work/public-domain/cc0/) licensed at the time of committing.

Downloaded originals are housed in [/source/images/](https://github.com/pragmatika/textpattern-demo-resources/tree/master/source/images). Processed images ready for use can be found in [/dist/images/](https://github.com/pragmatika/textpattern-demo-resources/tree/master/source/images).

### Image sizes
All images are derived from the highest resolution or original file. Processed image filenames have the following format/namespace:

* Photographs: `scene_size_#widthx#height_#dpi_#qualitypc.[jpg|webp]`
* Illustrations: `scene_size_#widthx#height_#dpi(_#qualitypc).[png|webp]`
* Vectors: `scene.svg`

JPG and WebP file formats indicate export quality (typically 80%), PNG and SVG files formats are considered lossless and do not. PNG optimisation in [ImageOptim](https://imageoptim.com/) should only include lossless algorithms.

### Raster image specifications

| Size | Long edge | DPI | Quality | Optimisation |
|---|---|---|---|---|
| `base` | 2000px | 300 | 80% | [ImageOptim](https://imageoptim.com/) |
