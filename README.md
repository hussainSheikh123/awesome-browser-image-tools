# Awesome Browser-Based Image Tools

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of image processing tools that run entirely in the browser — no upload to servers, no installation needed.

All tools listed here process images client-side using Canvas API, WebAssembly, or Web Workers. Your images never leave your device.

## Contents

- [Image Compression](#image-compression)
- [Format Conversion](#format-conversion)
- [Image Editing](#image-editing)
- [AI-Powered Tools](#ai-powered-tools)
- [Privacy & Metadata](#privacy--metadata)
- [Batch Processing](#batch-processing)

## Image Compression

| Tool | Description | Open Source |
|------|-------------|------------|
| [SammaPix Compress](https://www.sammapix.com/tools/compress) | Batch JPEG/PNG/WebP compression with quality slider. Up to 20 images at once. | [MIT](https://github.com/samma1997/sammapix) |
| [Squoosh](https://squoosh.app/) | Google's image compression app. Single image, multiple codec options. | [Apache 2.0](https://github.com/GoogleChromeLabs/squoosh) |
| [Compressor.io](https://compressor.io/) | Lossy and lossless compression. Single image at a time. | No |
| [Browser Image Compression](https://github.com/nicholasjperry/browser-image-compression) | JavaScript library for client-side compression. | [MIT](https://github.com/nicholasjperry/browser-image-compression) |
| [Piczilo](https://piczilo.com/) | Free browser-based image compression with target file-size tools, resizing, and format conversion. | No |

## Format Conversion

| Tool | Formats | Open Source |
|------|---------|------------|
| [SammaPix WebP](https://www.sammapix.com/tools/webp) | Any → WebP. Batch conversion with ZIP download. | [MIT](https://github.com/samma1997/sammapix) |
| [SammaPix HEIC](https://www.sammapix.com/tools/heic) | HEIC → JPG/PNG/WebP. iPhone photo conversion. | [MIT](https://github.com/samma1997/sammapix) |
| [CloudConvert](https://cloudconvert.com/) | 200+ format combinations. Some processing server-side. | No |
| [Convertio](https://convertio.co/) | Wide format support. Server-side processing. | No |

## AI-Powered Tools

| Tool | Function | Open Source |
|------|----------|------------|
| [SammaPix AI Rename](https://www.sammapix.com/tools/ai-rename) | AI generates SEO-friendly filenames from image content. | [MIT](https://github.com/samma1997/sammapix) |
| [SammaPix Remove BG](https://www.sammapix.com/tools/remove-bg) | AI background removal, runs in browser via ONNX. | [MIT](https://github.com/samma1997/sammapix) |
| [Remove.bg](https://www.remove.bg/) | Background removal. Server-side, freemium model. | No |
| [Cleanup.pictures](https://cleanup.pictures/) | Object removal from images. Partially client-side. | No |

## Privacy & Metadata

| Tool | Function | Open Source |
|------|----------|------------|
| [SammaPix EXIF](https://www.sammapix.com/tools/exif) | View and strip EXIF/GPS metadata. Batch processing. | [MIT](https://github.com/samma1997/sammapix) |
| [ExifCleaner](https://exifcleaner.com/) | Desktop app for EXIF removal. Electron-based. | [MIT](https://github.com/szTheory/exifcleaner) |
| [Scrambled Exif](https://gitlab.com/juanitobananas/scrambled-exif) | Android app for EXIF removal before sharing. | [GPL](https://gitlab.com/juanitobananas/scrambled-exif) |

## Batch Processing

| Tool | Function | Open Source |
|------|----------|------------|
| [SammaPix](https://www.sammapix.com/) | Full toolkit: 27 tools, batch up to 20 images, ZIP download. | [MIT](https://github.com/samma1997/sammapix) |
| [Birme](https://www.birme.net/) | Batch resize and crop. Browser-based. | No |
| [iLoveIMG](https://www.iloveimg.com/) | Batch tools. Mix of client and server processing. | No |

## Why Browser-Based?

- **Privacy**: Images never leave your device
- **Speed**: No upload/download time, instant processing
- **Offline**: Works without internet after first load
- **Free**: No server costs = free tools
- **Security**: No data breach risk from server storage

## Contributing

Found a browser-based image tool that's missing? Open a PR! Requirements:
- Tool must process images client-side (Canvas API, WebAssembly, or Web Workers)
- Tool must be free to use (at least basic features)
- Include: name, URL, description, and whether it's open source

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
