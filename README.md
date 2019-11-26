# motoHUDsch
KiCad Schematic and PCB for STM32F103-based motorcycle digital instrument cluster with 2.8in ILI9341 LCD and X27.168 stepper motor for dial gauge indicator.

<b>Firmware - https://github.com/wiciu15/motoHUDini</b>

<b>Enclosure - no link for now :/ </b>

![3d back](https://i.imgur.com/eafEn4w.png)

![3d front](https://i.imgur.com/yldatLG.png)

![final render](https://i.imgur.com/zx7ixDC.png)

Rev1 has problems with thermals on 5V regulator, ADC accuracy and other brain farts like bad footprint or silkscreen marking

Rev2 comes with fixes and some new features like button switches. It is not perfect however :/

<b>Rev2 need some mods to work properly:</b>

<b>-U2 needs to be powered from a 5V rail or changed to a rail-to-rail dual opAmp in same package (LM2903 is not rail-to-rail unfortunately)</b>

<b>-C25 and C21 need a parallel resistor to discharge them (100k-200k ohm range)</b>

<b>-startup current is too high and destroys fuses immidately - I switched F1 fuse with a 1206 2,2ohm resistor </b>

If you don't have/like KiCAD there are schematic PDFs and gerber files.
