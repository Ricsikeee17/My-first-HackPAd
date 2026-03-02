So this is my first ever project that gets a Github repository.

This project is a custom 6-key macropad featuring:
6 mechanical switches for macros
1 dedicated mode switch
Rotary encoder (with press function)
OLED display for mode/status feedback
USB HID keyboard emulation
Built using an Arduino Pro Micro (ATmega32U4), which supports native USB communication.
Features:
Multiple macro modes (Mode 1 / Mode 2 / etc.)

OLED display shows:
Current mode
Encoder status
Custom labels (optional)

Rotary encoder:
Volume control

Fully programmable macros

And I want to make it a Plug \& Play (USB HID device)
Hardware components:
Xiao RP2040
7x MX switches

3x SK6812 MINI LED
A rotary encoder
An OLED panel 128x32
7x Diodes (DO-35)
Custom made PCB

Here's a screenshot of the schematic:
<img width="1044" height="693" alt="Screenshot 2026-03-02 145127" src="https://github.com/user-attachments/assets/12f154e7-cd5b-46c6-8f07-4e2a6804664e" />

The PCB:
<img width="608" height="487" alt="Screenshot 2026-03-02 145405" src="https://github.com/user-attachments/assets/86396dcb-1965-4dfc-8ae3-afeb6035bfe1" />
<img width="699" height="547" alt="Screenshot 2026-03-02 145425" src="https://github.com/user-attachments/assets/affcb3f0-7d8d-4892-af56-bf425c01c10c" />


BOM:
7xMX-Style switches
7x1N4148 Diodes
3xSK6812 MINI-E LEDs
1xEC11 Rotary encoders
1xSeeed XIAO RP2040
1x0.91 inch OLED display
7xWhite blank DSA keycaps
4x M3x16mm screws
4x M3x5mx4mm heatset inserts

Inspired by Hackclub Blueprint

