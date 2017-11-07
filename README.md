# esp-neopixel-notifier
Notification light using an ESP (nodemcu) and a ws2812 neopixel.


Simple device, attach the ws2812 to the nodemcu and upload the code. The nodemcu will take a color command in RBGW sent via mqtt to the device. The light will change colors depending on the code sent. You could use any ESP to do this I went with the nodemcy for power supply simplicity.

Example 255000000000 sent over the incomming mqtt topic turns the led red.

see https://www.itsalllost.com/neopixel-notifier/ for more.
