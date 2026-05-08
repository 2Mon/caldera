---
title: "Caldera"
author: "1Mon"
description: "supervolcano heater hotend with 51mm of meltzone"
created_at: "2026-05-8"
---

# Research | 5/6/26

Hotend design!! this is my second shot at making a decent hotend. My goals for this are to have a large melt zone, nice heater, filament path, and thermistor packaging, while keeping it small and lightweight. I was inspired by hotends like v9 (https://www.v9hotend.com/), tricorn (http://tricornhotend.com/) and Turtle's double barrel hotend he made for #rework (https://github.com/ProgrammerTurtle/DoubleBarrel). These all have CNC'd heater blocks and heatsinks. 

My idea for this hotend is to use a supervolcano heater cartridge (likely a high wattage one from Lukes Lab), in combonation with a very light weight and compact block to have as little temperature gradient between the heater and the thermistor as possible. 

You can see that idea here in Turtle's hotend. 

<img height="500" alt="image" src="https://github.com/user-attachments/assets/22502a06-2d48-4d0c-9f4d-0a5168a87582" />

The heaters are extremely close to the filament path and nozzle, which means that they dont waste energy heating the rest of the block. The walls are also very thin, which means that less heat is lost into the block. Another advantage of this is that the thermistor is able to read a very accurate temperature at the nozzle. The further the thermistor is from the heater the larger the difference will be.

**Total time spent: 3 hours**

# Block Design | 5/6/26

There are multiple things I needed to balance in the block design for this hotend.
1. Performance: this is pretty self explanitory. I want big meltzone so lots of plastic can be pushed out. 
2. Manufacturability (is that a word?): Even though I am not the one who is milling this part, I dont want the JLCCNC worker machining this to have a hard time. Also other people might want to machine it themselves. 
3. Cost: Keep the machining simple so cost is low
4. Weight: I had to keep all the parts as light as possible. This is going to be moving at high speeds, so the less weight the better the rigidity will be. Low rigidity leads to crap print quality. 

The design is fairly simple. I started with a couple circles to give holes for the heater bore, meltzone, and thermisor to sit. I origonally planned to use an M3 pt1000 thermistor, but was told that a cartridge thermistor would have better thermal control. 
<img width="600" alt="image" src="https://github.com/user-attachments/assets/4c03910c-ed6a-4f24-8bd9-7ff9c70a4124" />

I basically just extruded that upwards enough to fit the threaded part of a heatbreak, a supervolcano nozzle adapter (more on that in a sec), and a nozzle. I also added a section at the top for heatbreak stuff. 

<img width="300" alt="image" src="https://github.com/user-attachments/assets/c3ece415-cbf8-4561-9cf7-f067826845e4" />

I added features to allow the pt1000 and heater to fit in, and cleaned up the cad a bit. 

<img width="300" alt="image" src="https://github.com/user-attachments/assets/afd294ab-4ebb-43c8-92fa-2bc6e6879756" />

Here you can see something close to the final heater block design. I added holes for grubscrews to clamp the heater as well as mounting holes for the heatsink mounts. 

**Total time spent: 3 hours**


