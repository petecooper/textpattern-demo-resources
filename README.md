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

Ready-to use images are derived from the highest resolution or original source file.

| File type | Category | Compression | Transparency | Prefix ID range | Count |
|---|---|---|---|---|---|
| JPG | Photos | Lossy | No | `1000` - `1999` | 50 |
| WebP | Photos | Lossy | No | `2000` - `2999` | - |
| GIF | Illustrations | - | - | `3000` - `3999` | - |
| PNG | Illustrations | Lossless | Yes | `4000` - `4999` | 20 |
| WebP | Illustrations | Lossless | No | `5000` - `5999` | - |
| APNG | Animation | - | - | `6000` - `6999` | - |
| GIF | Animation | - | - | `7000` - `6999` | - |
| SVG | Vectors | None | Yes | `8000` - `8999` | - |
| SVG | Vectors | None | No | `9000` - `9999` | - |

### Raster image specifications

| Derivative | Dimensions multiplier | Long edge | Quality | Optimisation |
|---|---|---|---|---|
| base image | `@1x` | 1000px | 80% | ImageOptim, best algorithm at `Extra` optimisation level |
| base image | `@2x` | 2000px | 80% | ImageOptim, best algorithm at `Extra` optimisation level |
| `thumbnail` | `@1x` | 250px | 80% | ImageOptim, best algorithm at `Extra` optimisation level |
| `thumbnail` | `@2x` | 500px | 80% | ImageOptim, best algorithm at `Extra` optimisation level |

### Toolkit

* [ImageOptim](https://imageoptim.com/)
* [XnConvert](https://www.xnview.com/en/xnconvert/)
