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
|The TCP/IP model has 4 layers.|The OSI model has 7 layers.|
|The model follows a horizontal approach.|The model follows a vertical approach.|
|TCP/IP depends on protocols.|OSI doesn't depend on protocols.|
|TCP/IP is more lenient in terms of boundaries.|The OSI model has strict boundaries.|
|TCP/IP only supports connectionless communication stemming from the network layer.|OSI can support both connectionless and connection-oriented communication in the network layer.|
|The model doesn’t clearly differentiate between services, interfaces and protocols.|There is a clear distinction between the services, interfaces and protocols.|
|TCP/IP doesn’t fit any protocol stack.|OSI has a problem with protocol filtering into a model.|
|No separate session and presentation layer. The characteristics are provided by the application and transport layer respectively.|Separate presentation and session layer.|

## Standards and Protocols
### IEEE Standards
#### IEEE 802.3
IEEE 802.3 is the standard for Ethernet. The standard specifies the physical media and the working characteristics of the Ethernet. The standard also specifies the media that supports the standard, which are coaxial of both 185 and 500 meters, optic fibre, twisted pair telephone and multi-channel coaxial with a maximum length of 3,600. As only the Ethernet signals are carried on the medium, the Ethernet is designated ‘BASE’, meaning Baseband Signalling and designated 10BASE as the standard refers to the transmission speed of 10 Mbps.

#### IEEE 802.7
IEEE 802.7 identifies recommended broadband LAN practices. What is specified with the standard is the design, installation and the test parameters for the broadband cable technologies within the network.

#### IEEE 802.8
IEEE 802.8 is a standard for fibre optic in a LAN that is used in token passing computer networks. It was devised by the Fiber Optic Technical Advisory Group and essentially gives the recommendation for configuration and testing of fibre optic Local and Metropolitan Area Networks.

#### IEEE 802.11
IEEE 802.11 is a set of standards defining communication in wireless LANs, mainly a set of guidelines for implementing Wi-Fi. The standard is made up of numerous amendments, these being .11a, .11b, .11g and .11n which state the different frequency bands used.

### Routed Protocols
Routed Protocols is a protocol where data is routed from one network to another. These protocols use an addressing system that can address a particular network and host. There are different types of routed protocols, but the common being the IP address. The reason for IP being a more valued type of routed protocol is because of the fact that the rest is vanishing due to different issues.

IPv4 has started running out of addresses due to the population of the world and the devices being manufactured, meaning that there is not enough IPv4 addresses. IPv6 is the newer solution where there is a considerable amount of addresses, with more than IPv4. Global Unicast is a routable address that can used in the internet, associated with a single node and can identify that node. The problem with this protocol is mainly unicast flood, where the data packet that is supposed to be sent off to a single destination is sent to all hosts as a broadcast packet, making this protocol a potential security risk.

Link local is a computer address that is only effective for communications within the link or the broadcast domain where the host is connected. They are not unique beyond a single link and routers can’t forward the packets that have a link-local address. A Unique Local Address, or ULA, is an address that is used in IPv6. They are not meant to have data routed outside of their province and not allocated at all by an address registry.

Extended Unique Identifier, also known as EUI, assigns itself a unique 64-Bit IPv6 interface identifier, eliminating the need to manually configure the IP or use DHCP in IPv4 addresses. The problem that arises from using this however, is that privacy loss would be potential concern, with the MAC address of the router being revealed.
Auto-configuration is a feature in the IPv6 protocol that allows devices to use the internet without requiring any DHCP support, making it good for applications to require a secure connection without the DHCP server. The problem is that it doesn’t get the configuration needed to be functional on the network, so it needs a DHCPv6 server to get the rest of the configuration.

### Services and Network Applications
#### FTP
File Transfer Protocol, or FTP, is an internet protocol for transmitting files between computers over TCP/IP. It relies on two communication channels between client and the server and here a client can upload, download, delete or edit files on a server. The use however, would need to log on to the FTP server, but some servers can be accessed without having to login.

#### HTTP
Hypertext Transfer Protocol, or HTTP, is the protocol used by the World Wide Web. This protocol defines the actions that Web servers or browsers should take in from the user’s commands and how messages are transmitted and formatted. HTTP is used to help send the user to the webpage and to provide the user with a visual representation of the webpage, handling with the display and format.

#### SMTP
Simple Mail Transfer Protocol, or SMTP, is a protocol used for sending off email messages between servers. A majority of email servers use this protocol to send messages from one to another, where it can be retrieved via a client.

#### POP3
POP, known as Post Office Protocol, is a protocol in which email clients receive email. The most recent version is POP3 in which the email is held for the user by the internet server and once the mail is downloaded, it can be deleted, though it can still be saved for a period of time.

#### SSL
Secure Sockets Layer, or SSL, is the standard in security technology for creating an encrypted link between the web server and browser. It ensures that more personal information is transmitted securely, such as credit card info and login credentials, which is why it is used by most shopping websites.

## The Impact of Networking Topology, Communication and Bandwidth
### Topologies
Logical Topologies are concepts, defining the architecture of the communication of the nodes in a network. The topology of a network can be dynamically maintained and reconfigured by routers and switches. The topology is mainly defining how the signals act on the network media or how data passes through the network to the devices.

Ethernet is based on a type of logical topology known as the bus topology, which is a common logical solution defines the physical topologies, laying out the logics of the data travelling to all devices from one device in a network.

The physical topology refers to the actual structure of a LAN, utilising various networking cables to connect the physical devices on the network. It allows for organization of the network, by physically laying it out. It takes a lot of planning by determining the cable to be used and how they it runs through the building.

Several types of physical topologies:

* The star physical topology is a physical network that has the nodes connected to a centralized point, which can be a hub or switch.
* A mesh network is much different, where the various parts can connect via multiple hops and can allow for rerouting on a different path if the current one is broken.
* A bus topology is a lenient network, with the nodes all in a straight line and are terminated on both ends.
* A ring network is where the nodes create a circular path, each device joined to two others and the data packets travel around these nodes until it reaches its destination.

The main difference of physical and logical topologies is that logical is a visual representation of the network, showcasing how it could work, whereas the physical topology is actually physical; joined together with cables and switches.

### Communication
Communication is the transmission of data from either a computer or a device to another over a computer network, where said network is considered a telecommunications network that allows for the transmission of data. Essentially most common processes when browsing the internet has data transmission happening between the user and the server, such as retrieving a file from the internet or sending off an email, so with internet use, data is being communicated between servers, routers and other clients each time. However, to use the internet, the user would have to connect to the internet. A device is used to connect to a network, being a modem or router, which communicates with the internet; requesting permission to have the user join, to which data is sent back enabling the connection.

Data is being communicated each time, but the data flow is also prone to attacks and malicious attempts to gain information from other users. Security measures such as firewalls within a network that can limit down the communications rate and to ensure that no malicious attacks can happen. With security measures, no malicious data can travel to unsuspecting users or end up within the network.

Within a network model, the communication of data happens within layers. The TCP/IP has an applications layer that allows for services to be requested from the user to the application, meaning that data is ready to be sent, but namely focuses in the transport and internet layer, where the transport handles the communication between the hosts and for successful delivery and the internet layer sends the data across to the correct host. These layers aid the communication of data successfully by monitoring the data transfer and communicating with the right host.

## Operating Principles
### Networking devices
#### Hubs
Hubs are a common connection point for devices within a network and can either be wireless or wired. Hubs serve as a central connection for network equipment, sending off information and data across each connection. It sends the data individually and not at the same time, meaning slower transmitting speed.

#### Routers
Routers are electronic devices that join multiple computer networks, by receiving, analysing and moving incoming packets to another network. It can also determine the best route for packets of data to travel on. The data that it sends off runs through a number of network point with other routers before it gets to it destination.

#### Switches
A switch is a device that can receive incoming data packets and redirects them to their destination within a LAN. It creates an electronic tunnel that only uses the traffic that is requested, so during the data transmission, no other traffic can enter and that allows for communication without collisions.

#### Multilayer Switch
A multilayer switch is a device that can operate better and on higher levels than a traditional switch, performing the same functions but at a faster rate. Higher level functions were added that can allow the multilayer switch to look in the packets of data to aid in forwarding said data.

#### Firewall
A firewall in networking terms, is a software that enforces a set of rules for what traffic can enter or leave a network. This software is placed in a network to filter the amount of traffic and prevent any malicious data from travelling to private networks via the internet.

#### HIDS
Also known as a Host-Based Intrusion Detection System, is system used for overseeing a computer system in order to detect an intrusion. It analyses the traffic between the computer on which it is installed and reports any malicious packets that are entering or exiting the network.

#### Repeaters
A repeater is a device within a network used for regeneration or replication of signals that are weakened from any electromagnetic interference. It can relay messages between subnetworks using different protocols and cables, as well as can extend the LAN beyond its limits. Hubs can also be used as repeaters by relaying messages to computers connected within the same network.

#### Bridges
A network bridge provides interconnection with other bridge networks that use the same protocol. They are mainly used in LANs because of their tendency to block up a large network because of their ability to transmit the data to all the nodes within the network should they not know the destination node’s address. It uses a database to determine where the data frame can pass, transmit or be discarded.

#### Access Point
An access point is a station that allows for the connection of wireless devices and wired networks to connect via a wireless standard. For instance, Wi-Fi or Bluetooth is used to connect to a tablet computer. It can provide connectivity to anyone in the network anywhere and remain connected to that network.

#### Content Filter
Content Filtering in a network uses a program to prevent and exclude any data that is considered spam or is deemed objectional. It’s mainly used for security purposes by preventing network users from connecting to malicious websites that have malware or used to commit fraud, by blocking the file uploads to the internet.

#### Load Balancer
A load balancer is software that can distribute incoming network traffic across ‘server pools’, which are backend servers. It maximizes speed and efficiency by routing the traffic requests across servers to ensure that none are overloaded. Once a new server is added, the balancer sends requests to it automatically.

#### Modem
A modem is a device used for transmission of data over a cable or telephone connection. The modem is so called because it modulates or demodulates analogue signal simultaneously to digital signal for a computer to recognize and vice versa for other devices.

#### Packet Shaper
Packet shaping or traffic shaping, regulates the data transfer to maintain a level of performance and quality. It delays the flow of packets that is considered as less important for more prioritized traffic, hence to allow for maintained performance within the network.

#### VPN Concentrator
A VPN concentrator is a network device that provides a secure connection and delivery of data between VPN nodes. It adds to the capabilities of a VPN, allowing for many people to access the VPN at the same time.

### Server types
#### Web
A web server delivers the users content or services over the internet. Once a request is sent to the web server, it fetches the relevant HTML page sending it to the web browser. Any computer can be used as a web server via server software and the internet as well as the services it provides such as software and commercial packages.

#### File
A file server is a computer that is responsible for the storage and management of data files so that computers on the network can access said files. This server allows the users to share information over the network without resorting to transfer them physically.

#### Database
A database server is either a hardware or software server used to run a database, mainly providing services related to access and retrieving files from the stored database. The access to the server can either be “front end” or “back end”, where the former can be running locally on a user’s machine or the latter, where its running in the server itself. Once the information in the database is retrieved, it is displayed to the user who requested it.

#### Combination
A combination server is a server that combines the functions of a web, file and database server to make a server that can fulfil all the functions of those servers. This server provides all the services offered but as a singular server.

#### Virtualisation
A virtualized server is a server that was at once physical, but broken up into small virtual servers assisted by software. These servers provide web hosting, file or database services but is masked as individual servers so it cuts down on hardware from a physical server.

#### Terminal Services
A terminal server is a device or server that provides terminals, usually PCs but can be other devices, with a port to a Local or Wide Area Network. With a terminal server, client systems don’t have to connect using a modem or network interface.

## Workstation Hardware
### Networking Software
Network software is a term for software that is used for designing and implementing modern networks. There are six networking software programs that can be used for creating networks:

#### Client Software
A client is a piece of software that works within local and wide area networks. The term basically describes software that functions like an interface between a client’s computer and the server so it technically is located within the client’s PC. Basically, it can be anything that provides services, such as a word processor or a web browser, that makes use of services provided by the server and also provides an interface for the user to interact with these services.

#### Server Software
Server software is a piece of software designed for use in a server, providing power of a use of high end functions. It is used to interact with the infrastructure of the server to ensure maximum performance within the server. The type of usage may vary and the server may be used as a web, application, database, cloud or file server. The primary focus is clear however, which is to use computer resources and capacity.

#### Client Operating System
A client operating system is a computer that doesn’t require networks or external components to properly function and mainly works within the computer. It helps the user perform functions within the computer whenever used, such as browsing the internet. Operating systems must function with a distinct type of hardware. An example of a client operating system is Microsoft Windows, a common operating that comes within a desktop or laptop.

#### Server Operating system
A server operating system is an operating system designed for use on servers, built to serve the requests of client computers in a network. This server is opposite to that of a client operating system but also does function the same way, but the difference is that it enables server roles such as web, mail, file, database, application and print server. The Microsoft Windows Server line-up is a prime example of server operating software and has capabilities required within a client-server architecture.

#### Firewall
A firewall is software that enforces a set of rules that affect the traffic flow from within a network. They are incorporated into a variety of network devices to filter the traffic coming in and out of a firewall, but the main benefit is the security aspect of firewalls as they can prevent any malicious packets of data to flow into the network, mainly a public network. Two types can be used; host-based, which can be installed onto a server and network-based, typically built into the cloud infrastructure.

#### Proxies
A proxy server is a software system that runs on a computer, acting as midway between an endpoint device and another server that the client requests a service from. The proxy exists in the same machine as a firewall server, so that the requests can be forwarded through the firewall. Once a proxy server receives a request for an internet resource, which can be a web page, it runs through a cache of past pages and returns it to the user once found, without having to forward the request to the internet.

### Comparison of network and Cabling
#### Network Comparison
A network card is a device used to connect a computer to a computer network, by exchanging the data with the network and using a suitable protocol to achieve connection. Wireless networks are networks that don’t rely on cables but rather radio waves and can connect via Wi-Fi hotspots to establish a connection. Mobile or a cellular network is network distributed through cells where each cell has a fixed transceiver or base station. From describing them, each network has unique features, mainly in how they need to work and it requirements.

A network card would be the only one of the networks described that requires a wired input to connect, requiring at least a connection port, such as coaxial or ethernet port, so in contrast with the other networks there is no form of wireless output for connecting to a network. In terms of the wireless networks, both use a wireless form, but a minor difference is that radio waves are used within the wireless network whereas mobile requires a dedicated control channel for transmitting digital information. Continuing with the mobile comparison, but in comparison to all three, mobile phones can only use the mobile network, as mobiles manipulate the frequencies for good connection to the network.

#### Cabling Used
Structured cabling is a system of cabling and hardware that provides a comprehensive communications infrastructure. It is mainly an organized approach to a cable network, where most elements of the network are done within the hardware, rather than using multiple cables. Network cables are hardware used for connecting one device to another and for transmitting information and data between computers, routers, switches and storage are networks. Network cables are mostly different between each other, mainly having different ports or cabling types. The common types of cabling are:
* Patch Cables are commonly ethernet cables used for linking a computer to a hub, switch or router, or even other devices to them. This type of cabling is used primarily for building home computer networks and those that need wired access when mobile, such as in hotels.
* Shielded Cables are ethernet cables but are composed of insulated conductors enclosed within a conductive layer, either being copper or aluminium.
* Twisted pair are copper wire used for connecting computers both home and business together. The copper wires are twisted around each other, so to prevent any crosstalk and electromagnetic induction between the wires.

### Permissions
Permissions are access details that are given by users or network administrators to define the rights to certain files on a network. An example of this would be a customer having access to a certain customer’s information that would otherwise be blocked by employees. There are two diverse types of permissions for sharing resources.

NTFS permissions are used for determining access to files and folders and are features commonly seen in Microsoft Windows. They allow for users to read, write, edit and/or delete files when given the opportunity. There are more flexible options than the shared permissions, meaning that users can be assigned specific functions, making it more organized and ensuring that higher level access isn’t given to a huge number of users.

Shared Permissions are permissions that are set for shared folders. These permissions determine the type of access that others can have to the folder across the network and apply to those who are joined within network, unlike NTFS permissions that aren’t other a network and only apply to certain users.

### Local Workstation Architecture
Workstation computers are specialized computers that can run tasks at a faster and more capable rate, as well as a networking workstation is a personal computer that is hooked up onto a local area network to share resources of one or more larger computers. These machines are connected to a LAN network. The reason for the workstation is good for CPU and RAM intensive programs is because of the fact of a faster processor and a considerable amount of RAM memory. Despite being a one user only, it can be remotely accessed by other users over the network. Different sorts of workstations have been designed to help with resources, such as a thin client, where the actions are performed on a server within the network.

#### System Bus
A system bus is a pathway that is made up of cables and connections, used for carrying data between the main memory and the computer microprocessor, essentially providing a communication pathway for the data between the major components of the computer system. It works by connecting CPU with the main memory and the level 2 cache. The internal bus carries the data within the motherboard, but some other buses branch out to provide a communication channel between the CPU and other components. The lines or pins of a bus are as followed:
* Address – The components pass memory to each other over this bus.
* Control – This is used to send signals for coordinating and managing the activities of motherboard components.
* Data – This is transferred between peripherals, memory and the processor.

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
![Complete](https://github.com/LBruni98/Networking/blob/master/Complete%20WAN%20Network.PNG)

This was the system that was built to match the requirements given. The system implemented with both the main and optional requirements that made up the system.

The Star Topology was used because of performance and that it gets to the destination without going through all the devices on the network; at most being 3 to 4 devices and around 2 to 3 links and with a switch acting as the main hub, it allows data to be sent to the destination without any additional copies of the same data. This topology is also simplistic, allowing me to easily connect different nodes to the system with the rest of the network being affected, hence the access point and printer being added while the network was active.

Copper Straight through was used as the standard for Ethernet connection between ports, so it was the most convenient in terms of choice. This was chosen over fibre optic because of the cost effectiveness of the connection, despite the efficiency of fibre, also with the network being used for a small network, the connections are effective. A Serial DTE connection was used for the connection of both routers to provide a WAN connection, where there is a serial port on said routers. The DTE connection was chosen over the DCE because of the device types used.

### Testing
The plan to test the network is to build the network and test it alongside development, to ensure quicker and orderly development as well as clear testing.

![Test](https://github.com/LBruni98/Networking/blob/master/Network%20Test.PNG)

### User Feedback
|Name|Feedback|
|----|--------|
|Mark|The networks work well and can connect within their own networks, even through other networks. However, there should be a level of security within the network.|
|Matthew|The design is ordered and easy to comprehend. The Star topology helps the data transmit fast and routes to the correct PC. The only improvement would be to configure a wireless access point to be able to effectively use the printer.|

#### Analysing Results
From the testing carried out prior, most of the network features worked perfectly and performed to the expected results. There was only one failure throughout the whole testing phase, which was done because of the lack of gateways and effective pinging.

The LAN networks worked correctly; the first was set up by focusing on the requirements and the second was copying the first network but changing names and the addresses to function. Both networks connected and worked flawlessly. The WAN connection through the routers was successful and allowed for the two Local networks to become a Wide Area Network. However, when ping the computers across both networks, unlike pinging locally, the connection timed out, so to ensure the computers connected across, the gateway IP was assigned to all PCs and Servers and a DNS server was set up. This allowed for computers across the WAN to communicate effectively and without interruption. The optional specifications were carried out and tested to completion where both passed. The printer connected successfully to the network and so did the access point, which can be used to connect to and function the printer.

### Evaluation
The network had met and performed to the standard of the requirements completely. Many factors have contributed towards the effectiveness of the system, such as the star topology used where the data can be sent seamlessly to the destination device and not to all the devices on the both the networks in the WAN. The connections used, these being the copper straight-through connections, worked despite the types used because of the small size of the network and the cost effectiveness of the connections. The network however, is susceptible to drawbacks and/or failures. For instance, the star topology does work well but when the network continues when a single node fails, the same can’t be said to when the centralized switch fails as the whole network will go down. Improvements that could be made to the network would be to consider other topologies that would’ve fit the requirements and personally, I would have considered using fibre connections for their reliability and longevity despite how expensive they can get. Factoring in on Feedback, there could have been improvements to the structure that would have helped with user convenience and security; the wireless access and printer have been added to both networks, but should’ve been considered beforehand and implementing a firewall to both LANs would have helped with safer data transferral and preventing incoming attacks.

Overall, the network had met the requirements needed and would does function well for a home or small business, but improvements to the structure of the network would prove for it to function more effectively, as well as ensuring security and better reliability.
