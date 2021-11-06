  
  boxcutter
  Copyright Matt Rasmussen 2008-2011
  
  The original version made cropped screenshots due to DPI issues... I fixed that using Window's EnumDisplaySettings API.
  Now it auto-detects the correct resolution no matter what DPI is set. It will take a screenshot with no issues.

boxcutter is a minimal Windows command line screenshot
application. It requires and accepts a single argument: the file name
to store the screenshot. Nothing is echoed to the console. If the
program exits on 0, it was successful. If not, the program
failed. Screenshots are stored as uncompressed bitmaps.  This program is
useful for very quick fullscreen screenshots.

usage: boxcutter OUTPUT_FILENAME
example: "boxcutter test.jpg"

Saves a bitmap screenshot to 'OUTPUT_FILENAME'.
