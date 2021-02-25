# OpenDrive-Programmer
A open hardware USB programmer for the OpenDrive flashcart

# What can it do?
- Read or write OpenDrive flashcarts Flash memory and FeRAM,
- Backup commercial cartridges
- Backup and restore commercial cartridges save games

# Why?
Created this from my old project with repros, as challenge and for personal use. Decided to share the project for other to use and learn. Hope it is useful to somebody!

# Why two boards?
This is just and option for those who are not so skilled with a soldering iron. The design contained in the Bluepill folders can use both a standart BluePill development module or be built as a standalone unit. When using a BluePill, not so many components are necessary and almost any SMD component is needed to be soldered (just the two 74LVC245). The design in the Standalone folder is the one that i've been using and its been tested, should be exactly equal to the BluePill one, it just don't have the solder points for the headers needed to connect the BluePill.

# How to use
Assemble the PCB, all the files needed for producing the PCB are available here. After assembling connect a STLINK to the STLINK port and write the firmware. After that it is ready to be connected to a PC, it will be shown as a serial port. Connect to it using the OpenDrive Editor software and happy playing.

# Bill of Materials

# Useful docs for developers and those looking to learn about

# Troubleshooting
Most of the problems I had were related to bad solder joints, check and recheck your solder joints, specially the STM32 joints, lots of instabilities that I had were caused by falty contacts with solder.
