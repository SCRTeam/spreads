Changelog
=========
0.3.3 (2013/08/28)
------------------
* Fix typo in device manager that prevent drivers from being loaded

0.3.2 (2013/08/24)
------------------
* Fixes a critical bug in the devices drivers

0.3.1 (2013/08/23)
------------------
* Fixes a bug that prevented spreads to be installed

0.3 (2013/08/23)
----------------
* Plugins can add completely new subcommands.
* GUI plugin that provides a graphical workflow wizard.
* Tesseract plugin that can perform OCR on captured images.
* pdfbeads plugin can include recognized text in a hidden layer if OCR has
  been performed beforehand.
* Use EXIF tags to persist orientation information instead of JPEG comments.
* Better logging with colorized output
* Simplified multithreading/multiprocessing code
* CHDK driver is a lot more stable now

0.2 (2013/06/30)
----------------
* New plugin system based on Doug Hellmann's `stevedore` package,
  allows packages to extend spreads without being included in the core
  distribution
* The driver for CHDK cameras no longer relies on gphoto2 and ptpcam,
  but relies on Abel Deuring's `pyptpchdk` package to communicate with
  the cameras.
* `Wand` is now used to deal with image data instead of `Pillow`
* New 'colorcorrection' plugin allows users to automatically correct
  white balance.
* Improved tutorial

0.1 (2013/06/23)
----------------
* Initial release
