# NetPractice_42

### LEVEL 01 :

In order for my PC and my little brother's to communicate, the two interface need to have the same subnet mask and have IP addresses from the same rang (same goes for connecting my Mac and my little sister's computer):
- 104.96.23.1 - 104.96.23.254 /24 ;
- 221.191.0.1 - 221.191.255.254 /16.

![alt text](https://github.com/mboy29/NetPractice_42/blob/main/Levels/level01-2.png)

### LEVEL 02 :

Same goes for this level :
- 92.168.1.1 - 92.168.1.2 /30 ;
- 192.168.65.193 - 192.168.65.222 /27.

![alt text](https://github.com/mboy29/NetPractice_42/blob/main/Levels/level02-2.png)

### LEVEL 03 :

In order for interfaces from the same network switch to communicate, all interfaces need to have the same subnet mask and have tp belong to the same range of IP addresses : 104.198.212.129 - 104.198.212.254 /25.

![alt text](https://github.com/mboy29/NetPractice_42/blob/main/Levels/level03-2.png)

### LEVEL 04 :

Same goes here : 82.78.118.1 - 82.78.119.254 / 23.

![alt text](https://github.com/mboy29/NetPractice_42/blob/main/Levels/level04-2.png)

### LEVEL 05 :

As seen before, for two interfaces to communicate they need to share the same subnet mask and have IP addresses form the same range. However, for two interface to communicate outside of there respective network we have to use static route.

A static route is composed of one IP address with a subnet mask (where we come from / on the left) and another IP address (where we are going / one the right) also called a gateway. Where we come from can be composed of a default IP address and a default mask : 0.0.0.0/0).

![alt text](https://github.com/mboy29/NetPractice_42/blob/main/Levels/level05-2.png)

### LEVEL 06 :

A internet interfaces work the same way as a static route. However, the IP address and the subnet mask of where i come from can't be set to a default value. Else, see level03 in order to configure the interfaces connect to a network switch.

![alt text](https://github.com/mboy29/NetPractice_42/blob/main/Levels/level06-2.png)

### LEVEL 07 :

See level05 in order to configure the different gateways. 
Warning : When configuring two computers in order for them to communicate with each other, it is important to make sure no there is no intersection of networks

![alt text](https://github.com/mboy29/NetPractice_42/blob/main/Levels/level07-2.png)


### LEVEL 08 :

See level05 in order to configure the different static routes. 
Else, see level06 to set internet interface.

![alt text](https://github.com/mboy29/NetPractice_42/blob/main/Levels/level08-2.png)

### LEVEL 08 :

See level05 in order to configure the different static routes. 
Else, see level06 to set internet interface.

![alt text](https://github.com/mboy29/NetPractice_42/blob/main/Levels/level08-2.png)

### LEVEL 09 and 10 :

See all previous levels in order to configurate the networks of level09 and level10.

![alt text](https://github.com/mboy29/NetPractice_42/blob/main/Levels/level9-2.png)
![alt text](https://github.com/mboy29/NetPractice_42/blob/main/Levels/level10-2.png)
