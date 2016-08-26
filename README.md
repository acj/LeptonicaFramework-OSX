This is a macOS framework "wrapper" for the Leptonica library.

## Getting Started

1. Clone this repository.
 * Drag `LeptonicaFramework.xcodeproj` to your project.
 * In your project settings under Build Phases, add `LeptonicaFramework.framework` under "Target Dependencies" and "Link Binary with Libraries".
 * Add `#import <Leptonica/Leptonica.h>` to your source file.
 * Build and enjoy.

If you improve this project, please send me a pull request.

## Notes

To simplify Leptonica's dependency on various graphics libraries (libtiff, libpng, freetype, etc) and make this framework self-contained, I include the [UnixImageIO and FreeType](http://www.kyngchaos.com/software:frameworks) frameworks from KyngChaos.

## Credit

The fabulous Leptonica image analysis library is available at [leptonica.com](https://www.leptonica.com).

The list of source files in this project is adapted from https://github.com/mcku/leptonica-osx .