# imagemagick-q8

## Supported tags:
* `latest` [_(Dockerfile)_](https://github.com/AllYourBase/docker-imagemagick-q8/blob/master/Dockerfile)

## Description
ImageMagick built [from source](http://www.imagemagick.org/script/install-source.php#unix) with quantum depth 8 for faster processing, and is suitable for workflows with minimal adjustments to the appearance of an image. This build based on my [`magickdeps` image](https://hub.docker.com/r/allyourbase/magickdeps/), which in turn is based on a [`debian:jessie-slim` image](https://registry.hub.docker.com/u/library/debian/). Includes Ghostscript delegate for PostScript and PDF processing. Includes PerlMagick module installed onto Debian system Perl.

## Usage
````
$ docker run -it -P allyourbase/imagemagick-q8 (convert|identify|mogrify) [options] arg1 arg2 ...
````
