# DIY - Smart Home Power Relay (ESP8266)
There exists many Relay-Modules based on ESP8266 or other wireless Modules, but I could not find a Module that fits in a european Wallbox and is independent of protocols or wireless standards. That’s why I've created my own Solution: <br>
![Power,Relay and ESP Module](https://cloud.githubusercontent.com/assets/11909453/18434072/5daa4cb4-78eb-11e6-865b-17c6970bbcd9.png)<br> 

> **Caution: These modules do not have any certifications… In most countries it’s not legal to use it in Production. <br>And: 230V AC can kill !**

The main goals for this Project are:
 -	As **small** as possible
 -	As **cheap** as possible
 -	As **save** as possible
 -	As **flexible** as possible

Specially the flexibility is something important for me, as I have different scenarios to fulfill and I want to be able to change the wireless technology if it’s required. This is the reason why the result is not a single Module, there are currently 3 Modules: Power, Relay and Wireless (currently based on a ESP8266-12) <br>
<img src="https://cloud.githubusercontent.com/assets/11909453/18467891/ed95e96c-79a1-11e6-883f-d4646f68d3db.png" width="400"> <br>
<img src="https://cloud.githubusercontent.com/assets/11909453/18434075/5ddd3142-78eb-11e6-8e0a-02ff5e7ba243.png" width="300"> <br>
With a **size** of 45mm * 35mm * 20mm (Length, Width, Height) for all three Modules,  it's small enough to mount it in wall (e.g. behind a power switch).

The price for the material is around **14$ (for all three modules)**. 

Eagle and Gerber Files are part of this Project. The Modules are Open-Hardware, feel free to reproduce... Feedback is Welcome.

## Power Module
Input: 100-240V AC<br>
Output: 5V and 3.3V DC (3W Total)<br>
Size: 45mm * 20mm * 20mm (length, width, height)<br>
<img src="https://cloud.githubusercontent.com/assets/11909453/18434069/5d19f8b2-78eb-11e6-9f84-c34a4af077a0.png" width="800"> <br>

### Schema
<img src="https://cloud.githubusercontent.com/assets/11909453/18434070/5d5881fe-78eb-11e6-8329-78c9f57f4448.png" width="600"> <br>
### Layout
<img src="https://cloud.githubusercontent.com/assets/11909453/18434073/5daad94a-78eb-11e6-9c4e-ed430878a274.png" width="600"> <br>
### Bill of Materials

|Item|Price (USD)|
|:---|---:|
|1 * Fuse 500ma (MF2410F0.500TM)|0.30|
|1 * Connector Block (4-Ports)|0.70|
|2 * 47uF Tantal Capacitor|0.90|
|1 * Voltage Regulator 3.3V (MC33269ST-3.3T3G)|0.90|
|1 * Power-Supply 5VDC 3W (Hi-Link)|2.75|
|1 * Print|1.00|
|Total:|6.55|

## ESP Module
Size: 40mm * 20mm * 5mm (length, width, height)<br>
<img src="https://cloud.githubusercontent.com/assets/11909453/18434079/5df5a326-78eb-11e6-87fa-6e3e9b86b671.png"><br>

### Schema
<img src="https://cloud.githubusercontent.com/assets/11909453/18434076/5ddf1aa2-78eb-11e6-97ed-82c2312c69ee.png" width="600"> <br>
### Layout
<img src="https://cloud.githubusercontent.com/assets/11909453/18434078/5df57180-78eb-11e6-9b7f-183fe6fe5615.png" width="600"> <br>
### Bill of Materials

|Item|Price (USD)|
|:---|---:|
|4 * Resistor 10k|0.45|
|1 * ESP8266-12F|1.75|
|1 * Print|1.00|
|Total:|3.20|

## Relay Module
Input: PWR 5V, Signal 3V<br>
Output: 250V 10A<br>
Size: 45mm * 10mm * 20mm (length, width, height)<br>
<img src="https://cloud.githubusercontent.com/assets/11909453/18434074/5db6f9f0-78eb-11e6-847e-435527d89558.png"> <br>

### Schema
<img src="https://cloud.githubusercontent.com/assets/11909453/18434077/5ddf383e-78eb-11e6-9c33-0deaa92f1701.png" width="600"> <br>

### Layout
<img src="https://cloud.githubusercontent.com/assets/11909453/18434071/5d86098a-78eb-11e6-81ee-bdacc55e0a95.png" width="600"> <br>

### Bill of Materials

|Item|Price (USD)|
|:---|---:|
|1 * Gate Driver (MDC3105LT1G)|0.50|
|1 * Relay (ALQ305)|2.35|
|1 * Connector Block (2 Ports)|0.30|
|1 * Print|1.00|
|Total:|4.15|
