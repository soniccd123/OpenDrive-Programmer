# OpenDrive-Programmer
A open hardware USB programmer for the OpenDrive flashcart

# Other projects of the same family
- OpenDrive Genesis: https://github.com/soniccd123/OpenDrive-Genesis
- OpenDrive Programmer firmware: https://github.com/soniccd123/OpenDrive-Programmer-firmware
- OpenDrive Editor: https://github.com/soniccd123/OpenDrive-Editor

# What can it do?
- Read or write OpenDrive flashcarts Flash memory and FeRAM,
- Backup commercial cartridges
- Backup and restore commercial cartridges save games

# Why?
Created this from my old project with repros, as challenge and for personal use. Decided to share the project for other to use and learn. Hope it is useful to somebody!

# Why two boards?
This is just and option for those who are not so skilled with a soldering iron. The design contained in the Bluepill folders can use both a standart BluePill development module or be built as a standalone unit. When using a BluePill, not so many components are necessary and almost any SMD component is needed to be soldered (just the two 74LVC245). The design in the Standalone folder is the one that i've been using and its been tested, should be exactly equal to the BluePill one, it just don't have the solder points for the headers needed to connect the BluePill.

# How to use
Assemble the PCB, all the files needed for producing the PCB and Bill of Materials are available here. After assembling connect a STLINK to the STLINK port and write the firmware (available here: https://github.com/soniccd123/OpenDrive-Programmer-firmware). After that it is ready to be connected to a PC, it will be shown as a serial port. Connect to it using the OpenDrive Editor software and happy playing.

# Documentation
- Programmer Technical documentation, a constant work, sugestions are welcome:https://docs.google.com/document/d/e/2PACX-1vRtMwSrP43Q_9yeqR024jhnHt7tN-bjPW5AL-o--7ggXnXnSzmwVzF4QqODWmXAdS4KnoAx6XXx5pVw/pub
- MX29L3211 Datasheet: http://www.wolfgangrobel.de/electronics/datasheets/eprom/MX29L3211.pdf
- FM1808 Datasheet: https://datasheet.octopart.com/FM1808-70-PG-Ramtron-datasheet-8328945.pdf
- 74LVC8T245 Datasheet: https://assets.nexperia.com/documents/data-sheet/74LVC_LVCH8T245.pdf

# Troubleshooting
Most of the problems I had were related to bad solder joints, check and recheck your solder joints, specially the STM32 joints, lots of instabilities that I had were caused by falty contacts with solder.

# Disclaimer
I'm not a professional hardware engineer, while this programmer was designed to be the safest possible to your flashcart, I'm not responsible for any damages done if used or built wrong. Also, revise the design always before building the PCB, I'm a amateur human and errors may have been commited. It you spot anything, hit me with a message and I will happily fix that. Also, any sugestions are welcome!
