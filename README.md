# Textpattern CMS demo site resources

Work in progress.

## Images

Images are licensed for commercial and non-commercial use at the time of committing, and sourced from:

* [Pixabay](https://pixabay.com) ([licence](https://pixabay.com/service/terms/#license))
* [Pexels](https://www.pexels.com) ([licence](https://www.pexels.com/photo-license/))

Downloaded originals: [/source/images/](https://github.com/pragmatika/textpattern-demo-resources/tree/master/source/images).

Ready-to-use images: [/dist/images/](https://github.com/pragmatika/textpattern-demo-resources/tree/master/dist/images).

Thumbnails: [/dist/images/_thumbnails](https://github.com/pragmatika/textpattern-demo-resources/tree/master/dist/images/_thumbnails).

### Image sizes

Ready-to use images are derived from the highest resolution or original source file. Processed image filenames have the following namespace:

* Photographs: `1###@dimensionMultiplier.jpg` (e.g. `1012@1x.jpg`)
* Illustrations with transparency: `4###@dimensionMultiplier.png` (e.g. `4012@2x.png`)
* Illustrations without transparency: `5###@dimensionMultiplier.webp` (e.g. `5012@2x.webp`)
* Vectors with transparency: `8###.svg` (e.g. `8012.svg`)
* Vectors without transparency: `9###.svg` (e.g. `9012.svg`)

JPG and WebP files use lossy compression, PNG and SVG files are considered lossless. PNG optimisation in [ImageOptim](https://imageoptim.com/) should only include lossless algorithms.

### Raster image specifications

| Derivative | Density | Long edge (algorithm) | Quality (algorithm) | Optimisation |
|---|---|---|---|---|
| `base` | `@1x` | 1000px (Lancsoz) | 80% | [ImageOptim](https://imageoptim.com/), best algorithm at `Extra` optimisation level |
| `base` | `@2x` | 2000px (Lancsoz) | 80% | [ImageOptim](https://imageoptim.com/), best algorithm at `Extra` optimisation level |
| `thumbnail` | `@1x` | 100px (Lancsoz) | 90% | ImageOptim, best algorithm at `Extra` optimisation level |
| `thumbnail` | `@2x` | 200px (Lancsoz) | 90% | ImageOptim, best algorithm at `Extra` optimisation level |
