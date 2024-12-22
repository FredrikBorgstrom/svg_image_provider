<!--
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/tools/pub/writing-package-pages).

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/to/develop-packages).
-->

A simple Dart package that provides an `ImageProvider` for Flutter that can load SVG images.

## Features

- Load SVG images from assets
- Scale SVG images to fit a given container size

## Getting started

Add the package to your `pubspec.yaml` file:

```yaml
dependencies:
  svg_image_provider: ^0.1.0
```

## Usage

```dart
SvgImageProvider(
            'assets/images/placeholder.svg',
            scale: 1.0,
            containerSize: Size(100, 100),
)
```

## Additional information

My name is Fredrik Borgström, and if you have any suggestions or want to report a bug, you can reach
me through my web site at [abcx3.com](https://abcx3.com), or you can submit an issue on the 
[GitHub repository](https://github.com/FredrikBorgstrom/svg_image_provider).
The package is open source and contributions are welcome.
