# WOL

Wake on Lan

use mac and broadcast to send the magic packet.

broadcast : xxx.xxx.xxx.255

magic packet:FF FF FF FF FF FF + (MAC * 16)

-----------------------------------------------------------

1.Change the mac and broadcast in the source.
#windows
2.Change the setting in the network interface card.
 - open the wake on card
 - open the magic packet wake on card


* test ok
* next : read the File for multiple PC.
