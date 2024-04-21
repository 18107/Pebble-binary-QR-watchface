Most of the code was copied from https://github.com/TrueJournals/pebble-qrwatch  
The QR library is from https://github.com/ksasq/QR-Image-embedded

The QR code contains the time and date (separated by a line break) and is displayed centered on the Pebble's display.

The bottom right corner of the QR code (4 wide, 3 high) also has the time in binary.  
The top row is hours, the middle row is 10-minutes, the bottom row is 1-minutes. The left square in the middle row is pm.  
The values of the squares are, left to right, 8,4,2,1. Add the values together to get the time.  
Black is on, white is off.
