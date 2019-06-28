## Adafruit TPL5111 Reset Enable Timer PCB

<a href="http://www.adafruit.com/products/3573"><img src="assets/image.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit TPL111 Reset Enable Timer. For more details, Pick up one today & check out the product page at
* https://www.adafruit.com/products/3573

### Description

With some development boards, low power usage is an afterthought. Especially when price and usability are the main selling points. So what should you do when it's time to turn around and make that project of yours run on a battery or solar? Sure you could try to hot-air that regulator off, or you could jerry-rig a relay. Or, use a 555? Ugh, the options aren't that great.

The Adafruit TPL5111 Low Power Reset Timer is a stand-alone breakout that will turn any electronics into low-power electronics! It will take care of enabling & disabling your electronics using a built in timer that can vary from once-every 100ms up to once every two hours. Basically, the TPL will set an enable pin high periodically, adjustable by potentiometer or resistor, and turn on your project's power. It will then wait until a signal is received from the project to tell the TPL that it can safely disable the project by setting the enable pin low. If the TPL does not receive a signal by the set time-out, it will reset the device like a watchdog timer.

We also have a TPL5110 breakout, which rather than setting an enable pin high/low, connects and disconnects power. The TPL5111 breakout is best when you have an enable pin you can control, the TPL5110 is best when you are able to 'break' the power input line to place the TPL5110 between the power supply and Vin.

Usage is easy. First, set your desired delay but adjusting the on-board trim pot: all the way to the left is once-per-100ms and all the way to the right is once-every-2-hours. Then, connect VDD up to your 3-5V project power supply, and then your project's enable pin to the Enable pin. Finally, select a signal pin from your project to the Done pin. In your project's code or design, just make sure that it sets the Done pin high once it is completed with its task. That's it!

While the TPL5111 is running (but the remainder of the project is de-powered) the current draw is about 20uA (according to our Monsoon Power Meter).

If you want to turn the device on by hand, you can also activate the TPL by pressing the onboard tactile switch (or wire your own switch to the Delay pin) See? Your power problems just got solved!

Comes as a fully assembled breakout board with a TPL5111 chip, all components on-board, and some header. A little light soldering is required to put it together for breadboard use.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. See license.txt for additional details.
