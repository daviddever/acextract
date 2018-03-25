# acextract
A set of short shell scripts for extracting text from DOS binary using screenshots and ocr.

`xte` and `gnome-screenshot` are used to scroll through programs text and screenshot each page. Then ImageMagick  `convert` creates new tiff formatted images in grayscale and blown up 500% after which the tiff's are run through `tesseract` and then compiled into a single text file.

These scripts have hardcoded variables for the speciffic program and things like using alt tab to select the correct window but could be adjusted.
