# Networking
## Different Network Types and Standards
### Peer-based
Peer-based, Peer-to-peer or P2P networks mainly revolve around having two or more PCs connected and sharing the resources without utilising a separate server computer. Peer-to-peer networks allows each node to function as both the client and the server, unlike the client-server where the client makes the request and the server has to fulfil it.

Computers running P2P networks generally run the same protocols and software. Peer network devices generally sit close to one another, much like a row of computers in an office, but some can be spread worldwide via the internet. These networks can provide anonymized routing of network traffic, provide parallel computing environments across computers, allow distributed storage and other functions.
Different P2P applications can allow for control parameters, such as how many connections be allowed at one time, what systems can be connected to or avoided, what services can be offered and how many resources can be devoted to the network.

P2P networks are easy to understand and set up. Any computer can be used and a simple hub or switch can be used to connect it all together and because of this, there is no need for any special hardware or software; there is no need for any servers and each computer can be managed by the individual users. All computers can be maintained, meaning no need for any network manager and that there is less network traffic because of the fact that no one in the peered network needs to rely on a single server.

However, because of the way that Peer-to-peer works, there can be some drawbacks. Each computer fulfils more than one role, be it printing or file sharing and can increase the load. As the computers have to be maintained themselves, every user must ensure that antivirus and malware protection software are installed on each computer retrospectively, otherwise should a virus infect one machine, it will quickly be transferred across any other computer connected to this network.

### Client-server
Client network is a model that involves a client and a server, where the client requests a service from the server. The request that the client makes is to connect to a website over a local area network, to which a secure connection to the server. The connection is then terminated once the server has fulfilled the client’s request. Internet browsers are basically a client program that when clicked on a link to a web page, has actually requested a service from the server.

All resources and data are controlled by the server so that a program or an unauthorized client can’t damage the system, which better facilitates the task of uploading data and other such resources. Also noting that because of the centralization, backups and security is handled by the server, without the user having to do it themselves. Roles can be distributed to several computers and that servers can be replaced or fixed without any of the users being interrupted.

There can be some drawbacks to this network model; the server, for one, is expensive to purchase and install, along with requiring professional IT specialists to handle the maintenance and technical details of the network. Unlike the P2P server, congestion may be likely to happen if the server takes in too many requests, leading to overload of servers.

### Cloud
Cloud network or cloud based networking is a network model that uses a third party provider for accessing resources via Wide Area Networking. Cloud networking uses cloud computing, where centralized computing resources are shared amongst clients, but the network is also shared as well. It works the same way as standard networking but it’s component, devices and operations are all in the cloud.

The main benefit of cloud computing is that you can connect anywhere at any time regardless of device or place. A user can connect via a router that goes directly to the cloud server, so the user is not bound to a room. Cloud networking shares its characteristics with cloud computing, meaning that the benefits of cloud computing are also present with networking. For instance, you can access, edit and share documents at any time with people who are also connected to the network, allowing for good teamwork workflow without having to be in the same office.

### Cluster
A computer cluster consists of a single unit made up of multiple computers linked through a LAN and the joint computers act as if they were a single powerful machine. They have a node set to each cluster to perform the same task, so that they can perform that task at a faster rate with a higher joint processing speed.

The obvious benefit that Cluster networking offers is the processing speed, where the computers working together provide unified processing, producing the fastest amount overall. If a single component in the cluster fails, other computers can continue to provide the processing, backing up the failed component. The computer cluster is made up of different LAN topologies and these networks create a highly efficient and effective mainframe that prevents any bottlenecking.

### Centralized
Centralized networking is a form of networking where users connect to a central server and this server manages all of the computing resources, administration and user management. The server in turn delivers application logic, processing and the computer resources to the connected users. Each machine involved in this network generally are considered “thin clients”, computers with a display, basic input devices and a thin CPU with networking capabilities, so the main server provides the client with computing resources and other high-end faciliites.

In regards to the benefits of this type of networking, it helps in reducing cost as the main server mainly has the high-end output; it doesn’t emphasize on hardware and the client PCs, so any thin client can be used with it.

### Virtualised
A virtualized network is a method of combining the available network resources by splitting up the bandwidth into channels. Each channel is independent from the others and can be assigned to a server or device in real time. All users have access to the resources from the network from one computer.

A virtualized network is virtual; nothing physical is used with this type of networking and makes it more cost effective, with no need to utilize and maintain, physical switches, routers or servers. In case of a failure or a disaster, the virtualized network gets applications and systems up faster and even such outages can be prevented.

## Conceptual Models

![Comparison](https://github.com/LBruni98/Networking/blob/master/Model%20Comparison%20Table.jpg)

### TCP/IP Model
The Transmission Control Protocol/Internet Protocol model, shortened to TCP/IP is made up of many communication protocol used to connect network devices on the internet and is used as a communications protocol within a private network.

It uses the client/server model of communication where a client is provided a service from another computer in the same network. The model is made up of different protocols and divided into four layers:

* Application - The application layer is responsible for providing network services to applications. High-level protocols are included within the application layer, such as Domain Naming System (DNS), Hypertext Transfer Protocol (HTTP), File Transfer Protocol (FTP), etc.
* Transport - This layer maintains the end-to-end communications within the network. The communications between the hosts are handled within this layer and flow control, multiplexing and reliability are maintained as well by the layer. Two protocols are used within this layer; TCP, for providing error control and successful delivery of the data, and UDP, though only used for less extensive control features.
* Internet - The internet layer, or network layer, packs the data into data packets and routes it to the correct device on the destination network. These packets then form the IP, containing the source and destination address used to transmit the IPs across networks.
* Network Access - The lowest layer is known as the Network Access Layer, that combines the data link and physical layers from the OSI model. It provides a means for the data to be delivered to other devices on a network and defines how the network should transmit an IP. This layer has to understand the details of the underlying network before it can format the data being transmitted.

### OSI Model
* Application - The application layer in the OSI model is a means for applications to receive network services, basically communicating the services to them such as file transfers and e-mail. Numerous protocols are used within this layer, such as Hypertext Transfer Protocol for web based languages transferred across the network and mail services by the SMPP protocol for email services.
* Presentation - The presentation layer is used for interpreting the data and transformed that the application layer can use it. Many file types are represented by the application and can be converted, encrypted, decrypted or compressed.
* Session - The session layer establishes connections between applications and can set up, coordinate and terminate the conversations that happens between them. The protocols used are Transmission Control Protocol (TCP) and User Datagram Protocol (UDP), commonly provided within most applications.
* Transport - This layer provides the transferal of data between hosts or end systems and is responsible for error recovery and flow control. TCP and USP protocols, used in the session layer, provide these services through the internet for most applications.
* Network - The network layer handles the addressing and routing of data, where it is sent in the correct direction, selecting the appropriate routes and forwarding the data to the transport layer. The protocols that map to the OSI network include the IP protocol from the TCP/IP model, both IPv4 and IPv6, as well as Interwork Packet Exchange (IPX).
* Data Link - The data link layer is responsible for encoding the data prior to the transmission and decoding the data back into the bits at the destination, mainly handling the data transfer out of a physical link. The layer divides itself into two sub-layers; Media Access Control, how the computer gains access to the data and the permission to transfer said data, and Logical Link Control, controlling the frame synchronization, flow control and error checking.
* Physical - The bottommost layer is the physical layer that conveys the bit stream across the network. This is done via electrical impulse, light or a radio signal. A variety of devices and mediums are covered, through cables, cards and other ports.

### Differences between the two models
|TCP/IP|OSI|
|------|---|
## Standards and Protocols
### IEEE

### Issues of Routed Protocols

### Services and Network Applications

## The Impact of Networking Topology, Communication and Bandwidth
### Topologies
### Communication

## Operating Principles
### Networking devices
#### Hubs
#### Routers
#### Switches
#### Multilayer Switch
#### Firewall
#### HIDS
#### Repeaters
#### Bridges
#### Wireless Devices
#### Access Point
#### Content Filter
#### Load Balancer
#### Modem
#### Packet Shaper
#### VPN Concentrator
### Server types
#### Web
#### File
#### Database
#### Combination
#### Virtualisation 
#### Terminal Services

## Workstation Hardware
### Networking Software
### Comparison of network and Cabling
### Local Workstation Architecture
#### System Bus

## Network Design
### Architecture
The requirements for the network were for there to be two LANs; both LANs having 3 PCs, a server and a router. Pre-configured IP addresses were to be assigned to the PCs, servers and router for recognizing the devices. Further Requirements were to expand the network to be a Wide Area Network (WAN) where the PCs can communicate from the adjacent networks, as well as adding network printing and wireless access.

The design for the network is a WAN, consisting of two local networks, each with three PCs, a server and a router, along with two extras being a printer and access point. The LANs are designed within the Star topology, where the nodes are connected individually to a central point, this being the switch where all the traffic originates. The two LANs can communicate via a router as a gateway in both networks. An access point was included for connecting to wireless devices, hence the printer placed in both LANs.

![Layout](https://github.com/LBruni98/Networking/blob/master/WAN%20Architecture.jpg)

#### Set Configurations
##### Network 1 (Simpsons)
PC IPs:
* 192.168.1.100
* 192.168.1.101
* 192.168.1.102

Server IP:
* 192.168.1.10

Router IP:
* 192.168.1.1

##### Network 2 (Quahog)
PC IPs:
* 192.168.10.100
* 192.168.10.101
* 192.168.10.102

Server IP:
* 192.168.10.10

Router IP:
* 192.168.10.1

### Implemented System and Justification
![Completed System](https://github.com/LBruni98/Networking/blob/master/Complete%20Network.PNG)

This was the system that was built to match the requirements given. The system implemented with both the main and optional requirements that made up the system.

The Star Topology was used because of performance and that it gets to the destination without going through all the devices on the network; at most being 3 to 4 devices and around 2 to 3 links and with a switch acting as the main hub, it allows data to be sent to the destination without any additional copies of the same data. This topology is also simplistic, allowing me to easily connect different nodes to the system with the rest of the network being affected, hence the access point and printer being added while the network was active.

Copper Straight through was used as the standard for Ethernet connection between ports, so it was the most convenient in terms of choice. This was chosen over fibre optic because of the cost effectiveness of the connection, despite the efficiency of fibre, also with the network being used for a small network, the connections are effective. A Serial DTE connection was used for the connection of both routers to provide a WAN connection, where there is a serial port on said routers. The DTE connection was chosen over the DCE because of the device types used.

### Testing
The plan to test the network is to build the network and test it alongside development, to ensure quicker and orderly development as well as clear testing.

![Test](https://github.com/LBruni98/Networking/blob/master/Network%20Test.PNG)

### User Feedback
|Name|Feedback|
|----|--------|
|Mark|The networks work well and can connect within their own networks. There should be a DNS server that allows for the PCs to be recorded via names and to be able to ping between one another through both networks.|
|Matthew|The design is ordered and easy to comprehend. The Star topology helps the data transmit fast and routes to the correct PC. The only improvement would be to configure a wireless access point to be able to effectively use the printer.|

#### Analysing Results
From the testing carried out prior, most of the network features worked perfectly and performed to the expected results. There was only one failure throughout the whole testing phase, which was done because of the lack of gateways and effective pinging.

The LAN networks worked correctly; the first was set up by focusing on the requirements and the second was copying the first network but changing names and the addresses to function. Both networks connected and worked flawlessly. The WAN connection through the routers was successful and allowed for the two Local networks to become a Wide Area Network. However, when ping the computers across both networks, unlike pinging locally, the connection timed out, so to ensure the computers connected across, the gateway IP was assigned to all PCs and Servers and a DNS server was set up. This allowed for computers across the WAN to communicate effectively and without interruption. The optional specifications were carried out and tested to completion where both passed. The printer connected successfully to the network and so did the access point, which can be used to connect to and function the printer.

### Evaluation
