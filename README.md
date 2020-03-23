heroku-buildpack-exiftool
=========================

A Heroku buildpack that installs the latest production version of Phil Harvey's [ExifTool](http://www.sno.phy.queensu.ca/~phil/exiftool/).

version: https://sno.phy.queensu.ca/~phil/exiftool/Image-ExifTool-11.92.tar.gz

Usage
-----

Simply add this Git repo to your `.buildpacks` file and set your Heroku config var `BUILDPACK_URL` to `https://github.com/jeremedia/heroku-buildpack-exiftool#build-env`.
