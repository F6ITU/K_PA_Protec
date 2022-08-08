# K_PA_Protec

OpenHPSDR P.A. Protection board by LA2NI (Munin 400)


https://github.com/F6ITU/K_PA_Protec/blob/main/K_PA_Protec_down.png

![La carte de protection, périphérique de l'ATU Aries ](https://github.com/F6ITU/K_PA_Protec/blob/main/K_PA_Protec_down.png)


This protection board is part of a set consisting of a 400 W LD-Mos based RF power amplifier (Munin 400), 
a medium power (600 or 1500 W) Zolotarev low pass filter, an Automatic Antenna Tuner (ATU) nickname « Aries » 
and a 4 port antenna switch.

All these developments are the work of Kjell Karsten LA2NI and Laurence Barker G8NJJ.

This original work can be downloaded from 

https://github.com/LA2NI/


https://github.com/laurencebarker

The protection card ensures the physical measurements of the amplifier (VSWR, Power, Voltage, Current) and the shutdown of this amplifier in case of issues detected either by Aries (too high VSWR) or by any other sensor (temperature, voltage, current). It is used between Aries and Munin 400. 

For more information, please refer to the Aries documentation


This board was originally developed in September 2021 by Kjell LA2NI , with UltiBoard EDA. This repository is a « bug for bug » clone of the original Protection Board using the Opensource Kicad EDA. 

This port is placed under the CERN Open source/ Open hardware Licence.

The original work is protected by the TAPR Open Hardware licence

Kicad is an Opensource EDA software maintained by the European Reseach Center CERN (Conseil européen pour la recherche nucléaire)

