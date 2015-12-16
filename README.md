
> Opus is a totally open, royalty-free, highly versatile audio codec. Opus is unmatched for interactive speech and music transmission over the Internet, but is also intended for storage and streaming applications. It is standardized by the Internet Engineering Task Force (IETF) as RFC 6716 which incorporated technology from Skype's SILK codec and Xiph.Org's CELT codec.

iOS build scripts for the [Opus Codec](http://www.opus-codec.org). I am also working on an Objective-C wrapper called [OpusKit](https://github.com/chrisballinger/opuskit).

### Usage

1. `$ bash build-libopus.sh`
2. Drag `dependencies/` into your Xcode project.
3. Enjoy and have fun!

or you just can copy my dependencies

### buid settings in my dependencies:
VERSION="1.1.1" <- opus lib http://downloads.xiph.org/releases/opus version
SDKVERSION="9.2" <- iOS SDK
MINIOSVERSION="8.0" <- Min iOS SDK
