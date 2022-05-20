Displayens datablad: www.bgmicro.com/pdf/acs1375.pdf

Kaffemetern terminerar _inte_ CAN.

Tutorial hur man flashar AVR Microcontrollers med Atmel/Microchip Studio: [Programming AVR Microcontrollers with Atmel Studio 7](https://unboxing-tomorrow.com/programming-atmel-microcontrollers-with-atmel-studio-7/)

Tutorial hur man flashar AVR med AVRDude: [AVR Tutorial](https://www.ladyada.net/learn/avr/avrdude.html)

Kretskortets dokumentation finns på AUML-wikin: [CoreCard](https://projekt.auml.se/homeautomation:hardware:avr:corecard) Just nu sitter sitter det en Atmega88 monterat på kortet.

Ännu finns det inget skrivet om kaffemetern på [ETAs Wiki](https://wiki.eta.chalmers.se/). Men det får gärna någon göra.

![Programerare](programerare.jpg)

När du programerar behöver du mata med extern spänning. Typ 5V. Jag rekommenderar att använda Microchip Studio. Installationerna på ETAs datorer kan dock vara opålitlig.

Fuses är viktiga!!! Längst ner på den [här sidan](https://projekt.auml.se/homeautomation:software:embedded:avr:config) finns det info hur du confar klockor. LFUSE=0xE2 ger dig en intern 8 MHz klocka. 