# RetroLib: KiCad Symbol Library for 6502 and related retro microchips
*Version 3.0.0*

![Required KiCad Version](https://img.shields.io/badge/kicad-%3E%3D6.0-critical) ![License](https://img.shields.io/github/license/alarm-siren/6502-kicad-library) ![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/alarm-siren/6502-kicad-library) ![Symbols](https://img.shields.io/badge/symbols-69-informational) ![Downloads](https://img.shields.io/github/downloads/alarm-siren/6502-kicad-library/total)

This is a library of KiCad schematic symbols for a variety of Commodore, MOS Technology and Western Design Center retro microchips, including the eponymous MOS Technology 6502.

Currently included microchips:
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
- 6560-001 NMOS Video Interface Chip (VIC), 192x200 NTSC, 2MHz Clock Option, DIP-40
- 6560-101 NMOS Video Interface Chip (VIC), 192x200 NTSC, Light Pen Option, DIP-40
- 6560-201 NMOS Video Interface Chip (VIC), 192x200 NTSC, Vertical Sync Reset Option, DIP-40
- 6560-301 NMOS Video Interface Chip (VIC), 192x200 NTSC, Bus Available Option, DIP-40
- 6561-001 NMOS Video Interface Chip (VIC), 192x200 PAL, 2MHz Clock Option, DIP-40
- 6561-101 NMOS Video Interface Chip (VIC), 192x200 PAL, Light Pen Option, DIP-40
- 6561-201 NMOS Video Interface Chip (VIC), 192x200 PAL, Vertical Sync Reset Option, DIP-40
- 6561-301 NMOS Video Interface Chip (VIC), 192x200 PAL, Bus Available Option, DIP-40
- 6562-001 NMOS Video Interface Chip (VIC), 320x200 NTSC, 2MHz Clock Option, DIP-40
- 6562-101 NMOS Video Interface Chip (VIC), 320x200 NTSC, Light Pen Option, DIP-40
- 6562-201 NMOS Video Interface Chip (VIC), 320x200 NTSC, Vertical Sync Reset Option, DIP-40
- 6562-301 NMOS Video Interface Chip (VIC), 320x200 NTSC, Bus Available Option, DIP-40
- 6563-001 NMOS Video Interface Chip (VIC), 320x200 PAL, 2MHz Clock Option, DIP-40
- 6563-101 NMOS Video Interface Chip (VIC), 320x200 PAL, Light Pen Option, DIP-40
- 6563-201 NMOS Video Interface Chip (VIC), 320x200 PAL, Vertical Sync Reset Option, DIP-40
- 6563-301 NMOS Video Interface Chip (VIC), 320x200 PAL, Bus Available Option, DIP-40
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
- The VIC-II and VIC-IIe
- The TED

## KiCad Version Compatibility
This library requires at least KiCad 6 to function, and is tested on KiCad versions 6.0.8 and 7.0.2. Note that the installation procedure is different for KiCad 6 and 7; please see the [Library Installation](#library-installation) section below.

## Comments, Requests, Bugs & Contributions
All are welcome!
Please open an [Issue](https://github.com/Alarm-Siren/6502-Kicad-library/issues) or [Pull Request](https://github.com/Alarm-Siren/6502-Kicad-library/pulls), as appropriate.

## Library Installation
To install this library in your copy of KiCad, choose the correct section for your version of KiCad and follow the steps given. These instructions only cover automated installation using KiCad's built-in Package and Content Manager (PCM); manual installation is possible but not supported.

### KiCad 7

1. Download the `6502-kicad-library-3.0.0-pcm.zip` library file from the [Releases page](https://github.com/Alarm-Siren/6502-kicad-library/releases), and save it somewhere you'll be able to find it easily.
2. Open KiCad and open the Preferences window at "Preferences" -> "Preferences..."
3. Select the "Plugin and Content Manager" section in the left-hand pane.
4. Ensure that the "Automatically add installed libraries to the global lib table" option is ticked.
5. Ensuring that the "Library nickname prefix" is set to "PCM_" is recommended. **(Optional)**
6. Ensuring that the "Check for package updates on startup" option is ticked is recommended. **(Optional)**
7. Click "OK" to close the Preferences window.
8. Click the "Plugin and Content Manager" button.
9. Click the "Install from File..." button.
10. Navigate to, select and open the library file you downloaded earlier.
11. You should now find that this library is listed in the "Installed" tab.
12. Close the Plugin and Content Manager.
13. You may need to restart KiCad for the library installation to fully take effect. **(Optional)**
14. All done: you are now ready to use these schematic symbols in your projects!

### KiCad 6
**Recommendation:** If you can, you should upgrade to KiCad 7.

1. Download the `6502-kicad-library-3.0.0-pcm.zip` library file from the [Releases page](https://github.com/Alarm-Siren/6502-kicad-library/releases), and save it somewhere you'll be able to find it easily.
2. Open KiCad and click the "Plugin and Content Manager" button.
3. Click the "Install from File..." button.
4. Navigate to, select and open the library file you downloaded earlier.
5. You should now find that this library is listed in the "Installed" tab.
6. Close the Plugin and Content Manager.
7. Go to the "Preferences" -> "Manage Symbol Libraries..." menu option.
8. In the Symbol Libraries dialogue that appears, switch to the "Global Libraries" tab (if not already selected).
9. Click "Add empty row to table" button (the button with a big cross in it, beneath the table).
10. In the new line of the table, set the Nickname to "PCM_65xx-library", and ensure the Library Format is set to "KiCad".
11. In the same line of the table, set Library Path to "${KICAD6_3RD_PARTY}/symbols/com_github_alarm-siren_6502-kicad-library/65xx-library.kicad_sym".
12. Click "OK" to close the Symbol Libraries dialogue.
13. All done: you are now ready to use these schematic symbols in your projects!

## Donations

I really hope you've found this library useful. If you'd like to buy me a beer in thanks for the work I put into it, you can make a donation using the button below:

[![paypal](https://www.paypalobjects.com/en_GB/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=UX25HM4CZFFWW)

## License & Legal
Copyright 2018-2023, [Nicholas Parks Young](https://github.com/Alarm-Siren).

Except as otherwise noted, all content of this library is licensed under the 
[Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/), with the following additional exception:
> To the extent that the creation of electronic designs that use the Licensed Material can be considered to be Adapted Material, the Licensor waives Section 3 of the Public License with respect to these electronic designs and any generated files which incorporate data provided as part of the Licensed Material.

[![CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/)

## FAQ

No-one has asked any questions about this library yet. If they do so, this section will be updated.