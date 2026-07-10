==================================================
rgb Quickstart Guide
==================================================

Description:
  [Controls the 3-fan daisy-chained Arctic P12 Pro A-RGB]

Commands:
  List Devices: sudo openrgb --list-devices
  Set Color: sudo openrgb --device 1 --zone 1 --mode static --color [HEX] > /dev/null 2>&1
  Fix Array Size: sudo openrgb --device 1 --zone 1 --size 36
  Edit Autostart: vim ~/.bashrc
  Reload Profile: source ~/.bashrc
  Turn Off: sudo openrgb --device 1 --mode off > /dev/null 2>&1

==================================================
