---
title: "Introduction"
date: 2018-01-27T15:42:17+01:00
anchor: "introduction"
weight: 10
---

In this project, we aim to create an interesting Doorbell system. We use the Adafruit Feather RP2040 as the main microcontroller. This system can provide remote control, visual information, audio information with users.
In our desired scenes, there would be a door to distinguish the home and outside. 
On the outside, there is a sensor, a Circuit playground microcontroller has been installed.  When the sensor APDS9960 detects something below 40 cm, the system will start to work and send the distance and warning messages to the owners via the WIFI, provided by the Airlift wifi mode, the user can read the messages from the websites on the phone. 
In the home, there would be a ST7735R LCD screen, Adafruit STEMMA speaker installed. If some people want to visit the home, the speaker will power on when the sensor detects something, the visitor will shake the Playground as the doorbell, then the speaker will begin to play some audio and the LCD will display some pictures to give some messages to the owner.

![Example image](/1111.jpg)

{{< block note >}}
Consider Phlebas is Banks's first published science fiction novel set in the Culture, and takes its title from a line in T. S. Eliot's poem The Waste Land. A subsequent Culture novel, Look to Windward (2000), whose title comes from the previous line of the same poem, can be considered a loose follow-up.
{{< /block >}}

{{< youtube 4p-LufbBVxY >}}