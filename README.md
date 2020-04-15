# camsense-X1
unofficial reverse engineering of a Chinese LiDAR. 

Discussed this on my discord: https://discord.gg/zRGJcqa

## electrical connections
There are 3 pins needed to connect to the lidar: 5V, GND and TX. For this you can use the mounted connector(part number unknown) or solder some pinheader to the pcb.

A FTDI adapter is used to connect the lidar to a computer. The TX pin of the lidar needs to be connected to the RX pin of th FTDI adapter. The lidar can be powered using the 5V of the FTDI adapter.
