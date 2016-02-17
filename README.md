iOS build scripts for the [Opus Codec](http://www.opus-codec.org).

### Usage

1. `$ bash build-libopus.sh`
2. Drag `dependencies/` into your Xcode project or you just can copy repo dependencies.
3. Enjoy and have fun!

### Buid settings in respo dependencies:

* VERSION="1.1.2" <- opus [lib](http://downloads.xiph.org/releases/opus) version **release date(2016-01-12)**
* SDKVERSION="9.2" <- iOS SDK
* MINIOSVERSION="8.0" <- Min iOS SDK


#Usage:
>just runs the following commands in the shell:
> for framework:
```bash
./build-opus-framework.sh 
```
> for executable files:
```bash
./build-libopus.sh
```
