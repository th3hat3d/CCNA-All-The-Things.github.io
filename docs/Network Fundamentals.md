The Network Fundamentals section of the CCNA 200-301 exam has 13 subsections to it,
and each topic is linked and explained below.

## 1.1: Explain the role and function of network components 

What is a computer network?
According to Wikipedia, it's a digital telecommunications network which allows nodes to share resources.
The CCNA will give you a solid understanding of what that means by the end of it.

+ Router: a network device on Layer 3 used to provide connectivity between LANs through routing.
    * They have fewer ports than switches do
    * Often used to send data to the WAN (often the Internet)
    * Example: Cisco ISR devices

+ Switch: a network device on Layer 2 which forwards traffic within a LAN.
    * Usually has more ports for end hosts to connect to (24+)
    * Does not provide connectivity between LANs or the Internet.
    * Example: Cisco Catalyst 2960 series switches
    * Layer 3 switches have Layer 3 routing capabilities, allowing them to serve multiple purposes in a network.

+ Firewall: controls traffic coming in and out of the network.
    * Can be placed inside or outside the network.
    * They need to be configured with rules to operate.
    * "Next generation" firewalls have modern and advanced filtering capabilities, such as web scanning.
    * Host-based firewalls are software applications with much of the same functionality as a network firewall.
    * Example: Cisco ASA devices

+ Access point: a device advertising a wireless network for clients.
    * Can operate independently or in combination with other APs to form a service set.
    * They advertise an SSID and can provide authentication services for clients trying to associate.

+ Controllers: WLCs and Cisco DNA Center
    * A WLC (Wireless LAN Controller) centralizes many functions of access points, such as configuration, authentication, RF management, and QoS management (using CAPWAP to communicate).
    * Cisco DNA Center is an SDN controller for Cisco SD-Access, centralizing the control plane using LISP.

+ PoE: A mechanism through which devices can recieve power through Ethernet cables, nothing more required.
    * The PSE (Power Sourcing Equipment) provides power to PDs (Powered Devices).
    * PoE sends low power signals to the PD, monitoring it and supplying the right amount of power.

+ Server: a device that provides functions or services for clients.

+ Client (also called an endpoint): a device that accesses a service made available by a server.

**A device can be both a server and a client at the same time!**
