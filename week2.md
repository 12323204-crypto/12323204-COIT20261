**Task 1: Setting Static IP Addresses**

I created a simple network topology in GNS3 by adding four Linux hosts and one switch. This activity helped me understand how devices are placed before configuring the network.

![GNS project intro basic](./image/week2_1.png)

connected all the hosts to the switch using Ethernet links which helped me understand how a switch allows multiple devices to communicate on the same network.

![GNS project intro basic](./image/week2_2.png)

I edited the network configuration file and assigned a static IP address to Host 1. It helped me learn how to configure network settings in Linux.

![GNS project intro basic](./image/week2_3.png)

I used the ip a command to check the IP address of Host 1. The correct IP address was displayed, confirming that the configuration was successful.

![GNS project intro basic](./image/week2_4.png)

I configured the static IP address for Host 3 and restarted the network interface. After checking with the ip a command, I confirmed that the new IP address had been applied correctly.

![GNS project intro basic](./image/week2_6.png)

![GNS project intro basic](./image/week2_5.png)

I configured and verified the IP address of Host 4. This activity showed me the importance of checking the configuration after making changes to ensure the network is working properly.

![GNS project intro basic](./image/Setting-IP-12323204-host2.png)

This week's practical helped me learn how to build a network in GNS3, connect hosts through a switch, configure static IP addresses, and verify the settings using Linux commands. These activities improved my understanding of basic network configuration and increased my confidence in using GNS3 and Linux.



 **Task 2: Testing Network Connectivity and Delay with Ping**

 Ping Test (ping -c 3 10.1.1.2)
 
I tested the connection between two hosts using the ping command. The successful replies confirmed that both devices were connected and communicating correctly.

![Setting ip-12323204](./image/week2_ping1.png)

I sent multiple ping packets to check the stability of the network. The results showed no packet loss, which means the network connection was stable.

![Setting ip-12323204](./image/week2_ping2.png)

I tested the network using a larger packet size. The communication was successful, and I learned that the network can handle different packet sizes without errors.****

![Setting ip-12323204](./image/week2_ping3.png)

I performed a final ping test to verify the network configuration. The successful responses confirmed that the IP settings were correct and the network was working properly.

![Setting ip-12323204](./image/week2_ping4.png)

Overall, task helped me understand how to use the ping command to test network connectivity, measure response time, and verify that devices can communicate successfully. It also improved my confidence in troubleshooting basic network connections.
