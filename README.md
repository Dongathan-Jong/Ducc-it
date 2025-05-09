# Ducc It!
![Ducc_it_bedslinger_2025-Mar-24_02-10-12AM-000_CustomizedView1084799181_jpg](https://github.com/user-attachments/assets/4a3d2dac-56e1-479c-b29f-4d04f466ee3d)

### What is it?
This is a WIP DIY 3D printer for Hack Club's Infill YSWS! Check out my progress here: https://infill.hackclub.com/printers/ducc-it/

### Features
Here are some features: 
- 160x160x160mm Print Volume
- Cantilever Design
- Auto Ejecting prints
- Fits under $300 USD
- At least 100mm/s printing
- Klipper support

### BOM

The BOM is here: https://docs.google.com/spreadsheets/d/1qOZgMDn6hGFZKtvJTQ3WRMCq_ESmatV1Npfq33ltyqs/edit?gid=0#gid=0

### Progress

Check out my log [here](https://github.com/Dongathan-Jong/Ducc-it/blob/main/Duccbook.md)! 

### To Do

- Create a servo mount for the auto-ejecting print mount
- Create the auto-ejecting macro on klipper


*Please note that the step file in the repository does NOT include the fans + extruder, this is due to GitHub's size limit on big files.*

### Main Troubles

This was my first time using f360 for actual CAD work! It took a little while as the first CAD software I used and stuck w/ was Tinkercad, a pretty beginner website. Throughout building the printer, I found that these motor mounts aren't even bent to a proper 90 deg! I ended up creating my own motor mounts 3d printed, as for if they work well, not too sure if that will happen! 

### Tuning / Upgrades

As the goal was to be under $300 USD, but given klipper's amazing support, an ADXL sensor can be used to tune the X and Y axes. As for upgrades, many can be made, starting off with bed levelling. Currently it uses a Z limit switch with no probing and manual bed levelling screws, but it seems to work pretty well. 
