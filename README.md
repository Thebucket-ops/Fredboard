# ***THE FREDBOARD V1/V2***
  The fredboard is a custom pi pico devboard:
  - the v1 allows to use all but one pins provided by the rp2040, and has a led to indicate when the devboard is powered
  - the v2 has a MPU-6050 and has a reboot button with a led to indicate the restart

## **V2 (UNTESTED)**
![front of the fredboard v2](/v2/render/devboard.png "boring side of the fredboard")
![back of the fredboard v2](/v2/render/devboardback.png "look at that lizard smiling while riding his long skateboard")

### **SCHEMATICS**
  Here's the schematic for the pcb, you can see the whole project from /PCB

![The Schematic for the v2 project](/v2/render/schematic.pdf "schematic")

### **THE PCB**
  This is the pcb, front and back (image art can be found on /img/devboard):

![The pcb front v2](/v2/render/pcbfront.png "PCB front")
![The pcb back v2](/v2/render/pcbback.png "PCB front")

### **BOM and Gerber**
  The Bill Of Materials and the Gerber files can be found in the /PCB/production folder, these are the required materials:

 - 2 33pF 0402 capacitors
 - 13 0.1uF 0402 capacitors
 - 2 1uF 0402 capacitors
 - 2 10uF 0603 capacitors
 - 1 10 nF 0402 capacitor
 - 1 2.2 nF 0402 capacitor
 - 1 0402 white led
 - 1 USB_C_Receptacle_USB2.0_14P
 - 2 pinheaders 1x20 (optional)
 - 1 pinheader 1x3 (optional)
 - 2 0402 27 ohm resistors
 - 1 0402 150 ohm resistor
 - 2 0402 1K resistors
 - 2 0402 5.1K resistors
 - 1 0402 10K resistor
 - 2 SW_Push_SPST_NO_Alps_SKRK button
 - 1 RP2040
 - 1 MCP1700x-330xxTT
 - 1 W25Q16JVUXIQ TR flash memory
 - 1 Crystal_SMD_3225-4Pin_3.2x2.5mm
 - 1 MPU-6050


## **V1 (UNTESTED)**
![front of the fredboard](/img/frontpcb.png "boring side of the fredboard")
![back of the fredboard](/img/backpcb.png "look at that lizard smiling while riding his long skateboard")

### **SCHEMATICS**
  Here's the schematic for the pcb, you can see the whole project from /PCB

![The Schematic for the project](/img/schematic.png "schematic")

### **THE PCB**
  This is the pcb, front and back (image art can be found on /img/devboard):

![The pcb](/img/pcb.png "PCB")


### **BOM and Gerber**
  The Bill Of Materials and the Gerber files can be found in the /PCB/production folder, these are the required materials:

 - 10 0.1uF 0402 capacitors
 - 2 1uF 0402 capacitors
 - 2 10uF 0603 capacitors
 - 2 33pF 0402 capacitors
 - 1 0402 white led
 - 1 USB_C_Receptacle_USB2.0_14P
 - 2 pinheaders 1x20 (optional)
 - 1 pinheader 1x3 (optional)
 - 2 0402 5.1K resistors
 - 2 0402 27 ohm resistors
 - 2 0402 1K resistors
 - 1 0402 10K resistor
 - 1 SW_Push_SPST_NO_Alps_SKRK button
 - 1 RP2040
 - 1 MCP1700x-330xxTT
 - 1 W25Q16JVUXIQ TR flash memory
 - 1 Crystal_SMD_3225-4Pin_3.2x2.5mm