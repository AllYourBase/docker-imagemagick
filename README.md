# docker-imagemagick-q8

## Supported tags:
* `latest` [_(Dockerfile)_](https://github.com/AllYourBase/docker-imagemagick/blob/master/6.8.9-10_q8/Dockerfile)

## Description
ImageMagick built [from source](http://www.imagemagick.org/script/install-source.php#unix) with quantum depth 8 for faster processing. This build based on an intermediate "magickdeps" image, which in turn is based on a [`debian:jessie` Docker image](https://registry.hub.docker.com/u/library/debian/). Includes Ghostscript delegate for PostScript and PDF processing. Includes PerlMagick module installed onto Debian system Perl.


## Usage
````
$ docker run -it -P allyourbase/imagemagick-q8 (convert|identify|mogrify) [options] arg1 arg2 ...
````
