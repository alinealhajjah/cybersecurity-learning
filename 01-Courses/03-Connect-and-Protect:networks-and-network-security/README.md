## Connect and Protect : Networks and Network Security


First of all , network is basically a collection of connected devices that communicate with each other  but ofc it is not as easy as it sounds because devices use uniques addresses , like IP and MAC to locate each other and insure communication. This course is really big but i will try to explain things as briefly as possible.

We have two types of networks , WAN- which covers a large geographical area , and LAN which covers a small geographical area like a home , office or school.

---

### Network architecture 

* Hubs: These devices broadcast information to every connected device on a network, similar to a radio tower.

* Switches: More intelligent than hubs, switches create specific connections between devices, sending data only to the intended recipient, which enhances security and network performance.


### Connecting Networks and the Internet

* Firewall : its a security device , like a first line of defense

* servers: they provide information and services for devices like computers, smart home devices, and smartphones on the network. The devices that connect to a server are called clients.

* Routers: they connect networks and direct traffic, based on the IP address of the destination network. Routers allow devices on different
networks to communicate with each other. In the TCP/IP model, routers are a part of the network layer. 
The IP address of the destination network is contained in the IP header. The router reads the IP header information and forwards the packet to the next router on the path to the destination. This continues until the packet reaches the destination network. Routers can also include a firewall feature that allows or blocks incoming traffic based on information in the transmission. This stops malicious traffic from entering the private network and
damaging the local area network.

* Modems: they usually connect your home or office with an internet service provider (ISP). ISPs provide internet connectivity via telephone lines, coaxial cables, or fiber optic cables. Modems receive transmissions or digital signals from the internet and convert them into a digital format
compatible with the physical connection provided by your ISP




<img width="949" height="361" alt="image" src="https://github.com/user-attachments/assets/4140bec1-023d-4cd7-87c3-df533b627a8c" />


### cloud computing 

on premise networks are company owned , which means all operations are kept in a physical location.
A cloud service provider (CSP) is a company that offers cloud computing services. These companies  own large data centers in locations around the globe that house millions of servers. Data centers provide technology services, such as storage, and compute at such a large scale that they can sell their services to other companies for a fee. Companies can pay for the storage and services they need and consume them through the CSP’s application programming interface (API) or web console.

CSPs provide three main categories of services:

* software as service (SaaS)
* infrastructure as service(LaaS)
* Platform as a service (PaaS)


<img width="797" height="330" alt="image" src="https://github.com/user-attachments/assets/1218734e-a1b6-4889-8bd1-1ee78e68712a" />


### what are the benefits of cloud computing ? 

* Reliability --> secure connections , servers always running , availability

* cost -->  CSPs have such large data centers, they are able to offer virtual devices and services at a fraction of the cost required for companies to install, patch, upgrade, and manage the components and software themselves.

* Scalability -->  companies only pay for what they need when they need it



### Internet protocol (IP)
A set of standards used for routing and addressing data packets as they travel between devices on a network 

- IP provides standards for routing and addressing data packets as they move across a network.
- Each private network device is assigned an IP address, which functions as its unique identifier



**now we got to the important stuff**


### TCP/IP Model 


 The TCP/IP model is a framework that helps understand how data is structured and sent over a network.
 
- It consists of four distinct layers:
  
 **the network access layer** --> This layer is responsible for creating data packets and transmitting them across the network, involving hardware devices, cables, and switches.
  
  **Internet Layer**: At this layer, IP addresses are assigned to data packets to specify sender and receiver locations, and it determines how networks connect.

**Transport Layer**: This layer manages the flow of traffic and includes protocols for controlling communication between devices, as well as error control to ensure smooth data flow.

 **Application Layer**: This final layer defines how data packets interact with receiving devices, handling functions like file transfers and email services


















