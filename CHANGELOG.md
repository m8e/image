## 2.0.3 - June 6, 2018

- copyResize can maintain aspect ratio when resizing height by using -1 for the width.
- Added example for loading and processing images in an isolate.

## 2.0.2 - June 1, 2018

- Re-added decoding of orientation exif value from jpeg images.
- Added bake_orientation function, which will rotate an image so that it physically matches its orientation exif value,
useful for rotating an image prior to exporting it to a format that doesn't support exif data.

## 2.0.1 - May 28, 2018

Fix for bad jpeg files when encoding EXIF data.

## 2.0.0 - May 22, 2018

Remove the use of Dart 1 upper-case constants.
Update SDK dependency to a 2.0 development release.

## 1.1.33 - May 16, 2018

  Maintain EXIF data from JPEG images.

## 1.1.32 - May 9, 2018

  Remove the use of `part` and `part of` in the main library.

## 1.1.30 - March 10, 2018

  Update pubspec to account for the new version of xml package that has been
  published.

## 1.1.29 - September 18, 2017

- Add fixes for strong mode support.

## 1.1.28 - May 27, 2017

- Update pubspec to fix recent pub issues.
- Rename changelog.txt to CHANGELOG.md.
- Fix for 8-bit PNG decoding.

## 1.1.27 - May 14, 2017

- Fix crash decoding some jpeg images.


## 1.1.24 - January 23, 2015

- PVR encoding/decoding
- Fix 16-bit tiff decoding


## 1.1.23 - September 15, 2014

- Fix alpha for PSD images.


## 1.1.22 - July 31, 2014

- Various bug fixes


## 1.1.21 - June 19, 2014

- Add drawImage function
- Update XML dependency to 2.0.0


## 1.1.20 - April 26, 2014

- Fix OpenEXR decoder for dart2js


## 1.1.19 - April 15, 2014

- OpenEXR fixes.


## 1.1.18 - April 06, 2014

- Added OpenEXR format docoder.


## 1.1.17 - April 02, 2014

- Add Photoshop PSD format decoder


## 1.1.16 - March 24, 2014

- Fix JPEG encoder for compression quality < 100.


## 1.1.15 - March 10, 2014

- Update to new version of archive.


## 1.1.14 - February 26, 2014

- Optimizations


## 1.1.13 - February 16, 2014

- Added TIFF decoder


## 1.1.10 - February 11, 2014

- Added APNG animated PNG decoding support.
- Improved JPEG decoding performance
- Various bug fixes


## 1.1.8 - February 01, 2014

- Added GIF decoding support, including animated gifs.


## 1.1.7 - January 28, 2014

- Added WebP decoding support, included animated WebP.

