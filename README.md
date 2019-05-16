# Textpattern CMS demo site resources

Work in progress.

## Images

Source images are licensed for commercial and non-commercial use at the time of committing, and sourced from:

* [Pixabay](https://pixabay.com) ([license](https://pixabay.com/service/terms/#license))
* [Pexels](https://www.pexels.com) ([license](https://www.pexels.com/photo-license/))

Note: attribution will follow, see [issue 3](https://github.com/petecooper/textpattern-demo-resources/issues/3).

Original sources images, untouched: [/source/images/](https://github.com/pragmatika/textpattern-demo-resources/tree/master/source/images).

Ready-to-use images: [/dist/images/](https://github.com/pragmatika/textpattern-demo-resources/tree/master/dist/images).

Thumbnails: [/dist/images/_thumbnails/](https://github.com/pragmatika/textpattern-demo-resources/tree/master/dist/images/_thumbnails).

### Image types

Ready-to use images are derived from the highest resolution or original source file provided by the creator via the website(s) listed. Image filenames have the following namespace:

* Photographs (JPG, lossy): `1###[-derivative]@dimensionMultiplier.jpg` (e.g. `1012@1x.jpg`)
* Photographs (WebP, lossy): `2###[-derivative]@dimensionMultiplier.jpg` (e.g. `1012-thumbnail@1x.webp`)
* Illustrations with transparency (PNG, lossless): `4###[-derivative]@dimensionMultiplier.png` (e.g. `4012-thumbnail@2x.png`)
* Illustrations without transparency (WebP, lossless): `5###[-derivative]@dimensionMultiplier.webp` (e.g. `5012@2x.webp`)
* Vectors with transparency (SVG, lossless): `8###.svg` (e.g. `8012.svg`)
* Vectors without transparency (SVG, lossless): `9###.svg` (e.g. `9012.svg`)

| File type | Lossy | Lossless |
|---|---|---|
| JPG | X | - |
| PNG | - | X |
| SVG | - | X |
| WebP | X | X |

### Toolkit

* [ImageOptim](https://imageoptim.com/)

### Raster image specifications

| Derivative | Density | Long edge | Quality | Optimisation |
|---|---|---|---|---|
| base image | `@1x` | 1000px | 80% | ImageOptim, best algorithm at `Extra` optimisation level |
| base image | `@2x` | 2000px | 80% | ImageOptim, best algorithm at `Extra` optimisation level |
| `thumbnail` | `@1x` | 250px | 80% | ImageOptim, best algorithm at `Extra` optimisation level |
| `thumbnail` | `@2x` | 500px | 80% | ImageOptim, best algorithm at `Extra` optimisation level |
