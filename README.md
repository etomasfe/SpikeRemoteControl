# SpikeRemoteControl
Control your Spike Lego from HTML+JS 

This code is my first attempt to control a Lego Spike Robot using only HTML and JavaScript
Although the code is quite large and a bit confused, my intention is to share to everyone that only need to load the page and just play the program. That's why I put all togheter in a one file.

To sum up when BT connected:
-clear slot0 program on spike
-send file program & transfer by pieces (chunk)
-send start slot0 command
-just click on buttons

There are several functions to make data transfer correct.
That was the difficult part, where I spend a lot of time to test by trial and error.

I send some string values when a button is clicked (name of the button, power,...)
The python code downloaded on the hub just get this data and perform it.

In the future, a better version will be done... if I have time and patience.
