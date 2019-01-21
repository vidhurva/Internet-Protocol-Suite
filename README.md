# Internet-Protocol-Suite

In these projects, I explore the applications of Data Communications and Networks by using Ubuntu virtual machine. With virtual machine and Cisco Networking Academy, I am able to network engineer a prototype data communication system using the packettracer command in Ubuntu VM's terminal to perform switch configurations with PCs by executing wires and IP addresses. This resulted in successful connectivity between devices.

SOFTWARE USED
--
VirtualBox: VirtualBox allows me to open the Virtual Machine, run by Ubuntu OS. With VirtualBox, I have control over the amount of virtual memory required, and the speed in which my virtual machine runs by configuring the settings in the Motherboard. When dowloading virtual box, ensure that your download is compatible with the right Operating System!

Ubuntu: Operating system that you will open in the virtual machine. Note that this installation may not be required if you are not using a Mac OS. 

Packet Tracer: In order to obtain access to packet tracer, one must create a Cisco Networking Academy account. Furthermore, once Ubuntu is running from the virtual machine, users must install Packet Tracer through Ubuntu's terminal. Once packet tracer is open, users are able to run network engineering prototypes of connectivity between devices. 

Installation and Running Application:
--
With Virtual Box:
```
https://www.virtualbox.org/wiki/Downloads
```

With Ubuntu:
```
http://releases.ubuntu.com/16.04/
```

In Ubuntu Virtual Machine's terminal, enter these commands:
```
$ sudo apt-get update
$ sudo apt-get upgrade
$ cd Downloads
$ sudo tar xzvf Packet_Tracer_7.2_for_Linux_64_bit.tar.gz
$ ./install packettracer
```

To Open Packet Tracer:
```
$ packettracer
```

***NOTE: For picture diagrams with a step-by-step procedure, please view the attached PDF Files. 

PROJECT 1
----
In Project 1, I configure switch configurations, as well as IP addressing on switches and PCs. I then test network connectivity by implementing ping requests in the PC's command prompt. 

PROJECT 2
----
In Project 2, I implement a router to my earlier system design from PROJECT 1. I connect the switches to the router via the FastEthernet Interface. Additionally, I configured a default gateway in the switches and the PCs in order to allow these devices to communicate across multiple networks.

PROJECT 3
----
I focus on using VLANs for project 3. This allows me to reduce congestion in a LAN and organize PCs to particular access networks. 
