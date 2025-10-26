Task 4:  **Setup and Use a Firewall (Windows)**


**Overview**

In this task, I configured and tested a firewall on my Windows system to understand how network traffic can be controlled. The goal was to allow or block specific ports and services to improve system security.


**Tools Used**

- Windows Defender Firewall (built into Windows)
  
- Command Prompt (for testing connection with Telnet)
- 

**What I Did**

1. Opened Windows Defender Firewall and navigated to Advanced Settings.
  
2. Viewed existing Inbound and Outbound rules to understand current traffic controls.
  
3. Added a rule to block port 23 (Telnet), since it is considered insecure.
  
4. Tested the block by trying to connect to port 23 using Telnet:
   

   Command used:
   
   telnet localhost 23

   
   Output what i got:
   
    C:\Users\Lenovo>telnet localhost 23
    Connecting To localhost...Could not open connection to the host, on port 23: Connect failed
   

   
6. Verified that the firewall successfully blocked the port.
  
7. Removed the test rule to restore normal settings.
8. 


**Key Learnings**

##Firewalls control network traffic by allowing or blocking connections based on rules.
  
##Blocking insecure services, like Telnet, is an essential step in system hardening.
 
##Testing firewall rules ensures that the intended traffic is correctly blocked or allowed.
  
##Always clean up temporary rules after testing to avoid accidentally blocking needed connections.


## Screenshots / Evidence
One of the final output screenshot is included



