# NetPractice_42

This project will help us discover networking through practical cases. We will have to configure small networks thoughout 10 exercises of 10 different levels of difficulty.

Use :
- https://www.adminsub.net/ipv4-subnet-calculator/192.168.0.1/255.255.255.0 ;
- https://fr.wikipedia.org/wiki/Classe_d%27adresse_IP ;
- https://fr.wikipedia.org/wiki/Sous-r%C3%A9seau ;

### LEVEL 01 :

My PC and my little brother's computer need to have the same subnet mask and IP address range before they can communicate (the same applies for my Mac and my sister's computer):
- 104.96.23.1 - 104.96.23.254 /24 ;
- 221.191.0.1 - 221.191.255.254 /16.


![alt text](https://github.com/mboy29/NetPractice_42/blob/main/Levels/level01-2.png)

### LEVEL 02 :

The same applies to this level :
- 92.168.1.1 - 92.168.1.2 /30 ;
- 192.168.65.193 - 192.168.65.222 /27.

![alt text](https://github.com/mboy29/NetPractice_42/blob/main/Levels/level02-2.png)

### LEVEL 03 :

A network switch's interfaces must share the same subnet mask and IP addresses in order to communicate: 104.198.212.129 - 104.198.212.254 /25.104.198.212.129 - 104.198.212.254 /25.

![alt text](https://github.com/mboy29/NetPractice_42/blob/main/Levels/level03-2.png)

### LEVEL 04 :

The same applies here : 82.78.118.1 - 82.78.119.254 / 23.

![alt text](https://github.com/mboy29/NetPractice_42/blob/main/Levels/level04-2.png)

### LEVEL 05 :

It has been seen before that for two interfaces to communicate, they need to have the same subnet mask and IP addresses in the same range. However, static routes are needed for two interfaces to communicate outside their respective networks.

Static routes consist of one IP address with a subnet mask (where we come from/on the left) and another IP address (where we are going/on the right), also called a gateway. IP address and default mask for where we are can be represented as 0.0.0.0/0 (which is equivalent to any IP address and any subnet mask).

![alt text](https://github.com/mboy29/NetPractice_42/blob/main/Levels/level05-2.png)

### LEVEL 06 :

Internet interfaces work the same way as static routes. There is however no way to set my IP address and subnet mask to defaults. Otherwise, see level03 to configure the network interfaces.

![alt text](https://github.com/mboy29/NetPractice_42/blob/main/Levels/level06-2.png)

### LEVEL 07 :

To configure the different gateways, see level05.
In order for two computers to communicate with each other, it is important to make sure that their networks do not intersect.

![alt text](https://github.com/mboy29/NetPractice_42/blob/main/Levels/level07-2.png)


### LEVEL 08 :

In order to configure the different static routes, see level05.
Else, to set an internet interface see level06.

![alt text](https://github.com/mboy29/NetPractice_42/blob/main/Levels/level08-2.png)

### LEVEL 09 and 10 :

In order to configure the networks of level09 and level10, see all previous levels.

![alt text](https://github.com/mboy29/NetPractice_42/blob/main/Levels/level09-2.png)
![alt text](https://github.com/mboy29/NetPractice_42/blob/main/Levels/level10-2.png)
