# apex_task1
Kali lab setup
Creating a Virtual Cybersecurity Lab

The purpose of this project was to create a virtual cyber security lab environment, through the use of Oracle VM VirtualBox, where a user can practice penetration testing and network analysis against an attack machine and an intentionally vulnerable target.

Lab Components

Kali Linux is the attacker machine: Kali Linux is a Linux distribution that can run security testing and perform cyber security research. It contains a large number of security tools like Nmap, Wireshark, Burp Suite, and Metasploit which can be used by security personnel while doing vulnerability assessment or ethical hacking.

Metasploitable2 is the target machine: Metasploitable 2 is an intentionally vulnerable VM that is used for practicing penetration tests by exploiting known vulnerabilities and running insecure services, which allows students to practice and gain experience of system exploitation in a controlled manner.

Virtual Lab Configuration

Both Kali and Metasploitable 2 are installed in Virtual Box and are connected using an isolated virtual network. By using an isolated virtual network configuration, the attacker machine (Kali) can communicate with the target machine (Metasploitable 2), and the real network is unaffected.

Wireshark Capture Test

An analysis of the network traffic between Kali and Metasploitable 2 was done using Wireshark, where packets created during scanning and communication between the machines were captured.
Packets Captured will help when observing
The communications between the attacker and the target machines.

Purpose of the Lab

This virtual lab helps learners understand:
Basic penetration testing concepts
Network reconnaissance and packet analysis
Safe cybersecurity experimentation in an isolated environment
The protocol operations for both TCP and DNS.
The TCP three way handshake.
