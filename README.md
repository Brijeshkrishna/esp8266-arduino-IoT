# ESP 8266 and arduino IoT

IoT devices are the nonstandard computing devices that connect wirelessly to a network and have the ability to transmit data, such as the many devices on the internet of things (IoT).


IoT involves extending internet connectivity beyond standard devices, such as desktops, laptops, smartphones and tablets, to any range of traditionally "dumb" or non-internet-enabled physical devices and everyday objects. Embedded with technology, these devices can communicate and interact over the internet. They can also be remotely monitored and controlled.


	In this project with use of iot technology ,we control the motion of led ,it need not to an led we can control any device.ESP 8266 has a built in wifi , with that we communicate with the internet,In this  project we used telegram for communicating with esp8266.esp8266 is connected to the arduino with serial communication to send data from esp8266,indirectly from telegram to arduino esp8266 as an intermediate.
We see commands from telegram to arduino to turn on or off or blink a specific led ,for example if we send /led_1_on it will turn on the  led 1  to turn off /led_1_off . With the help of this we can blink a led by /led_1_blink . There is no restriction of number led except the pin in arduino,we demonstrated how we individually control the leds.
