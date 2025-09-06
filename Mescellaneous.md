# General Information about Networking

Networking in the field of technology simply means a connection/communication(s) between two or more devices, which allows them to share information among each other.  
We can compare this analogy to us human beings, in order for us to share information to each other firstly we need to know each other(connect) then start to communicate which makes sharing information possible.


## Network Components

- **End Device/End System**: This is a device that can receive or send a message. (Computer, cellphone, server).
- **Client**: This is a computer that request information from the server. E.g., requesting to access your emails on google mail server (gmail).
- **Server**: A server is an end device (computer) that is used to provide information requested by other end devices on a network. E.g., Web server, When you (client) access your facebook page you're basically requesting the facebook server for your page, and that server will do its job by providing it to you.
- **Intermediary Devices**: devices that interconnects end devices. These devices (*router, switch, wireless router, firewall*) are able to manage the data that flows through them.    


## PAN, LAN, MAN, WAN, Internet (Explanation)

- **PAN (Personal Area Network)**: This can be a connection personal devices that are connected to each other (within few meters), allowing them to share information with each other. E.g., Your cellphone connected to your headphones/(other cellphone) via bluetooth. 

- **LAN (Local Area Network)**: The network connection covers a small geographic area i.e office, home or small business.  
LAN allow devices (i.e printers, files, email servers) to share resources within the same location.  
It is commonly used in SOHO (Small Office/Home Office) setups, where only a few computers are connected.

- **MAN (Metropolitan Area Network)**: The MAN network focuses on connecting multiple LANs on a specific metropolitan area such as city, or large campus.  
High speed cables i.e., Optic fibre can be used to connect different building on that area. 

- **WAN (Wide Area Network)**: This network connects multiple MANs, typically spanning over a large geographic area.  
WANs are commonly used by companies with offices in different cities or countries. Employees can use VPNs to securely access company resources in remote locations.

- **The Internet**: This is a collection of interconnected LANs and WANs.  
Think of a the internet as a beautiful city where anyone can go to view it, go inside store and buy things they want, look at the buildings.  
It just a giant public network that allows end devices to connect and share resources.


## Network Architecture
Every company or organisation has a network architecture/set-up that defines how data moves across its network. [Naka](https://medium.com/@nakah_/recommended-design-for-a-secure-network-architecture-15612e17ece4)'s article demonstrates how a simple network architecture would look like and how different technologies such as end devices and intermediary devices would be utilised.  
In order for the organisation's architecture to meet user expectations, it must focus on these 4 basic characteristics:  
- **Fault Tolerance**: Reduces the impact of a failure in a network, meaning they implement ways to limit the number of affected by the failure.
- **Scalability**: The existing network must be able to expand quickly and accommodate/support new devices without impacting the performance of the devices that are already in the network.
- **Quality of Service (QoS)**: Ensures that there is reliable delivery of  of content for all users. QoS allows other traffics to be prioritised over others for the sake of quality of content. E.g., Voice Call may be prioritised over a web request to maintain the quality of the call.
- **Network Security**: Protects both the network infrastructure and the data transmitted across it. This includes physical security, access control, and encryption of data. Effective security should align with the CIA Triad:
    - **Confidentiality**: Only the intended user can read the data.
    - **Integrity**: Ensuring that the data is accurate and has not been altered with during a transmission.
    - **Availability**: Ensuring resources can be accessed whenever they are needed by authorised users.


# Adversary’s Perspective
