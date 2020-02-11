---
layout: post
title:  "Safer Internet Day 2020"
author: rotimi
categories: [ safer internet, Hacking ]
tags: [naijasecforce]
image: ../assets/images/sfid.png
description: "My review of Inception movie. Acting, plot and something else in this short description."
featured: true
hidden: true
rating: 4.5
---


February 11 is [Safer Internet Day](https://www.saferinternet.org.uk/safer-internet-day/2019) and the theme for this year's is "Together for a better internet". Safer internet day is celebrated globally to promote the safe and positive use of digital technology for children and young people and inspire a national conversation.

Subsequent, to our review of [Data Breaches in 2019](https://blog.naijasecforce.com/data-breaches-in-2019/). We are taking part in the Safer Internet Day to promoting online safety for all users (both young and old). We have included 5 tips to ensuring internet safety. 

### Do not re-use passwords
According to a 2019 [Google Survey](http://services.google.com/fh/files/blogs/google_security_infographic.pdf), 65% of people use the same password for multiple accounts. In addition,an investigation carried out by [Microsoft](https://www.microsoft.com/securityinsights/identity) between January 2019 and March 2019 revealed that over 44m Microsoft Users were using compromised credentials (those accounts were forced to reset their passwords). That's alot and concerning. Remember the  [Disney+ hack](https://www.zdnet.com/article/thousands-of-hacked-disney-accounts-are-already-for-sale-on-hacking-forums/) which happened last year where users lost access to their accounts or the [Ring hack](https://www.popularmechanics.com/technology/security/a30242264/ring-doorbell-hack/) where a strange voice was heard in a little's girl room. These were as a result of users re-using passwords across multiple platforms and websites resulting in some accounts being vulnerable. The risk is that attackers can use those compromised credentials to log on to other platforms and services.   

For IT Administrators, you can integrate your Active Directory with password hashes on HaveIBeenPwned to prevent your users from using already compromised passwords. You can use various implementation techniques like [checking for breached passwords](https://jacksonvd.com/checking-for-breached-passwords-ad-using-k-anonymity/), [Integrting database of pwned passwords with nicrososft active directory](https://amarkulo.com/integrating-database-of-pwned-password-hashes-with-microsoft-ad/#more-25), [integrting database of pwned password hashes](Integrting database of pwned passwords) and (https://support.knowbe4.com/hc/en-us/articles/360001508408-Breached-Password-Test-BPT-).

### Use Password Managers
A Password Manager is a program that stores your passwords in an encrypted form, helps you generate strong passwords and remembers passwords for you. Bear in mind, it comes with its own risks. You may forget your master password (the password to your password vault) or if your master password gets compromised (the keys to other platforms and services are at risk).   

However, generally they are a very good way to creating strong passwords as you do not need to remember them at all. You can also generate a distinct password for every site you use thereby preventing credential stuffing attacks (where attackers try a compromised credentials on various sites). Interestingly, if you use a password manager to create passwords for all your accounts you can track services with which you have accounts with.   

Good Password Managers include 1Password, LastPass, KeePass etc. 

### Phishing Emails
You probably get those emails that "come" from your bank telling you, your account is disabled or your late grandfather's cousin left you $500m and that have been looking for you to inherit the money.   

If an email or SMS seems too good to be true, then it’s a phishing email. If you get an email or an SMS from your bank asking you to click on a link even though it looks legitimate. Try going directly to the site yourself or calling your bank. 

Sometimes, you get calls from a representative of your bank alerting you to a suspicious transaction or activity. Then they ask you to read out the pin sent as an SMS to your phone in order to block the transaction.    

### Use HaveIBeenPwned
[HaveIBeenPwned](https://haveibeenpwned.com/) is a service that lets anyone assess if their personal data has been "pwned"or compromised in a data breach. The service collects and analyses various password database dumps containing leaked accounts. It allows users to search for their information via their username or email address. In addition, it allows users to check if their passwords has been exposed in a data breach (this is important in order to prevent hash table attacks - where attackers tries various password hashes in order to match the hash of a user's password).    

Users can also sign up to be notified if their username or email address pops up in a future breach.   

For IT Administrators, you can add register for a domain search. This service allows you find all email addresses in your domain that have been exposed in a data breach (past and future data breaches).    

### Do not share too much online.    
The internet is vast, wonderful and a dangerous place. Sharing too much information about yorself might lead you into trouble. Cybercriminals can leverage on information been shared online to build trust and cause some damages to you or your organization. Do not share personal information like your location or date of birth.    
"The internet is a permanent digital record that will live on long after we are gone"

## Refrences
1. http://services.google.com/fh/files/blogs/google_security_infographic.pdf   
2. https://www.microsoft.com/securityinsights/identity    
3. https://www.zdnet.com/article/thousands-of-hacked-disney-accounts-are-already-for-sale-on-hacking-forums/    
4. https://www.popularmechanics.com/technology/security/a30242264/ring-doorbell-hack/   
5. https://jacksonvd.com/checking-for-breached-passwords-ad-using-k-anonymity/    
6. https://amarkulo.com/integrating-database-of-pwned-password-hashes-with-microsoft-ad/#more-25   
7. https://www.reddit.com/r/sysadmin/comments/8bod2o/integrating_database_of_pwned_password_hashes/   
8. https://support.knowbe4.com/hc/en-us/articles/360001508408-Breached-Password-Test-BPT-   
9. https://haveibeenpwned.com/   

## About Author:
[Mosimilolu Odusanya](https://www.linkedin.com/in/mosimilolu-odusanya) is a cybersecurity senior consultant with experience in IT Audit and IT Security Consulting. She has assisted SEC-Listed organisations with various cyber security projects from Security Assessments, Data Privacy Law Implementation, SCADA Assessments, etc. She have also have worked with various clients in various sectors including Oil & Gas Companies, Financial Institutions, Insurance Companies etc.

One of her goals is bridging the gender gap in cyber security by motivating women to join the Cyber Security Industry. She is also available for a chat/discussion if any lady needs it. 

She enjoys travelling and blog about her experience on www.eattechtravel.com.

