# AutoCut-Charger
## Plan
This board is designed for trickle charging a lead acid battery and turn of the charging automatically once it reaches the max rated voltage of the battery automatically. the cutoff voltage can be set using the trim pot.
## How to use 
Its pretty simple to use we just need to connect a 12-0-12 transformer to the circuit and the ac voltage will be rectified from Full bridge rectifier then using RV1 we set the output voltage and measure it using a multimeter one we are at it then we will use the rv2 to set the cutoff voltage we will know that we are at the cutoff when we will see the full led turned on and the relay clicks.
## Connection Guide 
The connections are pretty straight froward the 12-0-12 from the center tap transformer goes to the 3 pin terminal of the PCB and the battery +ve and -ve is connected to the 2 pin terminal on the labelled pins


## Parts Requried 
- 12-0-12 transformer 
- 12v relay
- LM317t voltage regulator
- MJE2955 transistor  

## PCB and Schematic and CAD

<img width="595" height="306" alt="image" src="https://github.com/user-attachments/assets/322409dd-e026-4346-9ed5-ef633f605875" />
<img width="1073" height="531" alt="image" src="https://github.com/user-attachments/assets/9f42ce76-1c56-4344-8653-94625bd0850d" />
<img width="1374" height="347" alt="Screenshot 2026-01-24 192306" src="https://github.com/user-attachments/assets/8f379d24-2389-4262-898d-ea417f5823ca" />
<img width="1030" height="673" alt="Screenshot 2026-02-12 204520" src="https://github.com/user-attachments/assets/dd3b2a4e-5754-4921-9015-883352587d7d" />



# BOM 


| Name                                                                                           | Qty | Vendor     | Price ($) |
| ---------------------------------------------------------------------------------------------- | --- | ---------- | --------- |
| ALL BOM parts mosfet,resistor capacitors etc  |  | LCSC | 14     |
| [12-0-12 3A](https://robu.in/product/high-quality-12v-0v-12v-3a-center-tapped-stepdown-transformer/) | 1   | ROBU      | 6      |
|PCB||JLCPCB|5|
|Total|||25|
