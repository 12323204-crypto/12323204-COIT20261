Week 05 Tutorial

This week, I learned how routing works between different networks. I configured IP addresses, checked routing tables, and tested connectivity using ping and traceroute. I also learned how OSPF dynamic routing allows routers to automatically discover routes and choose paths between networks. The practical activities helped me understand the difference between directly connected routes and dynamically learned routes.

**Task 1: View Routing Tables**

In this activity, I created a basic network topology containing Host1, Host2, Switch1, Router1 and Host3. Host1 and Host2 are connected through the switch, while the router connects them to another network containing Host3. This activity helped me understand how routers are used to connect devices that belong to different networks.

![View-Route](./image/week5_image1.png)

I configured Host1 with the static IP address 10.1.1.2 and subnet mask 255.255.255.0. I also configured 10.1.1.1 as the default gateway. This helped me understand that a host needs a correct IP address, subnet mask and gateway to communicate with devices outside its local network.

![Selecting an IPv4 network address](./image/week5_image2.png)

I configured Host2 with the static IP address 10.1.1.3 and subnet mask 255.255.255.0. The default gateway was set to 10.1.1.1. Because Host1 and Host2 are on the same 10.1.1.0/24 network, they can communicate locally through the switch.

![Record of the IP addresses and routing table](./image/week5_image3.png)

In this step, I configured the network interface of Router1. The router interface was assigned 10.1.1.1/24, which acts as the gateway for the hosts on this network. This activity helped me understand the important role of a router interface when forwarding packets between different networks.

![3.Record of the IP addresses and routing tables](./image/week5_image4.png)

 I configured Host3 with the static IP address 10.1.2.2, subnet mask 255.255.255.0, and default gateway 10.1.2.1. Host3 is located on a different network from Host1 and Host2. This showed me why a default gateway is required when communicating between different subnets.

![Record of an ip address](./image/week5_image5.png)

![Record of an ip address](./image/week5_image6.png)

![Record of an ip address](./image/week5_image7.png)

![Record of an ip address](./image/week5_image8.png)

![Record of an ip address](./image/week5_image9.png)

![Record of an ip address](./image/week5_image10..png)

![Record of an ip address](./image/week5_image11.png)

**Task 2: Dynamic Routing with OSPF**

![Record of an ip address](./image/week5task2_1.png)

Screenshot of show ip ospf route, show ip ospf route, show ip route

![Record of an ip address](./image/week5task2_2.png)

![Record of an ip address](./image/week5task2_3.png)

![Record of an ip address](./image/week5task2_4.png)

![Record of an ip address](./image/week5task2_5.png)

Traceroute

![Record of an ip address](./image/week5task2_6.png)

![Record of an ip address](./image/week5task2_7.png)

