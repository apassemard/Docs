Raspberry Pi hardware setup
===========================

Intro
-----
Raspberry Pi models are quite cheap, as they are a bare bones board. Sometimes you can purchase all the required hardware accessories as a package. The hardware is often so common that it is already laying around your house. Either way, here are the necessary and optional things you will need to purchase (or scrounge) in order to start up your Raspberry Pi and to get the most out of RuneAudio.

Required Items
--------------

###Raspberry Pi, any model

![enter image description here](https://lh3.googleusercontent.com/U9xiQpORbTgsUcensoeV9B5QtTt-8cxpUJ1d7jeO4Q=s400 "Raspberry_Pi_-_Model_A.jpg")

###Power Supply

Raspberry Pi models function on 5V DC power. They require a minimum of 2A available current to avoid brownouts on the board. 'Wall warts' are the simple start. Make sure your power supply is appropriate for the grid power in your country, and that the other end terminates in a micro-USB plug. 

![enter image description here](https://lh5.googleusercontent.com/QM8JJUk9-fI1BVrAX-LsOAreSKcXRRECpZdPQtihOQ=s400 "wall wart.jpg")

Many tunable AC-DC switching power supplies on the market allow tuning to obtain a narrow (or sometimes wide) voltage output.

> [WARNING] <i class="fa fa-exclamation sx"></i> Make certain your power supply is tuned as close to 5V DC as possible

The Raspberry Pi board requires a fairly high tolerance voltage output. It is susceptible to both brownouts (below 4.7V DC) and frying your circuit paths (above 5.2V DC). Make certaiin your power supply is tuned as close to 5V DC as possible, to allow for voltage swing in either direction. Brownouts will also occur if the power supply is underrated, or the power draw is too high.

###4GB or larger SD card

The Raspberry Pi B+ requires a micro SD card, earlier variants require a regular SD card, or a Micro SD stuffed in a card adapter. RuneOS requires somewhat less than 4GB. Sizes larger than 4GB are not necessary, though models smaller than 8GB tend to have poor read-write speeds. Do yourself a favor and pick up a high-speed type, Class 6 or 10. 40MB/s read times or better will make for a quicker, more satisfying interface. 

![enter image description here](https://lh6.googleusercontent.com/zjukPBb75S6LZl6_mPkqTQd9K2ctxCSpPv0e9qGR5A=s400 "samsungsd.jpg")

###Card reader

You will be installing RuneOS on your SD card, and that card has to interface with your computer. If your computer does not have an integrated card reader, you can pick up USB types very cheap. 

![enter image description here](https://lh4.googleusercontent.com/fPNCbikcbEeFCvnh9uUUjcJuQuDDxgNhVZwN6GeyPA=s400 "cardreader.jpg")

###Media storage

- **Flash Drives.** For small libraries, flash drives are usually the ticket. Flash drives draw very little current, so there is no chance they will brown out your Raspberry Pi. Rpi B+ have four USB ports, earlier variants have two, all of which can be filled with cheap USB flash drive storage space. Make sure your flash drives are physically small enough that they can be plugged in next to each other. (You're going to have troubles with that novelty-flash-drive-encased-in-a-cricket-ball.) Before filling your flash drives with music, remove any pre-existing proprietary software that may interfere with RuneOS. 
- **USB external hard drives.** Both Solid State and Spin-up types may be used, but both tend to draw more current than a Raspberry Pi can offer. If hard drives are to be used, they must have their own power supply. Again, make sure that proprietary software has been deleted prior to populating with your music collection.
- **NAS Drives.** A hard drive mounted via ethernet on a local connection can be used as the system storage device. Find setup details [here.](http://www.runeaudio.com/documentation/runeui/sources/)

![enter image description here](https://lh4.googleusercontent.com/-lYgQpY5K9aI/VEtE8_C5gvI/AAAAAAAAAHU/zW9GSI8OrOE/s400/flash+drive.jpg "flash drive.jpg")

###Ethernet Connection and Wireless Router

Upon first use, RuneAudio requires a hard ethernet connection, and a local path which with to access RuneUI. Wireless dongles may be used after setup. 
	
![enter image description here](https://lh4.googleusercontent.com/-zFxz3t7j_5c/VEtFd6nVSYI/AAAAAAAAAHg/BIj7x1RwqgA/s400/cat5.jpg "cat5.jpg")

Optional Items
--------------

###Onboard DAC or Digital Output boards

Several small manufacturers have developed fine output boards that may be mated directly with Raspberry Pi variants. They allow either direct, high quality analouge output ready for your amplifier, or TosLink digital signal that stand-alone DACs can interpret into analouge signal. The native headphone output to all Raspberry Pi variants is pretty noisy and benefits by any DAC stage. These 'Hats' may not be required with your system, if your DAC has a USB input that can recieve the proper signal from the RPi. 

![enter image description here](https://lh5.googleusercontent.com/-ouxLDtMlQ8o/VEtGH84mkII/AAAAAAAAAHs/-wxF-yTLmaM/s400/iqaudiohat.png "iqaudiohat.png")

###Wireless dongle

If you do not usually have a local network set up near your soundsystem, a wireless dongle can be used to access the system.

![enter image description here](https://lh6.googleusercontent.com/-8LvDV-k6vm8/VEtGboOciDI/AAAAAAAAAH8/sR2f3vyCCys/s400/Edimax_Wireless_nano_USB.jpg "Edimax_Wireless_nano_USB.jpg")

###EMI filter

Switching power supply most commonly used with Raspberry Pis are known to be quite 'noisy,' and may introduce some switching 'noise' if plugged into the same power recepticle, even worse if plugged into a switched power supply as exists on many amplifiers.  If you are looking to up your game for a super high-fidelity source, an EMI filter placed between the power supply and power source can reduce a fair bit of that noise. 

###A Sweet Crib

We all like the neat look of a bare board and RuneAudio quietly doing amazing things with our music, but if you want a cleaner look, consider cramming everything into a classy chassis that can sit alongside the rest of your sweet looking audio gear. Check out the [forum](http://www.runeaudio.com/forum/tpa3116-runeaudio-project-t319.html) for some great inspiration! (If your project involves rhinestones, **please** post photos.) 


Alright, looks like you have everything you'll need. Let's head over to the [Quick-Start Guide](http://www.runeaudio.com/documentation/quick-start/quick-start-guide/) and put this all together.
