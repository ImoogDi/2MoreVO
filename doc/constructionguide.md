#  2MoreVO
 Construction of CEM/AS3340 dual analog VCO eurorack-modul.

**Table of Contents**

- [Preconditions](#preconditions)
- [Construction](#construction)
- [First Switchon](#firstswitchon)
- [License](#license)

## Preconditions<a name="preconditions"></a>

- All PCB-Boards must be available:  
    1. Two 'MoreVO_Core'- PCB's. 
    2. One 'Backplane' - PCB. 
    3. One 'Backplane B' - PCB. 
- All BOM-parts must be available for PCB-Board 'MoreVO_Core', 'Backplane' and 'Backplane B' (see BOM-files: [MoreVO_Core](./../hw/MoreVO_Core/bom/MoreVO_Core.html) and [Backplane](./../hw/bom/2MoreVO_backplane.html)).
- The frontpanel is required for aligned soldering all pots, jacks and switches on PCB-Board 'Backplane'.


## Construction<a name="construction"></a>

### PCB-Board: 'MoreVO_Core' (two of them)

>#### 'MoreVO_Core' back side smd-parts (start soldering here!) [back side parts](./pictures/MoreVO_Core_PCB_bot.png)

> start soldering smd-parts on back side of Board: 'MoreVO_Core'.  

>- place all SMD resistors and capacitors to the back side. Watch the rigth alignment.
>- place all SMD diodes to the back side. Watch the rigth orientation and alignment.
>- place the LDO voltage-regulator U1 to the back side. Watch the rigth orientation and alignment.
>- place the transistor Q1 to the back side. Watch the rigth orientation and alignment.
>- place the quad opamp U2 to the back side. Watch the rigth orientation and alignment.
>- solder all parts on back side (reflow or by hand).
>- at least 'MoreVO_Core'-PCB back side should look like: [MoreVO_Core back side smd-parts (rev.: 1.1)](./pictures/MoreVO_Core_bot_smds_only.png) 

>#### 'MoreVO_Core' top side smd-parts [top side parts](./pictures/MoreVO_Core_PCB_top.png)

> continue soldering smd-parts on top side of Board: 'MoreVO_Core'.  

>- place all SMD resistors and capacitors to the top side. Watch the rigth alignment.
>- solder all parts on top side (by hand).
>- at least 'MoreVO_Core'-PCB top side should look like: [MoreVO_Core top side smd-parts (rev.: 1.1)](./pictures/MoreVO_Core_top_smds_only.png) 

>#### 'MoreVO_Core' <u>M</u>ounting<u>T</u>hrough<u>H</u>ole-parts [MTH-parts](./pictures/MoreVO_Core_PCB_top.png)

> continue soldering MTH-parts on back side of Board: 'MoreVO_Core'.  
>- fit the 10-position, 1 row header to the back side and solder it at the top side.  
>- fit the  8-position, 1 row header to the back side and solder it at the top side.  

> continue soldering MTH-parts on top side of Board: 'MoreVO_Core'.  
>- place one DIP16 socket at U4-position on top side. Watch the rigth orientation and solder it on back side.  
>- place all pots (RV1...RV5) on top side. Watch the rigth values and orientation and solder them on back side.  
>- at least place styrene capacitor CF1 on top side and solder it on back side.  

### PCB-Board: 2MoreVO 'Backplane'

>#### 'Backplane' back side MTH-parts (start soldering here!) [back side parts](./pictures/Backplane_bot_parts_mounted.png)

> start soldering MTH-parts on back side of Board: 'Backplane'.  

>- place all resistors to the back side and solder them on top side.
>- fit the two 10-position, 1 row pin-sockets to the back side and solder them at the top side.  
>- fit the two  8-position, 1 row pin-sockets to the back side and solder them at the top side.  
>- fit the two 16-position, 1 row pin-sockets to the back side and solder them at the top side.  
>- at least place jumper J1_3 to the back side and solder it on top side.  

>#### 'Backplane' top side MTH-parts [top side parts](./pictures/Backplane_top_parts_mounted.png)

> continue soldering MTH-parts on top side of Board: 'Backplane'.  

>- place all resistors to the top side and solder them on back side. Be aware two of them mounted vertically.  
>- place all capacitors to the top side and solder them on back side.  
>- place all diodes to the top side. Watch the rigth orientation and solder them on back side.  
>- place the shunt regulator U1 to the top side. Be sure to mount it close as possible to the PCB. Watch the rigth orientation and solder it on back side.  
>- place one DIP8 socket at U2-position on top side. Watch the rigth orientation and solder it on back side.  
>- place two jumpers J1_1 and J1_2 on top side and solder them on back side.  
>- place two pots (RV1 and RV12) on top side. Watch the rigth orientation and solder them on back side.  
>- the currently mounted '2MoreVO'-backplane top side should look like: [2MoreVO backplane top side (rev.: 1.0)](./pictures/Backplane_top_parts_mounted.png) 

>- **All following parts have to be aligned to the frontpanel and not yet soldered **
>- fit that snapin-potentiometers PV4,PV5,PV6,PV7,PV8 and PV10 on PCB top side.
>- fit that snapin-potentiometers PV2 and PV3 on PCB top side.
>- fit that switches SW1,SW3,SW4,SW5 and SW6 on PCB top side. Must be ON-OFF-ON type with three positions.
>- fit that switch SW2 on PCB top side. Must be ON-ON type with two positions.
>- fit all twelve jacks on PCB top side.
>- place the **frontpanel** on top side parts and **align** them.
>- check alignment and distance to the frontpanel, see: [alignment](./pictures/2MoreVO_left.png)
>- use nuts for the jacks, switches and pots to fix that frontpanel to the PCB-parts.
>- now solder all parts on back side and make sure everything is still aligned.
>- mount two 10mm spacer with 3mm screws and plastic washer on the backplane.
>- at least the '2MoreVO backplane' without mounted frontpanel should look like: [backplane mounted parts](./pictures/Backplane_top_mounted.png) 

### PCB-Board: 2MoreVO 'Backplane B'

>#### 'Backplane B' top side MTH-parts (start soldering here!) [top side parts](./pictures/Backplane_B_top.png)

> start soldering MTH-parts on top side of Board: 'Backplane B'.  

>- place all resistors to the top side. **Important:** vertical mounted resistors have to be bend as close as possible to there resistore-cases (see: [vertical resistors mounted](./pictures/Backplane_spacer.png)). solder them on back side.
>- place all capacitors to the top side and solder them on back side.  
>- fit the two 16-position, 1 row header to the top side and solder them at the back side.  
>- at least 'Backplane B' top side should look like: [Backplane B top side parts (rev.: 1.0)](./pictures/Backplane_B_top_parts_mounted.png) 

>#### 'Backplane B' back side MTH-parts [back side parts](./pictures/Backplane_B_bot_parts.png)

> continue soldering MTH-parts on back side of Board: 'Backplane B'.  

>- place the electrolytic capacitors (C12/C15) to the back side. Watch the rigth orientation and solder them on top side.  
>- place the ceramic capacitors to the back side. solder them on top side.  
>- place all diodes to the back side. Watch the rigth orientation and alignment. solder them on top side.  
>- place the two transistors Q1 and Q2 to the back side. Watch the rigth orientation and solder them on top side.  
>- place the two pots to the back side. Watch the rigth orientation and solder them on top side.  
>- place the two pin- and three pin-jumpers to the back side and solder them on top side.  
>- place the 5-position, 2 row header to the back side and solder it at the top side.  
>- place the 8-position, 2 row header to the back side and solder it at the top side.  
>- place two DIP14 sockets at U3/U4-position on back side. Watch the rigth orientation and solder them on top side.  
>- place one DIP16 socket at U5-position on back side. Watch the rigth orientation and solder it on top side.  
>- at least 'Backplane B' back side should look compareable with this: (IC's not yet mounted) [Backplane B back side parts (rev.: 1.0)](./pictures/Backplane_B_bot_parts_mounted.png) 


## First Switchon<a name="firstswitchon"></a>
 Preconditions:

- Unmount any IC from the sockets on '2MoreVO Backplane B' if not already done.
- Push IC U2 (TL072) into the DIP-socket on '2MoreVO Backplane'.
- Push the '2MoreVO Backplane B' into the pin-sockets of '2MoreVO Backplane'.
- connect one 16pin buscabel between eurorack-bus and the '2MoreVO Backplane B' (watch the alignment of Pin1 := -12V).
- The two 'MoreVO_Core'-boards aren't yet mounted.
- The frontpanel isn't yet mounted.

 Action Step1:

- Switch **on** the eurorack-case power.
- Measure voltages at points:  

<table>
<tr>
    <th>2MoreVO Board</th>
    <th>measuring point</th>
    <th>measured voltages</th>
    <th>remark</th>
</tr>
<tr>
    <td>Backplane (top side)</td>
    <td>IC U2 Pin8</td>
    <td>+12 Volt</td>
    <th></th>
</tr>
<tr>
    <td>Backplane (top side)</td>
    <td>IC U2 Pin4</td>
    <td>-12 Volt</td>
    <th></th>
</tr>
<tr>
    <td>Backplane (back side)</td>
    <td>J16 and J18 Socket-Pin2</td>
    <td>+12 Volt</td>
    <th>Plus eurorack-power for 'MoreVO_Core' 1 and 2</th>
</tr>
<tr>
    <td>Backplane (back side)</td>
    <td>J16 and J18 Socket-Pin3</td>
    <td>-12 Volt</td>
    <th>Minus eurorack-power for 'MoreVO_Core' 1 and 2</th>
</tr>
<tr>
    <td>Backplane B (back side)</td>
    <td>Testpoint +2V</td>
    <td>range: +1.5 to +2.5 Volt</td>
    <th>will be adjusted in calibration-procedure</th>
</tr>
<tr>
    <td>Backplane B (back side)</td>
    <td>Testpoint -2V</td>
    <td>range: -1.5 to -2.5 Volt</td>
    <th>will be adjusted in calibration-procedure</th>
</tr>
<tr>
    <td>Backplane B (back side)</td>
    <td>U3 and U4 DIP14-Pin14</td>
    <td>+12 Volt</td>
    <th>Plus eurorack-power</th>
</tr>
<tr>
    <td>Backplane B (back side)</td>
    <td>U3 and U4 DIP14-Pin7</td>
    <td>-12 Volt</td>
    <th>Minus eurorack-power</th>
</tr>
<tr>
    <td>Backplane B (back side)</td>
    <td>U5 DIP16-Pin16</td>
    <td>+12 Volt</td>
    <th>Plus eurorack-power</th>
</tr>
<tr>
    <td>Backplane B (back side)</td>
    <td>U5 DIP16-Pin8</td>
    <td>-12 Volt</td>
    <th>Minus eurorack-power</th>
</tr>
</table>

 Action Step2:

- Switch **off** the eurorack-case power.
- Mount the frontpanel on '2MoreVO Backplane'.
- Insert all IC's on '2MoreVO Backplane B'. Watch the rigth orientation.
- Insert the two 'MoreVO_Core'-boards into the pin-sockets on '2MoreVO Backplane' intended for VCO1 and VCO2. Don't yet insert the CEM3340/AS3340 into there sockets.

 Action Step3:

- Switch **on** the eurorack-case power.
- Measure voltages at points:  

<table>
<tr>
    <th>2MoreVO Board</th>
    <th>measuring point</th>
    <th>measured voltages</th>
    <th>remark</th>
</tr>
<tr>
    <td>both MoreVO Core Boards (top side)</td>
    <td>U4 DIP16-Pin16</td>
    <td>+10 Volt DC</td>
    <th>+- 1% voltage accuracy</th>
</tr>
<tr>
    <td>both MoreVO Core Boards (top side)</td>
    <td>U4 DIP16-Pin3</td>
    <td>-5 Volt DC</td>
    <th>less then +- 2% voltage accuracy</th>
</tr>
</table>

- Switch **off** the eurorack-case power.

 Result:

If any measurement is out of range check the boards and repeat the required steps.

 Postconditions:

- push the IC's:=CEM3340 or AS3340 into the socket on the two 'MoreVO Core'-boards. Watch the rigth orientation.
- Calibration of the boards is required and defined in the calibration-procedure.  

- at least the '2MoreVO'-board back side should look like: [2MoreVO back side](./pictures/2MoreVO_back.png) 

## License<a name="license"></a>
> Hardware:cc by-nc-sa 4.0

