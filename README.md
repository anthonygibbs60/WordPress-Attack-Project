# WordPress-Attack-Project

For our Final Engagement project as part of the ASU Cybersecurity Bootcamp, our team was tasked with defensive, offensive, and network analysis of a WordPress server on an Azure virtual machine network. 

Utilizing an ELK SIEM and Kibana, we set up defensive alerts on our Target VM to monitor for any potential malicious activity from attacks against the WordPress server. Assuming the role of a Red Hat team, we attacked our WordPress virtual machine via a Kali Linux machine to capture 4 flags hidden on the WordPress website and server. Finally we performed analysis of the network traffic, captured via Wireshark, to confirm a baseline for normal traffic on the network and confirm any malicious activity. 

Our presentation is focused on the network analysis portion of the project. Utilizing Nmap scripting we identified several critical and high severity vulnerabilities on the WordPress machine. While analyzing the captured traffic in Wireshark we performed a behaviorial analysis of the users on the network to confirm normal behaviour for the network, as well as document any suspicious activity. Our team was able to identify several users on the network misappropriating company resources including creation of a personal Active Directory, downloading ransomware, as well as downloading torrented movies. 
