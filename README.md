# ICMP-Traffic-Analysis-using-Wireshark  
This project demonstrates a basic analysis of ICMP traffic using Wireshark,focusing on Echo Request and Echo Reply messages(commonly used by the 'ping' command) 

**Objectives**  
 -Understanding ICMP protocol basics  
 -Capturing and analyzing ping(ICMP Echo) traffic  
 -Using Wireshark filters to inspect ICMP types  
 -How ICMP work in cybersecurity  
 
**Project Files**  
  -capture/icmp.pcapng -Captured ping traffic   
  -analysis/icmp.report.md - Detailed findings and observations   
  -screenshots  -Wireshark filter views and protocol breakdowns   

**Wireshark Filters Used**  
 -icmp  
 -icmp.type==8 (Echo Request)  
 -icmp.type==0 (Echo Reply)  

**Security Relevance**  
 ICMP Often Used for:    
   -Host Discovery(used in reconnaissance)   
   -DOS Attacks(for ex: ICMP floods,ping of death)   
   -Network troubleshooting  
