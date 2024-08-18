# Amiga Action Replay III remake

This repository contains the reverse engineering schematic for the Amiga Action Replay III and everything needed to build it.<br>
It is a work in progress, wait to build it I have to test it first.<br>
![alt text](https://github.com/na103/ar3/blob/main/img/3d_1.png "AR3")
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
|5    |PLCC 20 POS Socket  |U1-U5                            |540-88-020-17-400-TR| Optional                      |
|1    |74F74               |U6                               |SN74LS74ANSR        |                               |
|2    |27C010 OTP EPROM    |U7, U9                           |AT27C010-70JU-T     |                               |
|1    |SRAM 64K            |U8                               |AS6C6264-55SCN      |                               |
|1    |SRAM 256K           |U10                              |AS6C62256-55SCN     |                               |
|1    |MC1455              |U11                              |MC1455DR2G          |                               |
|1    |ZVP2106A            |Q1                               |ZVP2106A            |                               |
|1    |Trimmer 10K         |VR1                              |3362F-1-103LF       |                               |
|1    |Red LED             |D1                               |TLCS5100            |                               |
|1    |Green LED           |D2                               |TLCYG5100           |                               |
|1    |Diode               |D3                               |LL4148-M-18         |                               |
|1    |Button switch red   |SW1                              |D6C40F1LFS          |                               |
|1    |SPDT ON-ON switch   |SW2                              |2MS1T1B3M2QES       |                               |
|1    |Conn edge female 86p|CN1                              |ECC43DCAI-S189      | from ebay or digikey ECC43DCAI-S189 |


<br>
If you found this my work useful, please consider buying me a cup of coffee if you want:<br>
<a href='https://ko-fi.com/na103' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/cup-border.png' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>

# License

This work is licensed under a Creative Commons Attribution 4.0 International License. See [https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/).

