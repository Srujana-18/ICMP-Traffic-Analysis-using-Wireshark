Capture Summary:  
  ICMP requests sent to google.com through ping
  Number packets sent through ping are 4 and received packets are 4.So its 0% packet loss
  Average Response time of packet is 40ms
  
Observations:  
 All ICMP packets followed expected structure
 No signs of flooding and malformed headers found
  
Security Notes:  
  This type of traffic is seen in scanning tools such as nmap uses for host discovery.
  ICMP is often blocked or restricted in sensitive or secure networks because it can pose security risks like Reconnaissance unauthorized sources and Denial of Service attacks.
  Attackers use ICMP tunnels or large payloads to sneak data out of secure network, communicate covertly with infected machines and bypass security controls that don't monitor ICMP closely.
  
Protocol Statistics:  
  Captired through "Statistics>Protocol Hierarchy"
  
  |Protocol|Percent Packets|Packets|Percent Bytes|  
  |ICMP    |100            |8      |65.31        |

  
  
