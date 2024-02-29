# Microsoft-Window-Defender-Firewall-Project

## Objective
[Brief Objective - Remove this afterwards]

The Detection Lab project aimed to establish a controlled environment for simulating and detecting cyber attacks. The primary focus was to ingest and analyze logs within a Security Information and Event Management (SIEM) system, generating test telemetry to mimic real-world attack scenarios. This hands-on experience was designed to deepen understanding of network security, attack patterns, and defensive strategies.

### Skills Learned
[Bullet Points - Remove this afterwards]

- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used
[Bullet Points - Remove this afterwards]

- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Network analysis tools (such as Wireshark) for capturing and examining network traffic.
- Telemetry generation tools to create realistic network traffic and attack scenarios.

## Steps
### Lab 1: Access and review Windows Security Virus & threat protection in a virtual environment. Run scans for threats.

1. Navigate to ‘Virus & threat protection’ Windows Security settings. Check for updates, then run a Quick scan for threats. 
![image](https://github.com/Damien-Lindsey/Microsoft-Window-Defender-Firewall-Project/assets/161356460/71acadf4-27a1-4679-8e6a-ea2e649166c8)
![image](https://github.com/Damien-Lindsey/Microsoft-Window-Defender-Firewall-Project/assets/161356460/b1c5b72a-5e39-4101-9cb2-51c20dff44ea)
![image](https://github.com/Damien-Lindsey/Microsoft-Window-Defender-Firewall-Project/assets/161356460/5c4cf67a-58c7-44c5-b742-617addd74d12)

2. Review Threat history to review results of last scan. Confirm there are no threats in Last scan, Quarantined threats, or Allowed threats sections.
![image](https://github.com/Damien-Lindsey/Microsoft-Window-Defender-Firewall-Project/assets/161356460/aecd4530-45f0-4697-9846-bdcf32be2a7a)

3. Run a custom scan that only scans files in Downloads folder.
![image](https://github.com/Damien-Lindsey/Microsoft-Window-Defender-Firewall-Project/assets/161356460/b3b0bf6b-7923-4b54-9c7f-b8f73c9ce5c7)
![image](https://github.com/Damien-Lindsey/Microsoft-Window-Defender-Firewall-Project/assets/161356460/fb1ca2ea-f9f2-427d-9106-434668ad4f13)
![image](https://github.com/Damien-Lindsey/Microsoft-Window-Defender-Firewall-Project/assets/161356460/2f7e9e0b-eded-45b3-a59d-9989c37b918d)


### LAB 2: Configure firewall rules using the Windows Defender firewall in a virtual environment.

1. Access Firewall & network protection settings in Windows Security settings.
![image](https://github.com/Damien-Lindsey/Microsoft-Window-Defender-Firewall-Project/assets/161356460/b0d131d1-5d34-4bb2-8a03-66c0063caad6)

2. Confirm Windows Defender Firewall is on for the domain network and the checkbox for blocking incoming connections is unchecked. Repeat for private and public network.
![image](https://github.com/Damien-Lindsey/Microsoft-Window-Defender-Firewall-Project/assets/161356460/ebdba11c-35f0-45a3-b783-561b0217d597)

3. In ‘Allow app through firewall’ setting, configure Firefox to communicate on the public network.
![image](https://github.com/Damien-Lindsey/Microsoft-Window-Defender-Firewall-Project/assets/161356460/75a42c6c-e797-4716-99b3-e114d432ab20)
![image](https://github.com/Damien-Lindsey/Microsoft-Window-Defender-Firewall-Project/assets/161356460/09e83f4a-96ed-4f05-a221-e5566681dfa9)

4. For inbound rule ‘Key Management Service (TCP-In)’, disallow public communication.
![image](https://github.com/Damien-Lindsey/Microsoft-Window-Defender-Firewall-Project/assets/161356460/dd4872ea-be44-4888-9d58-fbe7530cba06)
![image](https://github.com/Damien-Lindsey/Microsoft-Window-Defender-Firewall-Project/assets/161356460/cf57949d-cd9c-48af-a85f-a691172e0cd5)
![image](https://github.com/Damien-Lindsey/Microsoft-Window-Defender-Firewall-Project/assets/161356460/50d6ce1f-df6f-4375-9a9a-aaed220c6b87)

5. Create ‘Key Management Service (TCP-In)’ inbound rule that blocks communication with the public network. To do this copy the other ‘Key Management Service (TCP-In)’ rule and configure it. Finally enable both inbound rules.
![image](https://github.com/Damien-Lindsey/Microsoft-Window-Defender-Firewall-Project/assets/161356460/61dedcbb-9ecb-4faa-8b66-3fba4317a043)
![image](https://github.com/Damien-Lindsey/Microsoft-Window-Defender-Firewall-Project/assets/161356460/23e60f2d-8353-4c32-86b8-a64f5a586f55)
![image](https://github.com/Damien-Lindsey/Microsoft-Window-Defender-Firewall-Project/assets/161356460/1e4a0c5c-ab2a-4ed2-8ee2-1edc44b39a7a)
![image](https://github.com/Damien-Lindsey/Microsoft-Window-Defender-Firewall-Project/assets/161356460/b99e285a-5b52-4761-9200-8be36feeca7a)
