---
layout: post
title:  "THE USB TRAIL: ANTI-FORENSICS AND ANTI-ANTI-FORENSICS BITTER ROMANCE"
author: Chidi
categories: [ Career]
tags: [Simbiat, naijasecforce]
image: ../assets/images/USB-Trail-Chidi-Used-USB.jpg
description: "Using Digital Forensics to prove that an a USB device was used to conduct an attack."
featured: false
hidden: true
rating: 4.5
---

# 20 things Cybersecurity Teams need to do better in 2020 – NaijaSecForce Edition
cybersecurity remains a great concern as cyber attacks continue to rise. Cybersecurity teams are responsible for protecting IT infrastutures, networks and data among others from cyber attacks. For effective cyber defense, cybersecurity teams should incoperate the folowing:

1.	**Review completeness of asset inventory:** You need complete visibility into what is on your network, where your data is and where it transverses.
2.	**Improve endpoint security:** Implementing an EDR on your endpoints would aid detection and possible prevention of attacks that starts from your endpoints. If you do not have the budget for EDR, rollout Sysmon on endpoints and tweak the sysmon config files from SwiftOnSecurity/olafhartong to suit your environment.
3.	**Log. Every. Thing. Okay**, just kidding, but you need to identify critical devices on your network, critical applications (onprem/remote/cloud), endpoints (laptops, desktops, etc), email system, web proxies, Active directory, etc. Enable their logs, forward to a centralized location (with the aid of a SIEM solution) – and build effective use cases around them.
4.  **Manage risk of obsolete software:** identify obsolete software within your environment and prioritize remediation activities for those that have exploits available in the wild. You might need to put in compensating controls for those you cannot upgrade right away.
5.  **Review adequacy and effectiveness of compensating controls:** Remember the conversation you had with your system/network/application/database team – where you identified existing vulnerabilities which they could not patch, but then, they had compensating controls instead? Now is the time to review those compensating controls. Are they still valid? Are they effective? You need to re-evaluate these controls.
6.	**Enhance your email security:** Implement email filtering controls and look out for things like Similar Internal Domain, Newly Observed Domain, Similarity of sender's name with internal user's name, Reply-to Address Mismatch, etc. Also, you can have a regex match of phishing keywords based on a dictionary – to match against body/subject of inbound/outbound emails. You should also carry out URL sandboxing checks, Attachments sandboxing checks, etc. Enabling DMARC/DKIM/SPF is also key.
7.	**Use of Deception technology:** A well deployed deception solution would go a long way in timely identification of an adversary within your network. Again, if your environment is not mature enough, do not opt for this. Leverage on existing threats within your environment – to build more detective and preventive controls.
8.	**Implement two factor authentication:** If an adversary has access to passwords, a second factor would provide an additional layer of protection
9.	**Improve database security controls:** Put in place database security controls and enhance monitoring capabilities of critical databases.
10.	**Improve interactions with stakeholders:** Alignment with the organization’s goals is crucial to building and maintaining a successful security program. Actively engage your stakeholders (board, senior management, colleagues, etc). Make them understand the WHY, WHEN, WHAT, HOW & WHERE.
11.	**Review your KPIs:** Put in place KPIs that give a view of how effective your controls are and have an early indicator when things start to fall apart.
12.	**Third party risk management:** Third parties that provide crucial services and/or store/process sensitive data should be reviewed to ensure adequate controls exist to manage existing risks.
13.	**Cyber insurance:** consider subscribing to a cyber-insurance based on the results of a risk assessment and nature of your business. Remember the saying, “The question is not IF you are going to be hacked, but WHEN”. .Let's face it, you are going to be hacked anyways, or not?
14.	**Cloud security:** Identify all cloud based services and put in place relevant controls to protect your data stored in the cloud. You might also want to consider use of a CASB solution.
15.	**Identity and Access management:** The practices adopted by an organization in granting access to “crowned-jewels” should continue being the number 1 priority. A more data-centric view to identity should be prioritized and specifically, role-based access to application and resources should be seamless and transparent to the security team as well as real-time monitoring embedded in the entire process. This also applies to privileged admins/IDs as well as multi-cloud environments which organizations are now more willing to adopt.
16.	**Zero Trust environment:** much talk has been discussed about zero-trust in the last 5-6 years, with every security vendor having a different interpretation each time. However, at the principle-level, organizations need to consider a model where (and this could be network-centric or the preferred identity-centric) the design does not automatically trust anything inside or outside its perimeters but instead must verify anything and everything trying to connect to its systems before granting access.
17.	**Security by Design/DevSecOps:** Even with the increased automation of manual activities (SAST, DAST, IAST), developers remain one of the biggest stakeholders in the security of software applications. The relationship between security and development within the DevSecOps bubble is essential and this has to keep being reinforced from the requirements gathering/design phases until deployment. Developers need to be constantly trained to develop secure code as part of their regular BAU.
18.	**Orchestration Automation:** SOC teams are inundated with all types of alerts and this comes with the territory of continuous monitoring. However, the resultant effect is alert fatigue and thus high priority breaches could be missed in this process. Automating the orchestration and response helps to alleviate this problem to a high degree and where possible this should be adopted for all types of alerts.
19.	**Think Like Us:** If one isn’t in the security field, it’s almost always an uphill task in making them understand and see cybersecurity issues from our point of view. However, with the continued modus operandi by cybercriminals targeting the human element, employees are still (kind of) the first line of defense. Engaging them positively to identify suspicious emails/activities, best practice techniques on managing their passwords/devices/identities, secure browsing/internet activities and reporting anything suspicious to the cybersecurity team will eventually pay dividends and ultimately improve the security posture of that organization from a culture, controls and compliance point of view. Win – Win
20.	**Attend cybersecurity conferences, webinars and actively engage vendors**:To understand trends, threats and existing controls in the market. Believe everything a vendor tells you BUT verify first. A lot of vendors will come knocking at your door with cyberkillchain/AI/ML/Blockchain keywords – engage them, listen to what they have to sell, see it in action, compare with existing controls in your environment and then take a decision.

### About Authors:

[Rotimi Akinyele](https://ae.linkedin.com/in/nigerianpenetrationtester) currently manages Information Security, Governance and Business Continuity at a Government authority in the United Arab Emirates (UAE).

[Jaiyeola Abimbola](https://ae.linkedin.com/in/abimbola-jaiyeola-06448757) is an Information security professional with a wealth of experience covering operating systems, applications, software development, cryptography, forensics, information risk, software development and payment systems.

[Richard Uhunmwagho](https://ae.linkedin.com/in/ricuhun) is a versatile Cybersecurity Governance, Risk, and Compliance (GRC), Audit & Data Privacy professional with expansive experience in Business and Technology spanning diverse markets and cultures across various regions in several sectors.
