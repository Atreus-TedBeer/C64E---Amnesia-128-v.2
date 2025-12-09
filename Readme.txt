# Commodore 64 Prototyping Cartridge

"Amnesia 128 v.2" for C64 designed in "Express PCB" v7.0.2.

[ not produced, untested ]

 "Amnesia 128" card is a RAM Expansion designed for C64E (short) motherboard. It's a +60KB designed in 90's by Mr.Fiz from Samar group. I only designed small board which comes into place of 8500 CPU and 4464 DRAMs. Also in the same package I'd added "VIC CS" board, because I need VIC CS Signal and soldering cables to VIC Chip and VIC Socket doesn't look nice.
 It's simpler version of my previous design with the same name. It was designed at the time when I was still in "C&A Fan" Group. I showed drawings and photos to group members and couple of months later I saw in last number of "C&A Fan" or first "K&A+" a PCB for +60KB done in very similar manner to my design. Now after couple of years I redone my project and divided it into smaller pieces.
 I'd designed 3 small PCB's which fits into empty space on C64C "Short Board". This allows me to solder them directly to mainboard without worrying about interfering with components on it.
 Those boards are:
 - Amnesia 128 (+60KB with CPU Signals Connector for Bus Extension)
 - VIC CS (small board with connector for VIC CS Signal)
 - CIA Splitter (CIA Address Decoder with Address Connector for Bus Extension)
 Added connectors allows me to add another Extension Card, which can be accessed from CIA#2 area addresses. This lets me add f.e. another CIA and use it as parallel port, RS232 or I can add serial card based on R65C51P4 (GLINK232) on those addresses, and not in Expansion Port blocking some cartridge. Also there is possibillity of adding Speech Synthesizer, Adlib or Real Time Clock under those addresses.
 Possibillities are limited only by our imagination and programming knowledge ;)

Why "Express PCB"? You may ask. I found it easy for me to add my own components to design and was easy to learn. It has limitations of its own but I found it more challenging when designing something ;)

If You like my work, you can email me with converted files to Gerber, or donate me on Paypal: tedbeer@o2.pl

Atreus