## tinyAVR Business Card

This is my entry for Hackaday 2024 Business Card Challenge Contest.

A business card with contact info and QR Code, plus a charlieplexed realtime clock powered by a CR2016 coin cell with extremely low battery power consumption, it is also a complete ATtiny3227 development board with all the pins break-out.

!["PCB name card side"](https://cdn.hackaday.io/images/1379581718161484463.png)
!["PCB component side"](https://cdn.hackaday.io/images/7447181718161448331.png)

### Feature Highlights

- Business with contact information and QRCode for website
- Credit card size of 85.5x54mm
- 3.2mm thickness including 1mm PCB
- It is a clock/watch with 12 Charlieplexing LEDs
- It is also a ATtiny3227 development board with all the pins (22-GPIO pins) break-out.
- Programmable with [megaTinyCore](https://github.com/SpenceKonde/megaTinyCore/tree/master/megaavr) as an Arduino or with bare metal with just VSCode and avrdude. 
- Powered by a CR2016 coin cell battery (98mAh)
- Designed for low-power, with design target of 1-2uA during sleep, and 2.5mA when time is showed.
- More than 3 years battery life based on viewing the time 24 times a day.
- Less than \$8.00 BOM (based on sourcing from DigiKey).

Further description can be found at https://hackaday.io/project/196294-business-card-clock-attiny3227-dev-board.

