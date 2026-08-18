**Week 03 Tutorial**

**Task 1: Simple Application Communications with Netcat**

In this activity, I created a simple network topology with four hosts connected to one switch. This helped me understand how multiple devices on the same local network can communicate through a switch. I also learned how the interfaces of each host are connected to different switch ports.

![GNS project intro basic](./image/week3_1.png)

I used Netcat (nc) to establish communication between two hosts. One host was configured to listen on port 12345, while another host connected to it using its IP address and port number. I successfully sent text between the hosts, which helped me understand basic client-server communication using TCP.

![GNS project intro basic](./image/week3_2.png)

In this step, I used FileZilla to access the GNS3 server and locate the packet capture file. I could see the .pcap file created during the network activity. This helped me understand how captured network traffic can be saved and transferred for further analysis.

![GNS project intro basic](./image/week3_2.1.png)

I connected to the GNS3 server using FileZilla and browsed the remote server directories. This activity helped me understand how files stored on a remote system can be accessed using a secure file transfer connection.


**Task 2: Capturing Packets**

n this step, I configured FileZilla to connect to the GNS3 server using SFTP (SSH File Transfer Protocol). I entered the server address and login details to establish the connection. This helped me understand how SFTP provides a secure method for transferring files between computers.

![GNS project intro basic](./image/week3_3.png)

![GNS project intro basic](./image/week3_4.png)

![GNS project intro basic](./image/week3_5.png)

I used the ping command to test connectivity with the destination IP address 10.1.0.2. All three packets were successfully received with 0% packet loss, confirming that the network connection was working correctly. This helped me understand how ICMP ping can be used as a simple troubleshooting tool to check whether another host is reachable.

![GNS project intro basic](./image/week3_6.png)

In this step, I started a packet capture on the Ethernet link and saved the traffic as a .pcap file. Capturing the packets allowed me to record the network communication for later analysis. This activity helped me understand how packet capture can be used to investigate protocols such as ICMP and TCP/Netcat traffic and troubleshoot network communication.

![GNS project intro basic](./image/week3_7.png)

This week's practical activities helped me understand basic network communication and packet capturing. I learned how to use Netcat for communication between hosts, ping for testing connectivity, FileZilla/SFTP for transferring capture files, and packet capture for recording network traffic. These activities gave me practical experience with how data is transmitted, captured and analysed in a network environment.


