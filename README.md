# K_PA_Protec

OpenHPSDR P.A. Protection board by LA2NI (Munin 400)

This protection board is part of a set consisting of a 400 W LD-Mos based RF power amplifier (Munin 400), a medium power (600 or 1500 W) Zolotarev low pass filter, an Automatic Antenna Tuner (ATU) nickname « Aries » and a 4 port antenna switch.

The protection card ensures the physical measurements of the amplifier (VSWR, Power, Voltage, Current) and the shutdown of this amplifier in case of issues detected either by Aries (too high VSWR) or by any other sensor (temperature, voltage, current). It is used between Aries and Munin 400. 

For more information, please refer to the Aries documentation


This map was originally developed by Kjell LA2NI in September 2021, with UltiBoard EDA. This repository is a « bug for bug » clone of the original Protection Board using the Opensource Kicad EDA. 

This port is placed under the CERN Open source Licence.

The original work is protected under the TAPR Open Hardware licence

Kicad is an Opensource EDA software maintained by the European Reseach Center CERN (Conseil européen pour la recherche nucléaire)

