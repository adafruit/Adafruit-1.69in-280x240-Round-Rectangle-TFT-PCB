## Adafruit 1.69in 280x240 Round Rectangle TFT Display - ST7789 PCB

<a href="http://www.adafruit.com/products/5206"><img src="assets/5206.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit 1.69in 280x240 Round Rectangle TFT Display - ST7789. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5206

### Description

Don't be such a square - throw a curve-ball into your electronics with a curved-edge miniature display. Here's a new "round rect" TFT display - it's 1.69" diagonal and has a high-density 220 ppi, 280x240 full color pixels with IPS any-angle viewing. We've seen displays of this caliber used in smartwatches and small electronic devices but they've always been MIPI interface. Finally, we found one that is SPI and has a friendly display driver, so it works with any and all microcontrollers or microcomputers!

This lovely little display breakout is the best way to add a small, colorful, and very bright display to any project. Since the display uses 4-wire SPI to communicate and has its own pixel-addressable frame buffer, it can be used with every kind of microcontroller. Even a very small one with low memory and few pins available! The 1.69" display has 280x240 16-bit full color pixels and is an IPS display, so the color looks great up to 80 degrees off-axis in any direction. The TFT driver (ST7789) is very similar to the popular ST7735, and our Arduino library supports it well.

Note that the way we get the rounded corners is by deleting pixels. The corner pixels are still addressed in RAM, they just don't appear, so it isn't like you have to do some special radial-pixel mapping. Treat it like a rectangular display.

Our breakout has the TFT display soldered on (it uses a delicate flex-circuit connector) as well as an ultra-low-dropout 3.3V regulator and a 3/5V level shifter so you can use it with 3.3V or 5V power and logic. We also had a little space so we placed a microSD card holder so you can easily load full-color bitmaps from a FAT16/FAT32 formatted microSD card. The microSD card is not included, but you can pick one up here.

Of course, we wouldn't just leave you with a datasheet and a "good luck!" - we've written a full open-source graphics library that can draw pixels, lines, rectangles, circles, text, and bitmaps as well as example code and a wiring tutorial. The code is written for Arduino but can be easily ported to your favorite microcontroller!

This display breakout also features a 18-pin "EYE SPI" standard FPC connector with flip-top connector. You can use a 18-pin 0.5mm pitch FPC cable to connect to all the GPIO pins, for when you want to skip the soldering.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
