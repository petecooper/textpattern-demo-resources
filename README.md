# Textpattern CMS demo site resources

Work in progress.

## Images
Images are public domain, [CC0](https://creativecommons.org/share-your-work/public-domain/cc0/) licensed at the time of committing and sourced from:

* [Pixabay](https://pixabay.com)
* [Pexels](https://www.pexels.com)

Downloaded originals are housed in [/source/images/](https://github.com/pragmatika/textpattern-demo-resources/tree/master/source/images). Processed images ready for use can be found in [/dist/images/](https://github.com/pragmatika/textpattern-demo-resources/tree/master/dist/images).

### Image sizes
All images are derived from the highest resolution or original file. Processed image filenames have the following format/namespace:

* Photographs: `scene_size_#widthx#height_#dpi_#qualitypc.[jpg|webp]` (e.g. `farm_base_2000x1500_300dpi_80pc.jpg`, `house_base_2000x1000_300dpi_80pc.webp`)
* Illustrations: `scene_size_#widthx#height_#dpi(_#qualitypc).[png|webp]` (e.g. `shop_base_2000x500_300dpi.png`, `car_base_2000x2000_300dpi_80pc.webp`)
* Vectors: `scene.svg` (e.g. `logo.svg`)

JPG and WebP filenames indicate export quality (80%), PNG and SVG files are considered lossless and don't have an export quality. PNG optimisation in [ImageOptim](https://imageoptim.com/) should only include lossless algorithms.

### Raster image specifications

| Size | Long edge | DPI | Quality | Optimisation |
|---|---|---|---|---|
| `base` | 2000px | 300 | 80% | [ImageOptim](https://imageoptim.com/) |
