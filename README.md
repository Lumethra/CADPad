# CADPad

## What is this?? 

SHHH, this is a gift, dont spoiler it, SHHHH. But what exactly is this?? Good question. Its a keyboard. Again. Wait, what does again mean, well its my second one. My [Auth75](https://github.com/Lumethra/Auth75) was my first one. Back to what this is. Its technically a keyboard, but I would rather call it a Macropad, because its firmwares purpose is to make 3d modeling in Onshape easier. This is also why its called a CADPad, not Catpad (meow), CADPad. C A D, like CAD-design. 

### Features: 
  - custom 27 keys leyout
      - its kinda ergonomic? kinda.
  - Nice!Nano V2
      - ZMK firmware (hand written, yeeeeee)
      - better ZMK support, because Nice!Nano V2
      - build in BLE support
      - LiPo battery support
      - battery charger + support
  - USB Hub (SL2.1)
      - 1 USB-C upsream
      - 4 USB-C donwstreams
      - USB 2.0 fullspeed

---

## Why though?

This is a gift to [Chroma](https://github.com/Chroma165), my friend who likes to design 3d-models and print them with his 3d-printer. I though it would be nice to gift him a Macropad, my bad, its a CADPad, to make this process easier for him. It was also fun to design a PCB, that has a unique form. 

---

## How?

This CADPads development process was fairly easiy because of the knowledge from Auth75. It has 3 layers of keybinds, which u can cycle through with pressing the 2nd knob. The other knobs keypress is reserved for BLE pairing. 

---

## Renders

| PCB with Components |
| --- |
| <img alt="PCB Front" src="https://github.com/Lumethra/CADPad/blob/main/Images/PCB-Front.png" /> |
| <img alt="PCB Front" src="https://github.com/Lumethra/CADPad/blob/main/Images/PCB-Back.png" /> |

| PCB without Components |
| --- |
| <img alt="PCB Front" src="https://github.com/Lumethra/CADPad/blob/main/Images/PCB-Front-No-Components.png" /> |
| <img alt="PCB Front" src="https://github.com/Lumethra/CADPad/blob/main/Images/PCB-Back-No-Components.png" /> |

---

## PCB + Schematics

| PCB |
| --- |
| <img alt="CADPad PCB" src="https://github.com/Lumethra/CADPad/blob/main/Images/CADPad-PCB.png" /> |

| Schematics |
| --- |
| <img alt="CADPad Schematics" src="https://github.com/Lumethra/CADPad/blob/main/Images/CADPad-Schematics.png" /> |

---

<details>
  <summary>
    <h2>Zine</h2> 
  </summary>

| Zine |
| --- |
| <img alt="CADPad Zine" src="https://github.com/Lumethra/CADPad/blob/main/Images/zine.png" /> |

---
</details>

## BOM

| Part | Purpose | Cost | Quantity | Total Cost | LCSC/JLCPC Number | Link |
| --- | --- | --- | --- | --- | --- | --- |
| PCB | connect all of the compoenents | $14.10 | 1 (5) | $14.10 | ~ | [JLCPCB](https://jlcpcb.com/) |
| Nice!Nano V2 | handle the firmware | €24.63 | 1 | €24.63 | ~ | [42keebs](https://42keebs.eu/shop/parts/controllers/nice-nano-v2-wireless-controller/) | 
| Kailh Hotswap Sockets | holding the switches to the PCB without soldering | $0.1183 | 78 | ~$9 | C2803348 | [JLCPCB](https://jlcpcb.com/partdetail/C2803348) |
| Kailh (Cocoa) Switches | the switches you can press | $0 (comes with a Rainy75) | 78 | $0 (already owned) | ~ | ~ |
| Keycaps | goes onto the switches for better look and feel | $0 (3d printing ABS) | 78 | $0 (3d printed) | ~ | ~ |
| EC11 Rotary Encoder Switch | goes uii and click click | $2.22 | 1 | $2.22 | C370970 | [JLCPCB](https://jlcpcb.com/partdetail/C370970) / [Amazon](https://www.amazon.de/-/en/RUNCCI-YUN-Potentiometer-Automotive-Electronics-Multimedia/dp/B09SG3HF9N) |
| USB-C connector | connect to laptop | $0.0740 | 4 | $0.296 | C2765186 | [JLCPCB](https://jlcpcb.com/partdetail/C2765186) |
| SL2.1s | USB Hub core component | $0.2258 | 1 | $0.2258 | C2684433 | [JLCPCB](https://jlcpcb.com/partdetail/C2684433) |
| DW01A | battery protector | $0.0426 | 1 | $0.0426 | C351410 | [JLCPCB](https://jlcpcb.com/partdetail/C351410) |
| FS8205A | mosfet for protector | $0.0470 | 1 | $0.0470 | C2830320 | [JLCPCB](https://jlcpcb.com/partdetail/C2830320) |
| S2B-PH-SM4-TB | LiPo battery connector | $0.2014 | 1 | $0.2014 | C295747 | [JLCPCB](https://jlcpcb.com/partdetail/C295747) |
| Diodes | prevent voltage from backflowing and causing problems | $0.0117 | 82 | ~$0.9594 | C81598 | [JLCPCB](https://jlcpcb.com/partdetail/C81598) |
| Resistors | prevent things go boom | ~$0.0016 | 19 | ~$0.0304 | C23186, C21190, C22775 | [C23186](https://jlcpcb.com/partdetail/C23186) / [C21190](https://jlcpcb.com/partdetail/C21190) / [C22775](https://jlcpcb.com/partdetail/C22775) |
| Capacitors | smooth out the power | $0.0032 - $0.0110 | 14 | ~$0.0956 | C15849, C19666, C14663 | [C15849](https://jlcpcb.com/partdetail/C15849) / [C19666](https://jlcpcb.com/partdetail/C19666) / [C14663](https://jlcpcb.com/partdetail/C14663) |

> the prices can vary depending on the provider <br>
> you can find the JLCPCB parts on [LCSC](https://lcsc.com/) too (exept the PCB and the Pico)

--- 

## Contribute

Want to make anything better? Found any bugs? Anything always going booom?? Feel free to open a PR (pull request) and lets make the project better. ^_^
> the libraries are all imported with [easyeda2kicad](https://github.com/uPesy/easyeda2kicad.py) and [kiswitch](https://github.com/kiswitch/kiswitch)

---

## Thank you

A huge thank you too all these persons helping me making this project possible, thank you helping me sanity check, thank you for all these support. 
> Thank you, <3 u all ^_^
