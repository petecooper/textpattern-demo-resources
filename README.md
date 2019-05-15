# Textpattern CMS demo site resources

Work in progress.

## Images
Images are public domain, [CC0](https://creativecommons.org/share-your-work/public-domain/cc0/) licensed at the time of committing and sourced from:

* [Pixabay](https://pixabay.com)
* [Pexels](https://www.pexels.com)

Downloaded originals: [/source/images/](https://github.com/pragmatika/textpattern-demo-resources/tree/master/source/images).

Ready-to-use images: [/dist/images/](https://github.com/pragmatika/textpattern-demo-resources/tree/master/dist/images).

Thumbnails: [/dist/images/_thumbnails](https://github.com/pragmatika/textpattern-demo-resources/tree/master/dist/images/_thumbnails).

### Image sizes
Ready-to use images are derived from the highest resolution or original source file. Processed image filenames have the following namespace:

* Photographs & illustrations: `scene_derivative@density.[jpg|png|webp]` (e.g. `farm_base@1x.jpg`, `house_base@2x.webp`)
* Vectors: `scene.svg` (e.g. `logo.svg`)

JPG and WebP files use lossy compression, PNG and SVG files are considered lossless. PNG optimisation in [ImageOptim](https://imageoptim.com/) should only include lossless algorithms.

### Raster image specifications

| Derivative | Density | Long edge | Quality (algorithm) | Optimisation |
|---|---|---|---|---|
| `base` | `@1x` | 1000px | 80% | [ImageOptim](https://imageoptim.com/), best algorithm at `Extra` optimisation level |
| `base` | `@2x` | 2000px | 80% | [ImageOptim](https://imageoptim.com/), best algorithm at `Extra` optimisation level |
| `thumbnail` | `@1x` | 100px | 90% | ImageOptim, best algorithm at `Extra` optimisation level |
| `thumbnail` | `@2x` | 200px | 90% | ImageOptim, best algorithm at `Extra` optimisation level |
