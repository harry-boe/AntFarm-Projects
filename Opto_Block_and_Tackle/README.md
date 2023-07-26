# Opto Z Endstop 

Optical Z endstop. Verry reliable and more than 5mm additional Z travel after the stop has triggered. This prevents nozzle crashers into the bed

Note that this repo only includes the STL's that are different from the original Block and Tackle mod
here: https://mods.vorondesign.com/detail/KeNx5zprqki3m2QAxOx67A


![Opto Z](./Images/Voron0_Block_and_Tackle_Z_Belt_Opto_2023-Jul-26_01-56-27PM-000_CustomizedView17259745481.png)
![Opto Z](./Images/Voron0_Block_and_Tackle_Z_Belt_Opto_2023-Jul-26_01-59-30PM-000_CustomizedView11296608679.png)


| EE-SX673A-WR | Schema|
|--- |--- |
| ![SX673A](./Images/Screenshot%202023-07-26%20at%2014.10.17.png) | ![SX673A](./Images/Screenshot%202023-07-26%20at%2014.12.22.png) | 
| Add one 1k to 4.7k pullup resistor as load between VCC (brown) and Out (black). L (Pink) is not used/connected. VCC and Out will be connected like a traditional microswitch | |
|  Remove the outer wire insulation and the strain relief near the sensor to reduce bulk and allow for easy installation.| |

# BOM

| Item | Source | Notes |
|--- |--- |--- |
| EE-SX673A-WR | https://www.aliexpress.com/item/1005004415419601.html | Multiple Sources |

