# AutoCut-Charger
## Plan
This board is designed for trickle charging a lead acid battery and turn of the charging automatically once it reaches the max rated voltage of the battery automatically. the cutoff voltage can be set using the trim pot.
## How to use 
Its pretty simple to use we just need to connect a 12-0-12 transformer to the circuit and the ac voltage will be rectified from Full bridge rectifier then using RV1 we set the output voltage and measure it using a multimeter one we are at it then we will use the rv2 to set the cutoff voltage we will know that we are at the cutoff when we will see the full led turned on and the relay clicks.

## Parts Requried 
- 12-0-12 transformer 
- 12v relay
- LM317t voltage regulator
- MJE2955 transistor  

## PCB and Schematic and CAD

<img width="677" height="343" alt="Screenshot 2026-01-25 002654" src="https://github.com/user-attachments/assets/d5700362-9e8f-4afb-bf5d-2d1044c80f93" />
<img width="914" height="460" alt="Screenshot 2026-01-25 002048" src="https://github.com/user-attachments/assets/49a0edaf-1613-42f1-af0e-51bb1316dfab" />
<img width="1374" height="347" alt="Screenshot 2026-01-24 192306" src="https://github.com/user-attachments/assets/8f379d24-2389-4262-898d-ea417f5823ca" />
<img width="1030" height="673" alt="Screenshot 2026-02-12 204520" src="https://github.com/user-attachments/assets/dd3b2a4e-5754-4921-9015-883352587d7d" />



# BOM 


| Name                                                                                           | Qty | Vendor     | Price ($) |
| ---------------------------------------------------------------------------------------------- | --- | ---------- | --------- |
| ALL BOM parts mosfet,resistor capacitors etc  |  | LCSC | 14     |
| [12-0-12 3A](https://robu.in/product/high-quality-12v-0v-12v-3a-center-tapped-stepdown-transformer/) | 1   | ROBU      | 6      |
|PCB||JLCPCB|5|
|Total|||25|
