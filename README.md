https://docs.google.com/document/d/1Zja1b72fZuLunJIg5N1SLv2vtpVvemkKB-TgyyMr7Uo/edit?usp=sharing  -link to study plan doc
Meta Network Engineer 6-Month Study Guide (2026)
Study Plan Overview
This guide provides a day-to-day breakdown to prepare for a Network Operations role at Meta, focusing on the high-density, automated environments used in their data centers.
Cisco 300-635 Books | NWExam
Cisco Announces New AI Certifications and Courses
Start Your Journey into the Future with Cisco's AI Solutions ...
Learn Python for Network Engineers: Blog 1 - RichardKilleen
Phase
Focus Area
Primary Resource
Months 1–2
Python & DevNet Foundations
Cisco NetAcad PE1 & PE2
Months 3–4
Data Center Automation (DCNAUTO)
Cisco U. DCNAUTO Path
Months 5–6
AI Infrastructure & Fabric (DCAIAOT)
Cisco DCAIAOT Track

Months 1–2: Python Fundamentals [1]
Goal: Reach intermediate proficiency (PCAP level). Meta interviews often include "Leetspec" coding tasks related to log parsing. [2, 3]
Month 1: Python Essentials 1 (PE1) [4]
Days 1–5: Introduction to Python and Computer Programming. Focus on basic syntax and data types.
Days 6–10: Operators, Variables, and Basic I/O. Practice arithmetic operations and the input() function.
Days 11–20: Control Flow (If/Else) and Loops (for, while). Practice building logic gates for network status checks.
Days 21–25: Lists and List Processing. Master indexing and slicing, crucial for handling interface lists.
Days 26–30: PE1 Module Tests and Recap. [4, 5]
Month 2: Python Essentials 2 (PE2) [6]
Days 31–40: Functions, Tuples, and Dictionaries. Dictionaries are essential for mapping IP addresses to device names.
Days 41–50: Modules and Packages. Learn how to import libraries like json and sys.
Days 51–55: File Handling. Practice reading raw syslog files and writing out filtered error reports.
Days 56–60: Final PCAP Exam Preparation.
 [5, 6, 7]
Months 3–4: DCNAUTO (Data Center Automation)
Goal: Automate Day-0 to Day-2 operations using APIs and Configuration Management. [8]
Month 3: Network Programmability & APIs
Days 61–75: REST API Basics. Use Postman or Python requests to interact with Always-On Sandboxes.
Days 76–90: Model-Driven Programmability. Study YANG data models and the difference between NETCONF and RESTCONF. [7, 8]
Month 4: Infrastructure as Code (IaC)
Days 91–105: Ansible Playbooks. Learn to push bulk configurations to simulated Arista/Cisco switches.
Days 106–115: Terraform for Networking. Practice defining network state as code.
Days 116–120: Git/GitOps. Master branching and pull requests for network changes.
 [7, 9]
Months 5–6: DCAIAOT (AI Data Center Operations)
Goal: Master lossless Ethernet and high-scale RDMA fabrics required for AI training clusters. [10]
Month 5: AI Fabric Fundamentals (DCAIE)
Days 121–135: AI Workload Placement. Understand how GPU clusters communicate.
Days 136–150: RoCEv2 Mechanics. Study RDMA over Converged Ethernet and how it bypasses CPU bottlenecks. [10, 11]
Month 6: Troubleshooting & Monitoring (DCAIAOT)
Days 151–165: Congestion Management. Master PFC (Priority Flow Control) and ECN (Explicit Congestion Notification) protocol physics.
Days 166–175: Telemetry & Analytics. Learn to use Splunk for log correlation and issue diagnosis in AI environments.
Days 176–180: Final Review and Mock Interviews.
 [10, 12]
Lab Setup: GitHub Codespaces + Containerlab [13]
To simulate Meta's environment for free, use this setup:
Initialize Codespace: Create a repository and launch a 4-core GitHub Codespace.
Install Containerlab: Run the install script: bash -c "$(curl -sL https://get.containerlab.dev)".
Import cEOS: Download the Arista cEOS-lab image from Arista.com and import it:
sudo docker import cEOS-lab-X.XX.tar.xz ceos:latest.
Deploy Lab: Use a topology YAML to spin up your virtual data center: containerlab deploy.
 [14, 15, 16]

[1] https://www.youtube.com
[2] https://training.cam.ac.uk
[3] https://infraexam.com
[4] https://www.netacad.com
[5] https://www.youtube.com
[6] https://infraexam.com
[7] https://www.nwexam.com
[8] https://www.cisco.com
[9] https://www.udemy.com
[10] https://www.enterone.com
[11] https://u.cisco.com
[12] https://www.globalknowledge.com
[13] https://medium.com
[14] https://arista.my.site.com
[15] https://github.com
[16] https://arista.my.site.com
