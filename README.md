# Web Security
## Social Media & TOR

### Lab Requirements
- Internet connectivity & VMware Workstation version 14.0.0 or above.
- A web browser with default settings.
- Windows 10 vm
- Ubuntu vm

### Lab Overview
This lab focuses on understanding the implications of social media presence, the use of robots.txt for web crawlers, analyzing routing information, and exploring the dark web using the TOR network. 

### Lab Tasks and Screenshots


### Part 01: Create a robots.txt file
**Task**: Use a robots.txt file to control web crawlers on your personal Ubuntu Web Server VM.
- **Slide 01**: Screenshot showing the contents of your robots.txt file, demonstrating the rules set for different user agents and directories.

<img src="https://i.imgur.com/r5XXtZs.png" height="400px" width="auto" alt="Robots.txt File Contents"/>


### Part 02: Display the routes of the Facebook bots
**Task**: Investigate and capture the routing information for Facebook bots.
- **Slide 02**: Screenshot showing the robotindex.txt file with the routes of Facebook bots as captured from the whois command.
  
<img src="https://i.imgur.com/T17CXZX.png" height="400px" width="auto" alt="Facebook Bots Routing Information"/>
  

### Part 03: Download and Install the TOR Browser
**Task**: Download, install, and navigate the dark web using the TOR browser.
- **Slide 03**: Screenshot showing the hidden wiki page and the output of `net config workstation` filtered to "name".

<img src="https://i.imgur.com/nBptrmd.png" height="400px" width="auto" alt="TOR Browser and Hidden Wiki Page"/>


### Part 04: Configure the Ubuntu Server to use Hidden Services
**Task**: Configure Ubuntu Server VM to host a service over the TOR network.
- **Slide 04**: Screenshot showing the contents of `/etc/tor/torrc` as updated with HiddenService and other TOR configurations.
    
<img src="https://i.imgur.com/Ps4zXnK.png" height="400px" width="auto" alt="TOR Configuration"/>
    

**Conclusion**: This lab provides insights into personal digital footprints, controlling web crawlers, understanding network routing, and exploring hidden services with TOR. This lab emphasizes the importance of privacy, security, and understanding the complexities of the internet and dark web.

