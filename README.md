# LED-Ladybug-Keychain
This is my first legitimate project that I'm submitting, and it is a ladybug keychain connected to a 555 monostable timer that lights up my LED for 5 seconds after pressing a button. 

<img width="814" height="727" alt="image" src="https://github.com/user-attachments/assets/0de64032-71db-49f2-bf06-45b85e2f6070" />
<img width="1319" height="715" alt="MeasurementsForPCB" src="https://github.com/user-attachments/assets/08020419-1c62-4053-ac02-8314efd25d7f" />
<img width="488" height="315" alt="image" src="https://github.com/user-attachments/assets/17ccac7f-b097-433c-9156-c2dcf7b89069" />

# Install
The PCB components need to be soldered together into the board, and it will fit directly inside my ladybug casing. A battery gets hooked up to the screw terminals and will hide underneath the PCB in the casing itself. 

# Using the Piece
The LED lights up when the pushbutton is pressed due to using a 555 monostable timer, and the button has a cutout in the casing for easy access. 

# Bill of Materials

|  Component  |  Quantity  |  Unit  |  Description  | 
|---------------------------------------------------|
| NE555 Chip  |      1     |        |Controls Timing|
|---------------------------------------------------|
| Resistor    |      2     |10k ohm |Limits Current |
|---------------------------------------------------|
| Resistor    |      1     |470 ohm |Limits Current |
|---------------------------------------------------|
| Red LED     |      1     |        |Lights up      |
|---------------------------------------------------|
| Capacitor   |      1     | 470uF  |Timing Limitor |
|---------------------------------------------------|
| Capacitor   |      1     | 100nF  |Energy Storage |
|---------------------------------------------------|
| Pushbutton  |      1     |       |Triggers circuit|
|---------------------------------------------------|
|6 Term Screw |            |     |Allows positive   |
| Terminals   |      2     | |& negative connections|
|---------------------------------------------------|
|9volt Battery|      1     |9 volts | Powers Circuit| 
|---------------------------------------------------|


# Files for PCB and Onshape Design
Schematic Design - 
<img width="970" height="788" alt="image" src="https://github.com/user-attachments/assets/d2f74d29-ff3c-48a0-8357-7f5f70c0abd8" />
PCB Design - 
<img width="955" height="506" alt="image" src="https://github.com/user-attachments/assets/f628d265-5930-41a9-8dd0-4e33ff03a9fc" />
Onshape Design - 
<img width="660" height="598" alt="image" src="https://github.com/user-attachments/assets/2014aa66-1414-4c40-8d42-ad04f6b02e88" />

