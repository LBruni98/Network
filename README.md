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

|Layer No.|Type|Protocols|Description|
|---------|----|---------|-----------|
|4|Application|HTTP, FTP, SMTP, DNS, etc.|The application layer is responsible for providing network services to applications. High-level protocols are included within the application layer, such as Domain Naming System (DNS), Hypertext Transfer Protocol (HTTP), File Transfer Protocol (FTP), etc.|
|3|Transport|TCP, UDP|The Transport Layer maintains the end-to-end communications within the network. The communications between the hosts are handled within this layer and flow control, multiplexing and reliability are maintained as well by the layer. Two protocols are used within this layer; TCP, for providing error control and successful delivery of the data, and UDP, though only used for less extensive control features.|
|2|Internet|IP|The internet layer, or network layer, packs the data into data packets and routes it to the correct device on the destination network. These packets then form the IP, containing the source and destination address used to transmit the IPs across networks.|
|1|Link|Ethernet, Token Ring, Other Link-Layer Protocols|The lowest layer is known as the Network Access Layer, that combines the data link and physical layers from the OSI model. It provides a means for the data to be delivered to other devices on a network and defines how the network should transmit an IP. This layer has to understand the details of the underlying network before it can format the data being transmitted.|

### OSI Model
|Layer No.|Type|Protocols|Description|
|7|Application|HTTP, FTP, SMTP, DNS, etc.|The application layer in the OSI model is a means for applications to receive network services, basically communicating the services to them such as file transfers and e-mail. Numerous protocols are used within this layer, such as Hypertext Transfer Protocol for web based languages transferred across the network and mail services by the SMPP protocol for email services.|
|6|Presentation|ASCII, EBCDIC, TIFF, GIF, PICT, JPEG, MPEG, MIDI|The presentation layer is used for interpreting the data and transformed that the application layer can use it. Many file types are represented by the application and can be converted, encrypted, decrypted or compressed.|
|5|Session|---------|The session layer establishes connections between applications and can set up, coordinate and terminate the conversations that happens between them. The protocols used are Transmission Control Protocol (TCP) and User Datagram Protocol (UDP), commonly provided within most applications.|
|4|Transport|---------|This layer provides the transferal of data between hosts or end systems and is responsible for error recovery and flow control. TCP and USP protocols, used in the session layer, provide these services through the internet for most applications.|
|3|Network|---------|The network layer handles the addressing and routing of data, where it is sent in the correct direction, selecting the appropriate routes and forwarding the data to the transport layer. The protocols that map to the OSI network include the IP protocol from the TCP/IP model, both IPv4 and IPv6, as well as Interwork Packet Exchange (IPX).|
|2|Data Link|---------|The data link layer is responsible for encoding the data prior to the transmission and decoding the data back into the bits at the destination, mainly handling the data transfer out of a physical link. The layer divides itself into two sub-layers; Media Access Control, how the computer gains access to the data and the permission to transfer said data, and Logical Link Control, controlling the frame synchronization, flow control and error checking.|
|1|Physical|---------|The bottommost layer is the physical layer that conveys the bit stream across the network. This is done via electrical impulse, light or a radio signal. A variety of devices and mediums are covered, through cables, cards and other ports.|

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
