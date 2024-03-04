# ATT&CK Lab
MITRE ATT&CK is a knowledge base of adversary tactics, techniques, and procedures (TTPs) based on real-world cybersecurity observations. The ATT&CK framework provides the attacker's perspective on each stage of the cyberattack lifecycle, from end to end.

## Objective

The ATT&CK Lab project aimed to establish a controlled environment for simulating and detecting cyber attacks techniques. The primary goal be familiar with various techniques. This hands-on experience was designed to deepen understanding in using ATT&CK framework.

### Skills Learned

- Expertise in proactive threat-hunting methods, like anomaly detection, log analysis, and behavioral analytics by leveraging MITRE ATT&CK to detect and eliminate threats before they have a chance to cause harm.
- Leveraging MITRE ATT&CK in incident response and digital forensics to identify indicators of compromise (IOCs), investigate security incidents, and attribute attacks to specific threat actors. 

### Tools Used

- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Network analysis tools (such as Wireshark) for capturing and examining network traffic.
- Telemetry generation tools to create realistic network traffic and attack scenarios.

## Steps
The question in the lab gives a scenario of "A company heavily relying on cloud services like Azure AD, and Office 365 publicly. What technique should you focus on mitigating, to prevent an attacker performing Discovery activities if they have obtained valid credentials?" 
##Question 1 screenshot.
<img width="877" alt="Screenshot 2024-03-04 at 19 02 43" src="https://github.com/AlCybx/ATT-CK-Lab/assets/161755166/5aac0239-eaed-4fdd-95e5-1cf9f48ca1fa">

*Ref 1: MITRE ATT&CK search*
<img width="1343" alt="Screenshot 2024-03-04 at 19 16 37" src="https://github.com/AlCybx/ATT-CK-Lab/assets/161755166/5a925e56-3c08-452e-be12-c1244ad56354">
<img width="1440" alt="Screenshot 2024-03-04 at 19 18 02" src="https://github.com/AlCybx/ATT-CK-Lab/assets/161755166/e869b10b-31a6-4f3b-ae73-55c9f7ba726c">
Given that Question 1 mentions the company's reliance on cloud services, my initial thought is to consult the MITRE ATT&CK framework to identify relevant techniques and other cloud services utilized by the organization. Furthermore, the Cloud Services Dashboard can serve as an additional resource for discovery purposes.

##Question 2
Finding APT group while analyzing a log and found uncommon data flow on port 4050.
<img width="882" alt="Screenshot 2024-03-04 at 20 12 39" src="https://github.com/AlCybx/ATT-CK-Lab/assets/161755166/3d3b95cb-1036-41a6-9388-7705ceba2232">

*Ref 2: MITRE ATT&CK search*
<img width="1398" alt="Screenshot 2024-03-04 at 20 16 26" src="https://github.com/AlCybx/ATT-CK-Lab/assets/161755166/b3de6e72-4ba5-426c-9eb0-db44486989cd">
<img width="1306" alt="Screenshot 2024-03-04 at 20 18 45" src="https://github.com/AlCybx/ATT-CK-Lab/assets/161755166/296f971b-538d-457c-acf2-8869682de120">
As indicated in the question on finding the APT group port 4050. Upon researching the port number in the ATT&CK framework, the results revealed the involvement of an APT group, as depicted in the attached screenshots. The APT group is G0099.

##Question 3
Finding the framework thar has a list of 9 techniques that falls under the tactic to try to get into your network.

*Ref 3: MITRE ATT&CK search*
<img width="126" alt="Screenshot 2024-03-04 at 21 19 04" src="https://github.com/AlCybx/ATT-CK-Lab/assets/161755166/9c57c411-3078-4b27-8398-dbfcf5226a1f">
<img width="1440" alt="Screenshot 2024-03-04 at 21 20 11" src="https://github.com/AlCybx/ATT-CK-Lab/assets/161755166/deb449f9-e5a8-48e0-a343-8a6477c83cc8">
Initial Access consists of techniques that use various entry vectors to gain their initial foothold within a network. Techniques used to gain a foothold include targeted spearphishing and exploiting weaknesses on public-facing web servers. 

##Question 4
Finding a software that prohibits users from accessing their account by deleting, locking the user account, changing password etc. What such software has been documented by the framework?

*Ref 4: MITRE ATT&CK search*
<img width="1440" alt="Screenshot 2024-03-04 at 21 55 05" src="https://github.com/AlCybx/ATT-CK-Lab/assets/161755166/cbb28229-e6cb-4d7c-8828-65a359ade160">
<img width="1440" alt="Screenshot 2024-03-04 at 21 55 46" src="https://github.com/AlCybx/ATT-CK-Lab/assets/161755166/3b73f1a2-e252-426f-a1d4-6105bc8c799b">
In an effort to identify the software that prevents access to user accounts through deletion, account locking, or password modification, I conducted a search using relevant keywords. This led me to discover that Lockergoga is known for altering account passwords and logging off current users, as I learned from further reading.






