+++
title = 'LED Art Project - Overview'
description = 'Multi-part write up of an LED art project'
featured_image = 'led_art.jpg'
date = 2023-12-20T17:22:32Z
draft = true
+++

## Project Overview

I have used RGB LED strips in projects before, but only up to 20 or so LEDs in a project.  I wanted to create a piece of art using full strips. They come in 5m lengths containing 300 LEDs, and you can chain them together!  The completed piece of art is shown in the image below, but I am going to write a number of posts covering various aspects of the project.  The aim of the posts is to outline how I approach a project like this and also give some insight into the skills that the **Tinkerers** have in the group.

Key elements of the completed project are that it uses 600 LEDs that can each be driven with any colour.  The microcontroller that drives the LEDs is an ESP32.  I really like the ESP32 as it is cheap, powerful, and can connect to WiFi making it easy to integrate with other things.  This piece of art is connected to my "Home Automation" system which allows it to turn off when nobody is in the room, and turn back on when you are!  The ESP32 is easy to program using the [Arduino](https://www.arduino.cc/) tools, but in this case I have used [WLED](https://kno.wled.ge/) which is an open source project that runs on the ESP32 and already does all I want and more - No need to reinvent the wheel!

Finally the mounting board is painted plywood, strengthened with battens which also lift the board off the wall hiding the power supply and allowing lighting to shine out from behind the board as well as from the shape on the front.  Fixing the flexible strip to the board in the shape I wanted needed some custom mounts, which I 3D designed and printed using a 3D printer.

## Posts

The anticipated posts are as follows and I will update this section with links once I have posted a write up for each aspect.

1. Overview - This post
2. Design
3. Prototyping
4. Custom Printed Circuit Board (PCB)
5. 3D Printed Components