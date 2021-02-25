# OpenDrive-Programmer
A open hardware USB programmer for the OpenDrive flashcart

# What can it do?
- Read or write OpenDrive flashcarts Flash memory and FeRAM,
- Backup commercial cartridges
- Backup and restore commercial cartridges save games

# Why?
Created this from my old project with repros, as challenge and for personal use. Decided to share the project for other to use and learn. Hope it is useful to somebody!

# How to use
Assemble the PCB, all the files needed for producing the PCB are available here. After assembling connect a STLINK to the STLINK port and write the firmware. After that it is ready to be connected to a PC, it will be shown as a serial port. Connect to it using the OpenDrive Editor software and happy playing.

# Useful docs for developers and those looking to learn about

# Troubleshooting
Most of the problems I had were related to bad solder joints, check and recheck your solder joints, specially the STM32 joints, lots of instabilities that I had were caused by falty contacts with solder.
