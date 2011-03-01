- Added rcarlsen-Pocket-OCR-6f49b9f.zip. This is zipped content of fully working PocketOCR XCode project by rcarlsen bundled with: 
-- full tesseract3 with libs compiled from scratch from sources (sources included) with properly updated building script for tess3/iphone 4.2
-- full opencv 2.1 also with libs compiled from scratch from sources (sources included) with working build script for opencv 2.1/iphone 4.2
-- some opencv filters applied to image before OCRing it image for demo purposes

Project works out of the box (both for iphone and simulator), nothing stripped, that is why it is so big :) 
==========================
Pocket OCR
Tesseract OCR for iPhone

Robert Carlsen | robertcarlsen.net

This project is a demonstration of implementing the Tesseract OCR engine on the iPhone platform. It works best with the iPhone 3GS and it's autofocus lens. External lenses for older iPhones may be necessary for optimal image capture.

To build the tesseract library, download the source code and compile apropriately for the iPhone (arm processor). Add the library to the XCode project and build.

The Tesseract source code is available at:
http://code.google.com/p/tesseract-ocr/

A build script and instructions are available at:
http://robertcarlsen.net/2009/07/15/cross-compiling-for-iphone-dev-884

Issue tracker now available at http://bugs.robertcarlsen.net/projects/pocket-ocr-200.

Enjoy!
-Robert

---
Released 11.1.2010
