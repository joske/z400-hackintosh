# HP Z400 workstation OPENCORE bootloader files

Hackintosh with the following hardware:

- HP z400 motherboard
- intel Xeon X5687
- 20 GB RAM
- AMD RX460 GPU [1002:67ef]
- Kingston 240 GB SATA SSD
- ICH10 audio [8086:3a3e]
- BCM5764M Gigabit ethernet [14e4:1684]

## EFI settings

- MacPro5,1 SMBIOS

## Status

### Works

- boots to macOS mojave with opencore 0.9.7
- metal graphics with native AMD gpu driver (but graphical glitches appear near the top)
- network card works with native driver

### No Worky

- reboot gets stuck, shutdown/sleep work
