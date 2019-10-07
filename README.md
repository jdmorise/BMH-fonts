# Big Monochrome Bitmap Header Fonts
This repository contains a library of fonts in bitmap header format for use in AVR or other microcontrollers together with monochrome OLED or LCD Displays, like the SSD1306. 

Different header files are available for character size of 24, 32, 40, 48, 56, 64 pixels. 
The include files are stored in the bmh_fonts folder, the original ttf font files are found in the ttf_fonts folder. The license of each font is stored with each TTF file. 

The library contains two folders: 
* bmh_digits: contains digits 0-9 and colon (:) - Useful for creation of displays for clocks
* bmh_char: All printable ASCII characters, from !(ascii 0d33) to ~ (ascii 0d126)

## Fonts
Please check the folder structure for a full list of available fonts. 

## Used Software
The header files were produced with the python scripts in my git repository "TTF2BMH" and use of bmfont. 

https://github.com/jdmorise/TTF2BMH    
https://www.angelcode.com/products/bmfont/

## Additional Fonts
Upload of any free (in terms of license) font can be requested, just write a short note here and I will upload as fast as possible.

## Errata
Some fonts have the underscores too low to be printed. It needs to be checked in the font header file is content is present. If required, the font rendering with y-offset and character size needs to be changed. 

## 