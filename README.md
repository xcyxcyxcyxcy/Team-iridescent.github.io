# Interesting Doorbell System
<div align=center><img width="1200" height="600" src="https://github.com/xcyxcyxcyxcy/Team-iridescent.github.io/blob/main/image/Arlo-video-doorbell-best-video-doorbells-crop-6d815f7.jpg"/></div>

## Project showcase

In this project, we aim to create an interesting Doorbell system. We use the Adafruit Feather RP2040 as the main microcontroller. This system can provide remote control, visual information, audio information with users.

In our desired scenes, there would be a door to distinguish the home and outside. On the outside, there is a sensor, a Circuit playground microcontroller has been installed.  When the sensor APDS9960 detects something below 40 cm, the system will start to work and send the distance and warning messages to the owners via the WIFI, provided by the Airlift wifi mode, the user can read the messages from the websites on the phone. 

In the home, there would be a ST7735R LCD screen, Adafruit STEMMA speaker installed. If some people want to visit the home, the speaker will power on when the sensor detects something, the visitor will shake the Playground as the doorbell, then the speaker will begin to play some audio and the LCD will display some pictures to give some messages to the owner.

There are some images and video of our whole system:
<div align=center><img width="600" height="400" src="https://github.com/xcyxcyxcyxcy/Team-iridescent.github.io/blob/main/image/system.png"/></div>
<div align=center><img width="600" height="400" src="https://github.com/xcyxcyxcyxcy/Team-iridescent.github.io/blob/main/image/system2.png"/></div>
<div align=center><img width="600" height="400" src="https://github.com/xcyxcyxcyxcy/Team-iridescent.github.io/blob/main/image/ezgif.com-gif-maker.gif"/></div>

## Project instructions
### Components used
* Adafruit Feather  RP2040 
* Airlift wifi module
* APDS 9960 sensor
* ST7735R
* Adafruit STEMMA Speaker
* Relay
* Circuit Playground Express
* Several cables
### Assembly details
<div align=center><img width="600" height="400" src="https://github.com/xcyxcyxcyxcy/Team-iridescent.github.io/blob/main/image/5031671205774_.pic.jpg"/></div>
