---
title: "LED Ladybug Keychain"
author: "Allie Perkey"
description: "I'm currently working on an LED keychain where a 555 monostable timer is connected to an LED circuit, where once the pushbutton is pressed, the light will stay on for 5 seconds, turn off, waiting for the button to be pushed again. This is the first prototype, once I know this will work correctly, I'm going to work on an astable timer, where the light blinks continuously for a certain amount of time. My PCB is still going to be in a rectangular shape for convenience, but I am going to 3D model a cover for the board in a ladybug shape."
created_at: "2026-10-22"
---

# October 22: Designed my schematic layout

I started working on a design on how I wanted to lay out my schematic, and how I was going to arrange my components. This is the first schematic I've designed myself and ran into a couple issues with trying to figure out how to connect a power supply to my circuit. 

<img width="1055" height="841" alt="Schematic1" src="https://github.com/user-attachments/assets/cc0149e6-8a77-45e2-99ce-7b3e4cbf80be" />

**Total time spent: 2.5 hours**

# October 23: Finished schematic design, started PCB layout

Once figuring out a good power supply option would be using 01x06 screw terminals, one dedicated to positive and one designated to negative, I was able to correctly set up my schematic. After running it through the Electrical Rules Checker and no errors were found, I exported it into the PCB editor, where the layout of the design was started. Most of the day was struggling to find the correct footprints for the screw terminals and different PWR_FLAG options. 

<img width="1034" height="674" alt="image" src="https://github.com/user-attachments/assets/a96d5779-389b-452c-9e05-8747df3adb3a" />
<img width="968" height="647" alt="image" src="https://github.com/user-attachments/assets/996c1297-c945-4653-9351-dd271269ad2d" />

**Total time spent: 2.5 hours**

# October 26: Finished PCB Layout

After assigning the correct footprints to all of the different components, the layout for the PCB was designed. I put all my pieces together to fit correctly on a rectangular board; I connected all the copper layers to each other. There were several issues with trying to fit all of the different layers together without overlaying on top of the other. After running it through the DRC and viewing the 3D Viewer to make sure everything was laid right, I decided the hardware design was finished. Tomorrow, I'm going to tackle trying to figure out how to design the cover to look as a ladybug, while also being able to see the LED as it lights, as is the whole point of the design. 

<img width="994" height="653" alt="image" src="https://github.com/user-attachments/assets/06272c02-bd5d-41e0-8dbb-8401c25ced7e" />

**Total time spent: 2.5 hours**
