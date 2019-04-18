# PCB for the Adafruit Flora Smart NeoPixels

<a href="http://www.adafruit.com/products/1060"><img src="assets/image.jpg?raw=true" width="500px"><br/>Click here to purchase one from the Adafruit shop</a>

__Format is EagleCAD schematic and board layout__

What's a wearable project without LEDs? Our favorite part of the Flora platform is these tiny smart pixels. Designed specifically for wearables, [we found the brightest RGB LEDs available (an eye-blistering ~3800mcd)](http://adafruit.com/products/619) and paired them with a constant-current driver chip that sits on the back. The pixels are chainable - so you only need 1 pin/wire to control as many LEDs as you like. They're easy to sew, and the chainable design means no crossed threads.

__This is the first/original version of the Flora NeoPixels, which runs at at 'low speed' 400KHz communication.__ Unfortunately they are not forward-compatible with [the fully-integrated 'high speed' (800KHz) Flora NeoPixel V2's](http://www.adafruit.com/products/1260). If you have a project that already uses high speed pixels, and you want to attach more pixels to the chain, [you will need to purchase version 2's](http://www.adafruit.com/products/1260) as these are not cross-compatible. __If you don't have any pixels in your project yet, [we suggest purchasing v2 pixels](http://www.adafruit.com/products/1260) as they are lower cost and v1's will eventually be discontinued.__

These pixels have full 24-bit color ability with PWM taken care of by the controller chip. Since the LED is so bright, you need less current/power to get the effects you want. The driver is constant current so its OK if your battery power changes or fluctuates a little.

Each pixel draws as much as 60mA (all three RGB LEDs on for full brightness white). In theory, the Flora can drive up to 500 pixels at 30 FPS (it will run out of RAM after that). However, after about 10 pixels (or if the distance between pixels is more than an inch or two) the resistance of the thread can affect the power supply. For large quantities of pixels over 10, you may want to consider using stranded core wire or copper braid to provide a "power bus" for the pixels - the current draw will add up fast!

Each order comes with 4 individually controllable pixels.

## License
Adafruit invests time and resources providing this open source design,
please support Adafruit and open-source hardware by purchasing
products from Adafruit!

Designed by Adafruit Industries.
Creative Commons Attribution, Share-Alike license, check license.txt for more information
All text above must be included in any redistribution
