# Vaja11-LCD2x16-STM32F0

PINOUT MIKROPROCESORJA:\
![konfig](https://github.com/Hudi452/Vaja11-LCD2x16-STM32F0/blob/main/Pinout_konfiguracija.png)

FOTOGRAFIJA VEZAVE:\
![vezje](https://github.com/Hudi452/Vaja11-LCD2x16-STM32F0/blob/main/Fotografija_vezave.jpg)

VIDEO DELOVANJA:\
![video](https://github.com/Hudi452/Vaja11-LCD2x16-STM32F0/blob/main/Video%20delovanja.gif)

ODGOVORI NA VPRAŠANJA:\
2.\
b)\
E = PB11\
RS = PB12\
D4 = PB13\
D5 = PB14\
D6 = PB15\
D7 = PD8\
e) Nova frekvenca bo 84 MHz, saj je največja frekvenca 168 MHz.\
f) Hitrost podatkov na vodilih je nastavljena na Low (majhno hitrost).\
3.\
h)\
x: min = 0, max = 15\
y: min = 0, max = 1\
Funkcija itoa je okrajšava za integer to ASCII. Celo število (int) pretvori v niz znakov.\
Funckijo itoa moramo uporabiti, saj LCD zasloni razumejo le posamezne znake (ASCII kode).\
Tretji argument v tej funkciji nam pove številski sestav, v katerem bo vrednost prikazana (desetiški).
