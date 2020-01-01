---
layout: post
title:  "Data Breaches in 2019"
author: Mosimilolu
categories: [ Data breaches ]
tags: [Databreach, naijasecforce]
image: ../assets/images/databreach2019.png
description: "Data breaches in 2019"
featured: true
hidden: true
rating: 4.5
---

# Introduction

Many organisations today are leveraging the cloud to transform their business and help with cost reduction. However, the adoption of cloud technology introduces new risks, security and privacy concerns. One of these risks introduced are Data Breaches. There is an increasing number of exposed databases containing Personal Identifiable Information (“PII”) and Personal Health Information (“PHI”) and even sensitive company data (*more details later on*). 

Since the enforcement of the EU’s General Data Protection Regulation (“GDPR”), many other countries such as Canada, Brazil, India have begun rolling out similar data protection regulations to ensure higher data security security and giving individuals rights to their personal data. This has also helped with transparency around security incidents and data breaches. However, more work still needs to be done.

This data analysis is an update of the [Data Breaches in 2018 — Infographics](https://link.medium.com/65QgqceFB2). However, the data visualization is now interactive(*really excited about this*). Data research, gathering, analysis and visualization done by me.
The data analysis here considers the following factors:
* Method of compromise;
* Attack vector; and
* Data Sensitivity.

## Method of Compromise
1. **Oops!**  
These are data breaches that occurred due to some lapse in security processes or procedures. Sample cases include [FEMA](https://www.oig.dhs.gov/sites/default/files/assets/2019-03/OIG-19-32-Mar19.pdf), [Orvis](https://krebsonsecurity.com/2019/11/retailer-orvis-com-leaked-hundreds-of-internal-passwords-on-pastebin/), [Sephora](https://www.zdnet.com/article/sephora-data-breach-hits-southeast-asia-and-anz-customers/) etc. 

2. **Hacked**  
These are data breaches that occurred from someone attacking and/or gaining unauthorised access. Sample cases include [Capital One](https://www.businessinsider.com/capital-one-data-hacked-by-seattle-woman-affecting-millions-2019-7), [Macy](https://techcrunch.com/2019/11/19/macys-said-hackers-stole-customer-credit-cards-again/), [Hookers.nl](https://www.forbes.com/sites/thomasbrewster/2019/10/10/dutch-prostitution-site-hookersnl-hacked--250000-users-data-leaked/#372a098922f8) etc. 

3. **Insider job**  
These are data breaches that occured due to someone on the inside (i.e., employee, contractor, service provider etc.) exploiting their authorised access. Sample cases include [Trend Micro](https://blog.trendmicro.com/trend-micro-discloses-insider-threat-impacting-some-of-its-consumer-customers/), [Lion Group](https://www.reuters.com/article/us-lionair-leak/malindo-air-says-data-leak-caused-by-ex-staffers-at-contractor-firm-idUSKBN1W80DT), [Sberbank](https://www.sberbank.ru/en/press_center/all/article?newsID=04885252-1561-44c0-8532-2c4f33cd729f&blockID=1539&regionID=77&lang=en&type=NEWS) etc. 

4. **Misconfiguration**  
These are data breaches that occured due to misconfigurations in the Cloud Infrastructure such as Elasticsearch database, MongoDB, CouchDB, AWS Buckets etc. that allowed an individual to access the database without authentication. Sample cases include [Adobe](https://www.comparitech.com/blog/information-security/7-million-adobe-creative-cloud-accounts-exposed-to-the-public/), [Facebook](https://techcrunch.com/2019/09/04/facebook-phone-numbers-exposed/), [Pyramid Hotel Group etc.](https://www.vpnmentor.com/blog/pyramid-hotel-group-data-leak/) 

5. **Third Party**  
These are data breaches that are caused third parties such as Vendors, IT Contractors, Service Providers, Middleman etc. Sample cases include [Doordash](https://blog.doordash.com/important-security-notice-about-your-doordash-account-ddd90ddf5996), [Jana Cash](https://securitydiscovery.com/jana-bank-data-leak/), [Dow Jones Watchlist](https://securitydiscovery.com/dow-jones-risk-screening-watchlist-exposed-publicly/) etc. 

## Attack Vectors
These describe in more detail, the cause of compromise e.g. patch management, phishing attack, SQL injection, malicious scripts, exposed database etc. 

## Data Sensitivity
The other factor considered is the sensitivity of compromised data during that breach. Here, the data sensitivity has been classified into 5 categories:

1. **Online Information**  
These are details such as email address, usernames, passwords, gender etc.

2. **Personal Details**  
These are information that can be classified as personally identifiable information (“PII”) such as name, address, phone numbers, location, devices, IP address etc.

3. **Financial Information**  
These are information that are related to financial data such as credit card information, (un)hashed credit card details, payment card type etc.

4. **Health Records**  
These are information that can be classified as protected health information (“PHI”) such as medical record numbers, medical records, health insurance details, health plan beneficiaries, biometric identifiers etc.

5. **Company Data** 
These are information that can be classified as proprietary or sensitive company data and PII of employees such as such as username, host name, admin login credentials, endpoint security status etc. 

# Data Analytics — Data Breaches in 2019

<iframe width="933" height="750" src="https://app.powerbi.com/view?r=eyJrIjoiOTRiYTI3NTEtZmRmNS00MWZkLWFkOTYtMjVjZjNmNGU1N2M4IiwidCI6IjY5MDUwYzk0LTI5NmItNDYzYS04ZjBlLTZlMjZhNDNhOWI3YSIsImMiOjl9" frameborder="0" allowFullScreen="true" markdown="1"></iframe>


## Important Details
1.	Some  Data Compromised have been represented as 1. This is because for some breaches, the number of records compromised were not indicated or were indicated in terms of the size of the records compromised.
2.	To see the full data, right click Drillthrough  —  Full Data.

## Interesting Cases
1. **The Unknown Owner**   
In October, [2 Security Researchers](https://www.dataviper.io/blog/2019/pdl-data-exposure-billion-people/) found an open (no authentication or password was required to access or download the data) Elasticsearch server containing 4 billion user accounts amounting to about 4TB of data — more than 1.2 billion unique people scraped from social media sources such as Facebook, LinkedIn. It also contained details like names, email addresses, phone numbers, Twitter and, Github URLs.
In addition, the datasets appeared to be scrapped from 2 data enriching companies — People Data Labs (“PDL”) and OxyData.io (“OXY”). A data enrichment is a process of enhancing or improving or enriching a piece of information (e.g. name or username) with data from other sources. Even though the data seemed to come from both sources (PDL and OXY), the owner of the server was unknown. It raises the concern of who is liability for this breach — PDL/OXY or their customer? There is an argument that the data was “publicily available information” however, nobody consented to their information being used liked this (I certainly did not). This case is similar to the Cambridge Analytica Scandal and the Exactis Data Breach. 

2. **Exposed Internal IT Data**  
In July, a [Security Researcher](https://rainbowtabl.es/2019/07/31/honda-motor-company-leak/) found an open (no authentication or password was required to access or download the data) Elasticsearch server containing 134 million records amounting to about 40GB of data. More data records were being added to the database.
An analysis of the database revealed that it contained data from Honda’s global employee machines. It contained details about the employee’s personal data (name, department, account name, user name etc.), machine (patches applied, IP Address, MAC Address, endpoint security status etc.). Imagine a malicious individual had access to such data.

3. **Third Party Risk**  
This case is said to be the largest medical breach in 2019. In February, a security research company identified some PII being sold on the dark web. An analysis of the data revealed it may have been stolen from American Medical Collection Agency (“AMCA”). AMCA handled patient collections for a number of healthcare providers all of whom have been affected by the data breach. This included — Quest Diagnostics (11.9m patients) and LabCorp (7.7m patients). Currently, AMCA has filed for bankruptcy due to expenses related to the breach.
Managing third party security risk is very important as it allows you review how your vendors/contractors/service providers are managing their risks including your data. The following must be assessed — 
*	Compliance with regulations such as GDPR, PCI-DSS;
*	Business Continuity and Disaster Recovery Plans; and 
*	Security posture — security incidents , penetration test and vulnerability assessment carried out, security controls in place etc.

4. **Another Unknown Owner with Government Data**  
In August, a [Security Researcher](https://www.wizcase.com/blog/chile-leak-research/) found an open (no authentication or password was required to access or download the data) Elasticsearch server containing PII for over 14m Chilean residents above the age of 17. Chile is a South American country with a population of about 19m citizens according to this [report](https://www.worldometers.info/world-population/chile-population/).  
It contained details such as name, address, RUT (Rol Único Tributario — Chile’s National Identification Number and Tax ID number) etc. Although the Chilean Electoral Service has confirmed the authenticity of the data, the owner of the database is unknown. This data can be very valuable in the wrong hands.

5. **Hackers got there first**  
In September, 2 [Security Researchers](https://www.vpnmentor.com/blog/report-bat-romania-leak/) found an unsecured server related to YOUniverse.ro, a Romanian web platform owned by British American Tobacco (“BAT”). The leaked server contained data amounting to about 352GB of data relating to Romanian residents. However, by the time the unsecured server was discovered by the researchers, the server had been compromised by Ransomware. The hackers responsible had copied some of the sensitive data hosted on the server and were threatening to delete the data if their demands (bitcoin payment worth 0.1BTC) weren’t met. Daily logs which were still leaked by the server and weren’t affected by the ransomware attack contained PII such as name, email, phone number, cigarette and tobacco product preferences etc.

### How do Data Breaches Affect Me (as a user/consumer)?

The thing is that there is almost nothing you can do about it. We sign up on different platforms and services, most of which we are very reliant on and there is no company that is 100% secure.
Now that we have gotten that out of the way, what can you do?
* Get a password manager which allows you to have different and secure passwords for different sites;
* Enable Multi-factor authentication (“MFA”);
*	Use a Virtual Private Network (“VPN”);
*	Install a good anti-virus; 
*	Be careful who you share your personal details with;
*	Check senders email addresses when you receive suspicious emails;
*	Don’t click suspicious links or download files from unknown senders;
*	Don’t share personal information on social media;
*	Avoid the internet.

## Summary
The number of data breaches and known amount of data compromised is not comprehensive. My prediction for 2020 is that we would see more data breaches — the worst is yet to come. However, I think more countries and territories would rollout data protection regulations and laws. 

## About Author:
[Mosimilolu Odusanya](https://www.linkedin.com/in/mosimilolu-odusanya) is a member of the NaijaSecForce and a  cybersecurity senior consultant with experience in IT Audit and IT Security Consulting. She has assisted SEC-Listed organisations with various cyber security projects from Security Assessments, Data Privacy Law Implementation, SCADA Assessments, etc. She have also have worked with various clients in various sectors including Oil & Gas Companies, Financial Institutions, Insurance Companies etc.

One of her goals is bridging the gender gap in cyber security by motivating women to join the Cyber Security Industry. She is also available for a chat/discussion if any lady needs it. 

She enjoys travelling and blog about her experience on www.eattechtravel.com.


