<h1>Active Directory & Network Infrastructure Deployment for Centralized Management</h1>


<h2>Description</h2>
This project involved the end-to-end design and deployment of a robust Active Directory domain, establishing a centralized infrastructure for user authentication, resource management, and network services. By configuring a Windows Server Domain Controller with integrated DHCP and NAT/Routing, the project successfully provided automated IP addressing and secure internet access for isolated client machines, demonstrating comprehensive skills in Windows Server administration and network architecture.
<br />
<br />
<b>Key Project Objectives & Outcomes:</b>

- <b2> Centralized Identity Management: Successfully deployed Active Directory Domain Services (ADDS) to establish mydomain.com, enabling centralized user and computer management. </b2>
- <b2> Automated Network Services: Configured and managed DHCP for dynamic IP assignment to client machines, ensuring efficient network provisioning. </b2>
- <b2> Secure Internet Gateway: Implemented Network Address Translation (NAT) via Routing and Remote Access Service (RRAS) on the Domain Controller, providing internet access for clients on a segregated internal network. </b2>
- <b2> Scalable User Provisioning: Developed and executed a PowerShell script for bulk user creation, showcasing automation capabilities. </b2>
- <b2> Seamless Client Integration: Successfully joined Windows 10 clients to the domain and validated domain authentication and internet connectivity. </b2>
<br />



<h2>Architectural Highlights & Core Services</h2>
The project's foundation comprised a Windows Server Domain Controller (DC), meticulously configured with a dual-homed network setup: a NAT adapter for internet egress and an Internal Network adapter for isolated client communication. This DC served as the central hub for:
<br />
<br />

- <b2> Active Directory Domain Services (ADDS): Providing core domain services, including DNS resolution for mydomain.com. </b2>
  <p align="center">
  AD Users & Computers: <br/>
  <img src="https:" height="80%" width="80%" alt="AD Users & Computers"/>
  <br />
  </p>
- <b2> Dynamic Host Configuration Protocol (DHCP): Dynamically assigning IP addresses and network configurations to client machines on the internal segment. </b2>
  <p align="center">
  DHCP Management Console of configured scope and options: <br/>
  <img src="https:" height="80%" width="80%" alt="DHCP Management Console of configured scope and options"/>
  <br />
  </p>
- <b2> Routing and Remote Access Service (RRAS) / NAT: Enabling secure internet connectivity for client machines by routing their traffic through the DC's NAT service. </b2>
  <p align="center">
  RRAS Console showing the NAT configuration or enabled interfaces: <br/>
  <img src="https:" height="80%" width="80%" alt="RRAS Console showing the NAT configuration or enabled interfaces"/>
  <br />
  </p>
<br />



<h2>Client Integration & Validation</h2>
A Windows 10 client was seamlessly integrated, confirming the success of the deployed services:
<br />
<br />

- <b2> The client successfully obtained its IP address from the DC's DHCP server. </b2>
- <b2> Internet connectivity was verified from the client, routing through the DC. </b2>
- <b2> The client PC was successfully joined to mydomain.com, allowing for domain user logins. </b2>
  <p align="center">
  Client PC successfully logged in as a domain user: <br/>
  <img src="https:" height="80%" width="80%" alt="Client PC successfully logged in as a domain user"/>
  <br />
  </p>
<br />



<h2>Technologies & Tools Utilized</h2>

- <b2> Operating Systems: Windows Server (with Desktop Experience), Windows 10 </b2>
- <b2> Virtualization Platform: VirtualBox </b2>
- <b2> Core Services: Active Directory Domain Services (ADDS), DNS, DHCP, Routing and Remote Access Service (RRAS) / Network Address Translation (NAT) </b2>
- <b2> Scripting: PowerShell </b2>

<br />

For a detailed breakdown of the technical implementation, specific configurations, and in-depth analysis, please refer to the [Full Project Report (PDF/Docx/Link)] <br />
