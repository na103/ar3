# Amiga Action Replay III remake

This repository contains the reverse engineering schematic for the Amiga Action Replay III and everything needed to build it.<br>
It is a work in progress, wait to build it I have to test it first.<br>
![alt text](https://github.com/na103/ar3/blob/main/img/3d.png "AR3")
<br>
<br>

## Bill of materials
| Qt. |    Description     |             Designator          |    Mouser part     |             Note              |
|:---:|--------------------|---------------------------------|--------------------|-------------------------------|
|6    |Resistor 1K         |R1-R4, R6, R7                    |CRCW12061K00FKEA    |                               |
|1    |Resistor 4.7K       |R5                               |CRCW12064K70FKEA    |                               |
|1    |Cap. 10uF 16V       |C1                               |EEA-FC1E100H        |                               |
|4    |Cap. 100nf          |C2-C5                            |C1206C104K5RAC7867  |                               |
|1    |Cap. 1uF 63V        |C6                               |ESS105M050AB2AA     |                               |
|5    |GAL16V8             |U1-U5                            |ATF16V8BQL-15JU     |                               | 
|1    |74F74               |U6                               |SN74LS74ANSR        |                               |
|2    |TMS27PC010A-20FML   |U7, U9                           |                    | from ebay or [utsource](https://www.utsource.net) |
|1    |HY6264ALJ-10        |U8                               |                    | from ebay or [utsource](https://www.utsource.net) |
|1    |TC55257BFL-85L      |U10                              |                    | from ebay or [utsource](https://www.utsource.net) |
|1    |MC1455              |U11                              |MC1455DR2G          |                               |
|1    |ZVP2106A            |Q1                               |ZVP2106A            |                               |
|1    |Trimmer 10K         |VR1                              |3362F-1-103LF       |                               |
|1    |Led red             |D1                               |C4SMA-RGY-CS4V1BB1  |                               |
|1    |Led green           |D2                               |C4SMA-GGY-CU2W37A1  |                               |
|1    |Diode               |D3                               |LL4148-M-18         |                               |
|1    |Button switch red   |SW1                              |D6C40F1LFS          |                               |
|1    |SPDT ON-ON switch   |SW2                              |2MS1T1B3M2QES       |                               |
|1    |Conn edge female 86p|CN1                              |ECC43DCAI-S189      | from ebay or digikey ECC43DCAI-S189 |



<br>
<br>
# License

This work is licensed under a Creative Commons Attribution 4.0 International License. See [https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/).

