# r8169
I was working on a project with the r8169 driver that required an eeprom.
The driver didn't have eeprom support so I added support for an eeprom.
This was enough to work for me but the ethtool_eeprom->magic field was 
left unused so if you need something more comprehensive, feel free to reach
out.
