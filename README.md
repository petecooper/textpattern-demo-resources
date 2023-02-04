# Textpattern CMS demo site resources

Work in progress. Weekend project.

## Images

Source images are licensed for commercial and non-commercial use at the time of committing, and sourced from (alphabetical order):

* [Burst](https://burst.shopify.com) ([licence](https://burst.shopify.com/legal/terms))
* [Pexels](https://www.pexels.com) ([license](https://www.pexels.com/photo-license/))
* [Pixabay](https://pixabay.com) ([license](https://pixabay.com/service/terms/#license))
* [Unsplash](https://unsplash.com) ([license](https://unsplash.com/license))

### Image types

| File type | Category | Compression | Transparency | ID range | Count / (target) |
|---|---|---|---|---|---|
| JPG | Photos | Lossy | No | `1000` - `1499` | - / (150) |
| WebP <sup>([?](https://caniuse.com/webp))</sup> | Photos | Lossy | No | `1500` - `1999` | - / (150) |
| AVIF<sup>([?](https://caniuse.com/avif))</sup> | Photos | Lossy | No | `2000` - `2499` | - / (150) |
| - | Photos | Lossy | No | `2500` - `2999` | - / (150) |
| GIF | Illustrations | – | Yes | `3000` - `3499` | - / (150) |
| PNG | Illustrations | Lossless | Yes | `3500` - `3999` | - / (150) |
| WebP <sup>([?](https://caniuse.com/webp))</sup> | Illustrations | Lossless | No | `4000` - `4499` | - / (150) |
| PNG | Screenshots | - | No | `4500` - `4999` | - / (150) |
| GIF | Animation | - | - | `5000` - `5499` | - / (150) |
| APNG <sup>([?](https://caniuse.com/apng))</sup> | Animation | - | - | `6000` - `6499` | - / (100) |
| AVIF | Animation | - | - | `7000` - `7499` | - / (100) |
| SVG <sup>([?](https://caniuse.com/svg))</sup> | Vectors | None | Yes | `9000` - `9499` | - / (100) |
| SVG <sup>([?](https://caniuse.com/svg))</sup> | Vectors | None | No | `9500` - `9999` | - / (100) |

### Raster image specifications

| Size | Derivative | Dimensions multiplier | Long edge | Quality |
|---|---|---|---|---|
| M | base | `@1x` | 500px | 80% |
| M | base | `@2x` | 1000px | 80% |
| M | base | `@3x` | 1500px | 80% |
| M | thumbnail | `@1x` | 100px | 80% |
| M | thumbnail | `@2x` | 200px | 80% |
| M | thumbnail | `@3x` | 300px | 80% |
| L | base | `@1x` | 1000px | 80% |
| L | base | `@2x` | 2000px | 80% |
| L | base | `@3x` | 3000px | 80% |
| L | thumbnail | `@1x` | 200px | 80% |
| L | thumbnail | `@2x` | 400px | 80% |
| L | thumbnail | `@3x` | 600px | 80% |

### Toolkit

* [ImageOptim](https://imageoptim.com/)
* [Retrobatch Pro](https://flyingmeat.com/retrobatch/)
* [XnConvert](https://www.xnview.com/en/xnconvert/)
