# M5Stack Core 2 Audio - Arduino IDE Version!
This Fork of the excellent Audio Visualiser by Atomic14/Chris G ( https://hackaday.io/project/178220-m5core-stack2-audio-visualiser ) is a "Download and Upload" single click version of the code for the Arduino. The original compiles via PlatformIO which I don't use, so I went about editing it.

There's no extra configuring to be done - just download the folder, open the AudioMonitor.ino file, and hit "Upload".

I've done no coding - this is merely a reconfiguring of the code files to compile under the Arduino IDE. (Though getting the paths for the subfolders right for Arduino is a complete PITA.)

My Core 2 has the "Bottom 2" board (***1**), that integrates NeoPixels along with a mic and gyroscope. (***2**)
https://shop.m5stack.com/products/m5go-battery-bottom2-for-core2-only
I can confirm the mic in this unit works well with the software. =)

  -- SarahC

* 1 The updated board ensures the correct Core 2 IO pins are used in the port plugs, the "Bottom" clashed with the PSRAM connections - there's some forum posts about losing port use on the Core 2 when people plugged their "Bottoms" in. -grins-

* 2 Odd that the base didn't have a slot for the existing mic/gyroscope!? I guess it was designed on a Friday afternoon.
----------------------

You can watch a video explainer [here (YouTube)](https://www.youtube.com/watch?v=CwIWpBqa-nM) which goes into a bit more detail on the audio capabilities of the device.

[![Demo Video](https://img.youtube.com/vi/CwIWpBqa-nM/0.jpg)](https://www.youtube.com/watch?v=CwIWpBqa-nM)

This project is a nice little demo of audio on the M5Stack Core 2 with some simple visualisations.

~~You'll need to use PlatformIO to build the project.~~

Hopefully, the code should be easy to understand.

If you want to add some more visualisations then please open up a pull request and contribute some code, here: https://github.com/atomic14/m5stack-core2-audio-monitor

And if you'd like to buy me a coffee...

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Z8Z734F5Y)
