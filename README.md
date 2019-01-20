# Secure-Packet-Transmission
## What is this
You can use this method to protect your join requset when you using OTAA in LoRaWan.  
In case of the root key has been stolen, LoRaWan will loss its security, with this method, it may help!  
But it will need you to modify your end node, gateway and your network server.
## Core idea
![Image text](https://github.com/GaoSirgoo/Secure-Packet-Transmission/blob/master/articiture.png)
## How does it work
Your LoRaWan project must follow the LoRaWan 1.1 Specification. You will need to rewrite the firmware for your end node,gateway and your network server.  
For end node you need to modify the method for preparing payload in our method and other parts do not need to be changed.Firmware for your gateway need to be modified the format requirements of json data. The firmware of network server only needs to rewrite the processing after receving the json data. 


