# cisco-pt-dhcp-dns-http-ftp-tftp
Configured DHCP, DNS, HTTP, FTP, and TFTP in Cisco Packet Tracer

**Description**
This project demonstrates the implementation of a client-server architecture in a networked environment. It includes configurations for DNS (Domain Name System), DHCP (Dynamic Host Configuration Protocol), FTPS (File Transfer Protocol Secure), and HTTPS (Hypertext Transfer Protocol Secure) servers, showcasing how these components fit into the client-server model.


**Components and Functionality**

DNS (Domain Name System):
DNS servers resolve domain names to IP addresses for clients.
Clients request DNS resolution for domain names, and DNS servers provide IP addresses in response.

DHCP (Dynamic Host Configuration Protocol):
DHCP servers dynamically assign IP addresses and network configuration parameters to clients.
Clients request network settings from DHCP servers when joining the network.

FTPS (File Transfer Protocol Secure):
FTPS servers facilitate secure file transfer between clients and servers.
FTPS servers allow clients to upload and download files securely.

HTTPS (Hypertext Transfer Protocol Secure):
HTTPS servers enable secure communication between web clients and servers.
HTTPS servers respond to client requests by providing encrypted web content.


**Network Topology**

Router:
Serves as the central point of connectivity in the network.
Connects two switches and performs routing functions.

Switches:
Act as network hubs within their respective subnets.
Manage local Ethernet traffic and ensure data delivery within the same subnet.

DHCP Servers:
Dynamically assign IP addresses and network settings to connected devices.
Respond to DHCP requests from devices within their respective subnets.

DNS Server:
Resolves domain names to IP addresses for clients.
Responds to DNS requests from devices within the subnet.

FTP Server and Web Server (e.g., google.com):
FTP server allows secure file transfers within the subnet.
Web server provides web content accessible via HTTP or HTTPS requests.

PCs:
End-user devices that initiate various network activities.
Connected to switches and interact with servers for DNS resolution, DHCP configuration, file transfer, and web browsing.

**Summary**
This project showcases a comprehensive client-server architecture setup, including DNS, DHCP, FTPS, and HTTPS servers, within a networked environment. Through configurations and network topology, it demonstrates how clients and servers collaborate to provide and consume network services and resources effectively.
