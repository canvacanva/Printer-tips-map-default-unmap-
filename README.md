# Printer-tips-map-default-unmap

### MAP
powershell.exe Remove-Printer -Name ""\\192.168....\BrotherQL-1100""

### UNMAP
powershell.exe Add-Printer -ConnectionName ""\\192.168....\BrotherQL-1100""

### SET DEFAULT
rundll32 printui.dll,PrintUIEntry /y /n "\\192.168....\BrotherQL-1100"



