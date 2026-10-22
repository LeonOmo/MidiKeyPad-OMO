# MidiKeyPad-OMO

## What is this project?

The MidiKeypad is a circut board designed to

## What does it do?

The Midi Keypad OMO is a version of the Midi Keypad but with a few changes. Build around the Waveshare ESP32-S3-Zero

- Microcontroller: Waveshare ESP32-S3-Zero
- Switches: For instrument choice (preset change) and maybe one button for on / off
- Slide Potentiometers: For volume controller
- Midi Controlls: Exposed copper for note input (7 Playable Notes)

## Why does it exist?

- Just for the love of the game?: My intentions behind making this was for the pure joy i get from designing / soldering / wiring 

## Bill of Materials

| Designator | Component | LCSC Number / Link | Amount | Total Price | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| U1 | ESP32-S3-Zero | https://www.aliexpress.com/ssr/300000512/BundleDealsDutyCovered | 1x | 5,17 € / 5,79 $ | The Brain |
| RV1-2 | Potentiometer Bourns PTA1543 Single Slide | https://de.aliexpress.com/item/1005007386348713.html| 2x | 6,10 € / 6,83 $ | Sliding Potentiometer for volume control |
| SW1-3 | Kailh Choc Low Profile Switch | https://de.aliexpress.com/item/1005011812200097.html | 3x | 7,61 € / 8,52 $ | For switching between presets |
| SW4 | EC11 Rotary Encoder | https://de.aliexpress.com/item/1005008716778661.html | 1x | 2,69 € / 3,01 $ | Rotary Encoder for |
| PCB | PCB | [JLCPCB](https://jlcpcb.com/) | 1x | 4,00 $ | The PCB |
| Total Price | | 28,15 $ | | | |
| Shipping | | JLPCB 6,04 $ | | | |
| Total price with shipping | 34,19 $ | | | | |

## Tools

- PCB Design: KiCAD
- Case Design: Onshape
- Firmware: Arduino IDE (C++)

## Schematic

The Schematics in KiCAD

<img width="904" height="439" alt="Screenshot 2026-10-21 184545" src="https://github.com/user-attachments/assets/54c9a4e8-eda9-42bc-9de1-598304f0bdce" />

## PCB

The PCB in KiCAD

<img width="406" height="375" alt="Screenshot 2026-10-20 174015" src="https://github.com/user-attachments/assets/3512e822-80a2-4864-92f7-6d4bd46ff25d" />
<img width="406" height="375" alt="Screenshot 2026-10-20 174000" src="https://github.com/user-attachments/assets/51a8be72-8ebf-4bdc-8968-6379e4fe2bd7" />

## Case

<img width="406" height="375" alt="Screenshot 2026-10-21 182320" src="https://github.com/user-attachments/assets/d155bfc1-f41d-4ef0-83b2-a8d0c4677ccb" />

<img width="406" height="375" alt="Screenshot 2026-10-21 182348" src="https://github.com/user-attachments/assets/4f7bcbdd-476a-45de-936f-799c287c5cd9" />

## Extra

Yes i know i should be more creative with projects like these but Kais version is just so amazing that i wanted to make a similar one. At this project, Im most proud of my PCB wiring as it is way cleaner than my lasts and you can just see where what is going where. 

## Bonus

Before i saw the Midi Keypad i wanted to make "MusicMaker!" which is probably a future project of mine. The MusicMaker! will be sort of the same but i will use a buzzer / noise output to make noise and also it will have batteries.

<img width="941" height="584" alt="image" src="https://github.com/user-attachments/assets/41da697e-cd06-4ea1-8e5d-e4d483fe5c1f" />
