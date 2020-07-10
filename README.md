# Computer Network Projects

<h2>Project 1 - <a href="https://github.com/Nirali4/Networking_Projects/tree/master/IPSec-VPN">IPsec VPN</a></h2>
Created an IPSec based Virtual Private Network (VPN) for a company to connect with its partner's network securely. The data transmitted is authenticated and encrypted over the Internet so Confidentiality, Integrity, and Availability can be achieved.

<h4>Configuration includes:</h4>
<ul>
  <li>Type of VPN: IPsec tunnel
  <li>Tunnel policy: Internet Security Association and Key Management Protocol (ISAKMP-IKEv2) 
  <li>Failover plan: EtherChannel and Port-Channel
  <li>Packet filter: Extended Access-List 
  <li>IP addressing scheme: Internet Protocol Version 4 (IPv4)
</ul>

<h2>Project 2 - <a href="https://github.com/Nirali4/Networking_Projects/tree/master/Network-Port-Address-Translation">Port Address Translation</a></h2>
Implemented a simple network scenario of Port Address Translation (PAT) with Access-List (ACL) which will allow us to translate the private IP address into a public IP address (vice versa. It uses different port numbers instead of a specific IP address. This will help the company to save money as the least or no extra IP addresses needed to be leased from Internet Service Provides. 

<h4>Configuration includes:</h4>
<ul>
  <li>IP translation method: PAT
  <li>Packet filter: Standard Access-List 
  <li>IP addressing scheme: IPv4
  <li>Routing protocol: Routing Information Protocol (RIPv2) 
  <li>Other: Dynamic Host Configuration Protocol (i.e. DHCP)
</ul>
