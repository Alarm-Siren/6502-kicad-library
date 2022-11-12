# 6502 KiCad Library
*Version 2.0.2*

Library of schematic components of a variety of Commodore, MOS Technologies and Wester Design Center chips for KiCad 6.

Currently included are:
- 6502 8-bit NMOS Microprocessor, 64K, DIP-40
- 6503 8-bit NMOS Microprocessor, 4K, DIP-28
- 6504 8-bit NMOS Microprocessor, 8K, DIP-28
- 6505 8-bit NMOS Microprocessor, 4K, DIP-28
- 6506 8-bit NMOS Microprocessor, 4K, DIP-28
- 6507 8-bit NMOS Microprocessor, 8K, DIP-28
- 6508 8-bit NMOS Microprocessor, 64K, 8-bit I/O Port, 256 Byte RAM, DIP-40
- 6509 8-bit NMOS Microprocessor, 16x64K, DIP-40
- 6510 8-bit NMOS Microprocessor, 64K, 6-bit I/O Port, DIP-40
- 6510-1 8-bit NMOS/HMOS Microprocessor, 64K, 8-bit I/O Port, 2ϕ Clock, DIP-40
- 6510-2 8-bit NMOS/HMOS Microprocessor, 64K, 8-bit I/O Port, DIP-40
- 6510T 8-bit NMOS/HMOS Microprocessor, 64K, 8-bit I/O Port, DIP-40
- 6512 8-bit NMOS Microprocessor, 64K, 2ϕ Clock, DIP-40
- 6513 8-bit NMOS Microprocessor, 4K, 2ϕ Clock, DIP-28
- 6514 8-bit NMOS Microprocessor, 8K, 2ϕ Clock, DIP-28
- 6515 8-bit NMOS Microprocessor, 4K, 2ϕ Clock, DIP-28
- 6520 NMOS Peripheral Interface Adapter (PIA), 20-pin I/O, DIP-40
- 6522 NMOS Versatile Interface Adapter (VIA), 20-pin I/O, 2 Timer/Counters, DIP-40
- 6523 NMOS Tri-Port Interface (TPI), 24-pin I/O, DIP-40
- 6525 NMOS Tri-Port Interface (TPI), 24-pin I/O, DIP-40
- 6526 NMOS Complex Interface Adapter (CIA), 20-pin I/O, 2 Timer/Counters, RTC, DIP-40
- 6529 NMOS Single Port Interface (SPI), 8-pin I/O, DIP-20
- 6532 NMOS Memory, I/O and Timer Array (RIOT), 16-pin I/O, 1 Timer/Counter, 128-byte SRAM, DIP-40
- 6545 NMOS CRT Controller (CRTC), DIP-40
- 6551 NMOS Asynchronous Communication Interface Adapter (ACIA), Serial UART, DIP-28
- 6581 NMOS Sound Interface Device (SID), 3-Voice Sound Synthesizer, DIP-28
- 6582 NMOS Sound Interface Device (SID), 3-Voice Sound Synthesizer, DIP-28
- 65CE02 8-bit CMOS Microprocessor, 64K, DIP-40
- 8500 8-bit HMOS Microprocessor, 64K, 6-bit I/O Port, DIP-40
- 8502 8-bit HMOS Microprocessor, 64K, 7-bit I/O Port, DIP-40
- 8580 HMOS Sound Interface Device (SID), 3-Voice Sound Synthesizer, DIP-28
- W65C02S_P 8-bit CMOS General Purpose Microprocessor, DIP-40
- W65C02S_PL 8-bit CMOS General Purpose Microprocessor, PLCC-44
- W65C02S_Q 8-bit CMOS General Purpose Microprocessor, LQFP-44
- W65C21N_P CMOS Peripheral Interface Adapter (PIA), 20-pin I/O, NMOS-Compatible, DIP-40
- W65C21N_PL CMOS Peripheral Interface Adapter (PIA), 20-pin I/O, NMOS-Compatible, PLCC-44
- W65C21S_P CMOS Peripheral Interface Adapter (PIA), 20-pin I/O, DIP-40
- W65C21S_PL CMOS Peripheral Interface Adapter (PIA), 20-pin I/O, PLCC-44
- W65C22N_P CMOS Versatile Interface Adapter (VIA), 20-pin I/O, 2 Timer/Counters, NMOS-Compatible, DIP-40
- W65C22N_PL CMOS Versatile Interface Adapter (VIA), 20-pin I/O, 2 Timer/Counters, NMOS-Compatible, PLCC-44
- W65C22S_P CMOS Versatile Interface Adapter (VIA), 20-pin I/O, 2 Timer/Counters, DIP-40
- W65C22S_PL CMOS Versatile Interface Adapter (VIA), 20-pin I/O, 2 Timer/Counters, PLCC-44
- W65C22S_Q CMOS Versatile Interface Adapter (VIA), 20-pin I/O, 2 Timer/Counters, LQFP-44
- W65C51N_P CMOS Asynchronous Communication Interface Adapter (ACIA), Serial UART, DIP-28
- W65C51N_PL CMOS Asynchronous Communication Interface Adapter (ACIA), Serial UART, PLCC-28
- W65C51N_Q CMOS Asynchronous Communication Interface Adapter (ACIA), Serial UART, LQFP-32
- W65C134S_PL 8-bit CMOS Microcontroller, PLCC-68
- W65C134S_Q 8-bit CMOS Microcontroller, LQFP-80
- W65C265S_PL 8/16-bit CMOS Microcontroller, PLCC-84
- W65C265S_Q 8/16-bit CMOS Microcontroller, QFP-100
- W65C816S_P 8/16-bit CMOS General Purpose Microprocessor, DIP-40
- W65C816S_PL 8/16-bit CMOS General Purpose Microprocessor, PLCC-44
- W65C816S_Q 8/16-bit CMOS General Purpose Microprocessor, LQFP-44

Planned for future inclusion:
- The VIC, VIC-II and VIC-IIe
- The TED

## Schematic Compatibility Between Similar Components

The schematic components in this library have been specifically laid out such that chips with similar function and purpose will have compatible/equivalent pins in the same position, and incompatible pins will not overlap. This means it should be easy to replace one similar component with another, with minimal or no re-wiring; it also means that such a replacement should not result in a signal being routed to an incompatible pin by accident.

For example, if you were creating a design with the 6502 part, but then decided to replace it with a 6512 part, the phase 0 and phase 2 pins are in the same location because they have compatible functionality, but the phase 1 pins are not because on the 6512 it is an input, whilst on the 6502 it is an output.

## Compatibility with KiCad 5

This library is in the new KiCad 6 "S-Expressions" format, and is not compatible with KiCad 5. If you need compatibility with KiCad 5, please use version 1.0.0 of this repository - but be aware that said version does not contain all features and is not being maintained.

## Comments, Requests, Bugs & Contributions
All are welcome.  
Please file an Issue or Pull Request at https://github.com/Alarm-Siren/6502-Kicad-library

## License
Copyright 2018-2022, Nicholas Parks Young. All Rights Reserved.  
This library is licensed under the GNU LGPL v2.1, which can be found in file LICENSE.txt.

## Donations

If you've found this library useful and you'd like to make a donation towards its continued upkeep, click the button below:

[![paypal](https://www.paypalobjects.com/en_GB/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=UX25HM4CZFFWW)

## Library Setup
To add this library to your KiCad Project, do the following steps:
1. Copy the source files "65xx.kicad_sym" to the root of your KiCad project's folder.
2. In Schematic Editor go to the "Preferences" -> "Manage Symbol Libraries..." menu option.
3. In the Symbol Libraries dialogue that appears, switch to the "Project Specific Libraries" tab.
4. Click "Add empty row to table" button (the button with a big cross in it, beneath the table).
5. In the new line of the table, set Library Path to "${KIPRJMOD}\65xx.kicad_sym" on Windows or "${KIPRJMOD}/65xx.kicad_sym" on Linux/Mac, and ensure Plugin Type is "KiCad".
6. You can leave the Options and Description fields blank. You should set Nickname to something descriptive - for example, "65xx library".
7. All done: you are now ready to use these schematic components in your project!