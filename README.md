Starbie - A Tiny Digital Pet

What is this project?
Starbie is a small digital pet that runs on a custom-designed printed circuit board (PCB). This project aims to teach PCB design and programming while creating an interactive mini companion.

How does this project work?
Starbie uses a XIAO ESP32-C3 microcontroller to run its program. An OLED screen displays the pet and buttons allow the user to interact with it. An MPU6050 motion sensor lets Starbie react to movement, and a DHT11 sensor provides temperature and humidity readings. There are also customizable actions that are programmed through Arduino including dance, love, and other features to give Starbie a unique personality.

List of hardware components:

XIAO ESP32-C3 microcontroller

0.96-inch OLED display

MPU6050 sensor

DHT11 sensor

Buttons(2x) and resistor(1x)

Custom PCB designed with KiCad

My Project Status:
The PCB design is complete and the firmware is still in progress. Once the physical parts arrive, I plan to assemble it and run the code on the Starbie. My goal is to have a finished design, test Starbie on the physical hardware, and prepare the files for manufacturing.

Repository Contents:

BOM.md — Bill of materials(written from the Hack Club Half Life project page)

JOURNAL.md — Project progress and development notes(written from the Hack Club Half Life progress page)

Additional PCB design files and Arduino firmware will be added as they are organized

PCB Design:
<img width="856" height="662" alt="Starbie_PCB_layout png" src="https://github.com/user-attachments/assets/49f82dbc-0a19-4cb7-97ca-d30963a6e10e" />

PCB Schematic Layout:
https://github.com/528390/Hack-Club-Half-Life/blob/main/Starbie_PCB_Schematic_Layout.png.png 
