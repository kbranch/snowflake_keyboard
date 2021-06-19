# Snowflake Keyboard
![Overview Image](/pictures/overview.jpg)

This is a weird, tightly spaced split keyboard that I designed to be very specific to my needs. It uses 17x16 mm key spacing rather than the standard 19x19 mm (inspired by [this post](https://www.reddit.com/r/ErgoMechKeyboards/comments/hudjyt/current_research_on_ergonomics_keyboard_design/)). The odd keys on the outside bottom corners are meant to be pressed with the pinky's knuckle rather than a fingertip. I haven't included every detail necessary to build the whole keyboard since it's so specific to my needs, but I'm happy to share and/or answer questions if somebody is interested in more detail for some reason.

The original CAD files are public on OnShape: [Case](https://cad.onshape.com/documents/9b32c1e8e8106ea44925f1b6/w/90cc6aeac4d327d0808a83e7/e/3e782787b37f9a3620b3203b) and [Keycaps](https://cad.onshape.com/documents/7a9b7e869b26a13f2521e861/w/94ad519ba1de32380f27d44b/e/4a5e31582eda700c8368bdb9). Generating the keycap legends is a pretty manual and sometimes fiddly process. I believe I included copies of all of the STLs I used, but I may have forgotten a few. 3mf files are included for the keycaps and legends, which should load into PrusaSlicer with all models in their correct quantities and print settings ready to go for a Prusa i3 MK3S.

All 3D printed parts are designed to be printed without support. I used manual mid-print color changes to embed the LED diffuser pieces into the case and for the keycap legends. M2 screws and nuts hold the PCB and plate to the case, and M3 screws and nuts hold the case halves and palm rests together. Little o-rings sit between the plate and case.

I used USB-C for both the actual USB connector and the board to board connection. I repurposed some [USB-A to USB-C adapters](https://www.amazon.com/gp/product/B07VCZV3R4/ref=ppx_yo_dt_b_asin_title_o09_s00?ie=UTF8&psc=1) to use as panel mount USB-C connectors. I ended up needing to grind the fronts down a bit to allow for cables to snap in fully through the case thickness.

The referenced QMK version includes a small tweak to allow the brightness of the indicator LEDs to follow the regular LED animation brightness. The LEDs are set up to indicate the active layer and the status of num, caps and scroll lock - they're not intended for flashy animations.

![Inside Image](/pictures/inside.jpg)
