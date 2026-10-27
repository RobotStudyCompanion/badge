# RSC Badge

This repository contains the PCB design files for the **RSC Badge**, developed for the Robot Study Companion (RSC; [rsc.ee](https://rsc.ee/)) project.

The board is a small electronic badge featuring an astable multivibrator circuit that drives blinking LEDs. 

For the circuit design we were explicitly inspired by the KiCad workshop at [https://gitlab.com/evils/kicad-workshop](https://gitlab.com/evils/kicad-workshop).

We prepared this project as a simple and compact PCB badge for RSC affiliated events.


## Design Summary

We designed the PCB in **KiCad 10.0**.

The astable multivibrator circuit comprises two transistor stages.

When pressing the button switch, the transistors alternate ON and OFF states, causing the LEDs to blink alternately, while the middle LED stays powered.

The board includes:
- Two LEDs
- Two transistors
- Button switch
- CR2032 battery holder
- Informative silkscreen
- Resistors and capacitors (current limiting and oscillation rate setting)
- Compact badge with a face-shape layout (pareidolia)


### Front

![RSC Badge front side](images/badge_front.png)

### Back

![RSC Badge back side](images/badge_back.png)

## Assembled 2026 RSC Badge:

![RSC Badge final product](images/badge_ifixit.png)

![RSC Badge final product](images/day2_pcbway.jpg)

---

## Author

Timur Kedrov and Matevž Borjan Zorec 

Supervised by Farnaz Baksh

© Robot Study Companion 2026