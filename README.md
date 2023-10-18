# Active-Directory-and-Virtualization-Infrastructure
This GitHub repository documents the setup and configuration of an Active Directory and virtualization-based home lab environment using VirtualBox. The project serves as a practical demonstration of essential IT skills, network management, and server administration.

# Overview

1. Lab Setup and Infrastructure:
- Environment: Created a home lab active directory environment using VirtualBox.
- Operating Systems: Installed Windows 10 and Windows Server 2019 from ISO images.

2. Domain Controller Configuration:
- Virtual Machine 1: Established a virtual machine as the primary domain controller.
- OS Installation: Successfully installed Windows Server 2019 on the domain controller VM.
- Networking: Configured IP addressing for the internal network, enabling private network connectivity for client machines.
- Routing: Set up routing to allow clients on the private network to access the internet through the domain controller.

3. Active Directory Setup:
- AD Installation: Installed and configured Active Directory on the domain controller.
- Domain Creation: Successfully created an active domain to manage user accounts and permissions.

4. DHCP Configuration:
- DHCP Server: Configured a DHCP server on the domain controller.
- Client Integration: Ensured Windows 10 client VMs could automatically obtain IP addresses from the DHCP server.

5. User Account Management:
- Automation: Wrote and executed a PowerShell script to generate and add a thousand users to the Active Directory for testing and management purposes.

6. Client VM Integration:
- Client VM Creation: Created a Windows 10 client VM, named 'client1,' and successfully joined it to the domain.
- User Login: Logged into the client machine using one of the domain accounts for practical testing and validation.

Key Skills: Demonstrated proficiency in virtualization, network setup, Windows Server administration, Active Directory management, DHCP configuration, PowerShell scripting, and domain client integration.
