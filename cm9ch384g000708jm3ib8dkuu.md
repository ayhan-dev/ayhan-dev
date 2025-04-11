---
title: "How AI agents change attacks with stolen credentials"
seoTitle: "Artificial intelligence agents against hacking"
seoDescription: "Discover how artificial intelligence agents are transforming cybersecurity by detecting, preventing, and countering modern hacking techniques in real-time"
datePublished: Fri Apr 11 2025 07:35:49 GMT+0000 (Coordinated Universal Time)
cuid: cm9ch384g000708jm3ib8dkuu
slug: ai-and-hacking
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1744356693166/477ee0b8-c11b-480d-84f3-7777d2269dca.jpeg
tags: ai, cybersecurity-1, ayhan

---

### Stolen Accounts: The Main Weapons of Cybercriminals in 2024

In 2023-2024, stolen accounts became the most popular method of attack, serving as a hack vector of 80% of attacks on web applications. This is not surprising, given that billions of leaked combined logins and passwords are circulating on the network, and cybercriminals can purchase fresh bases for just $10 on underground forums.

The ferrous ferrous market is actively growing thanks to high-profile leaks of 2024, such as attacks on Snowflake customers, where attackers used accounting data found in data breaches and hacked databases obtained through informalers and mass phishing campaigns. As a result, 165 tenants of Snowflake were compromised and hundreds of millions of records were stolen.

But even despite the unprecedented scale of attacks based on the theft of accounts, there are many unrealized opportunities for attackers.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1744354400435/1de36ed9-7783-44fb-a718-ccdd2de285f9.jpeg align="center")

### Automation of attacks on accounts - what has changed with the transition to SaaS?

The methods of brute force and the selection of accounting data remain key instruments of cybercriminals for decades. However, an automated attack on various systems has become much more complicated than before.

#### The Universal Approach No Longer Works

Previously, IT infrastructure of companies was a single centralized space, where applications and data were inside the corporate security perimeter. Now, business processes have moved to the cloud, and each organization uses hundreds of web applications and platforms, creating thousands of digital identities.

This led to data decentralization: if previously accounts were stored centrally (for example, in Active Directory), now they are distributed across a variety of services that use various mechanisms and authorization protocols.

Although HTTP(S) remains the standard, modern web applications are characterized by a complex, dynamic and customized architecture, where the graphical interface changes for each user. Moreover, they are initially developed with protection against automatic attacks, including bots protection mechanisms such as CAPTCHA.

As a result, criminals can no longer use universal tools. If earlier it was possible to write one script for all services (for example, a DNS scanner, a port scanner Nmap, a single script for attacks on FTP, SSH, Telnet, etc.), now each service requires individual development of attack tools.

#### Filtering useful data in huge arrays of leaks

Attackers have to take into account not only an increasing number of target media for attacks, but also a huge amount of compromised accounts.

At the moment, there are about 15 billion leaked accounts in the public domain on the Internet – and this is without taking into account those that are distributed through closed channels and private databases. Moreover, this list is constantly growing: in the last month alone, 244 million previously uncounted passwords and 493 million unique pairs “+ e-mail” were added to the We I I Been Pwned bases of Instillers.

This sounds frightening, but it is difficult for attackers to effectively use this data array. The vast majority of these accounts are outdated or no longer relevant. A recent analysis of Threat Intelligence (TI) data from Push Security found that less than 1% of stolen data from multi-variable datasets could be used in practice. In other words, 99% of leaked data were outdated or unsuitable for attacks.

However, not all leaks are useless - attacks on Snowflake showed that the attackers were able to successfully use the accounts stolen in 2020. This proves that among the leaked data there are still valuable finds that can be used in attacks.

#### Intruders have to prioritize

The distributed nature of modern applications and digital identities, as well as the low reliability of data from leaks, force attackers to choose the most valuable goals. Despite the abundance of potential goals (hundreds of business applications and thousands of digital identities in each company), there are limitations:

* Automation of attacks for each service is impossible. On the Internet there are more than 40 000 SaaS-applications, and writing individual Python scripts for each - an unrealistic task. Even if you focus only on the 100 or 1000 largest apps, it will require a huge effort to support and update scripts.
    
* Even automated attacks face protective measures. Even with a complete spelling of the attack and the use of the botnet for its distribution (to avoid blocking IP addresses), built-in protection mechanisms (reputation limit, CAPTCHA, blocking accounts) make it difficult for mass attacks.
    
* Large-scale attacks attract attention. If the attackers try to sort out 15 billion passwords in an adequate time frame, it will lead to abnormally high traffic and is likely to cause security systems to be triggered.
    

Therefore, attackers concentrate on a smaller number of applications, checking only the exact matches (for example, if the leaked accounts belong to a specific service).

When criminals still take on new goals, they usually focus on one particular application or platform (for example, Snowflake) or are looking for narrow data categories, such as accounts associated with border devices that are used in traditional corporate networks.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1744355192061/e745c5a8-f4f6-4ce0-9967-93b96b4672a8.jpeg align="center")

### Missed opportunity?

As already noted, attacks with the selection of accounting data already pose a serious threat, despite all the existing restrictions. However, the situation may be even worse.

#### Reused password: one compromised account can lead to a lot of hacks

If attackers can expand the scale of the attacks, targeting not only a few valuable applications, but also a much wider list of services, they will be able to exploit the problem of reusing passwords. According to a recent stud

y of digital identities, the average:

* 1 in 3 employees reuses passwords.
    
* 9% of digital identities have a recurring password and do not use multifactor authentication (MFA).
    
* 10% of particulate logs (IdP) use a non-uniform password.
    

What does that mean? If the stolen accounts are valid, it is very likely that they will allow you to access not only one account, but also to several other services on which the same user is registered.

### Imagine this situation:

A recent data breach associated with infecting with infostlers or phishing attacks shows that a combination of a particular username and password works to access Microsoft 365.

However, this account is protected by multi-factor authentication (MFA) and has strict conditional access policies that limit the input over IP address and geolocation.

Previously, the attack would have ended, and the attacker would switch to another target.

But what if it would be possible to use the same credential data for automatic search in all other business applications in which this user is registered?

#### Scaling of attacks with the selection of accounting data using Computer-Using Agents

To date, the impact of artificial intelligence on digital identities attacks has been limited to the use of large language models to create phishing emails, the development of malware with support for artificial intelligence, and automating attacks on social media. Of course, these are significant factors, but they have not led to radical changes and still require constant human participation.

However, with the advent of OpenAI Operator – specialized Computer-Using Agent – the situation may change. Operator is trained on a specialized dataset and works in an isolated browser, allowing it to perform typical web tasks in the same way as a person does – see and interact with pages.

Unlike other automated solutions, Operator does not require custom integration or writing code to work with new sites, making it a much more scalable tool for intruders seeking to attack a wide range of sites and applications.

Researchers at Push Security tested the potential malign use of Operator, checking its capabilities for:

* Definitions of which companies have active tenants in certain applications.
    
* Attempts to log in to different corporate SaaS applications with usernames and passwords provided.
    

### Brief summary of impact

The results were impressive. Operator has clearly demonstrated the ability to target various applications using stolen accounts and perform actions within the applications themselves. Now imagine that this opportunity is scaled in 10, 100, 10 000 times...

These tasks do not require high complexity. However, the key value of CUA (Computer-Using Agents) such as Operator is not the complexity, but on a scale. Imagine that you can control the Operator windows through the API and run these processes simultaneously and in a huge amount (similar to existing API tools for ChatGPT).

But the problem is much broader than just Operator – we are talking about a technological trend. OpenAI can impose restrictions: improved protection mechanisms, limits on the number of tasks performed simultaneously and total operating time.

But it can be guaranteed that Operator will not remain the only CUA agent. The only question is in time when similar solutions will appear, perhaps even originally designed for malicious purposes, using the same technology.

#### Final thoughts

CUA technology is still at an early stage of development, but it is already obvious that this particular type of automation based on artificial intelligence can significantly exacerbate the already serious problem of cybersecurity. The ability to attack a wide range of applications previously went beyond traditional automation, but now it is becoming much more accessible even for inexperienced intruders (the new generation of script-kiddi?).

In other words, this actually gives the attacker “state” low-skilled trainees who do not fully understand what they are doing, but can perform specific, clearly spelled out tasks on a mass scale, demanding only minimal control. So it’s like managing a Red Team-style AI Bots.

Operator allows attackers to use compromised accounting data on a massive scale, exploit a huge number of vulnerable and incorrectly empathetic digital identities, simplifying their compromise. In a way, this can return attacks with the selection of credentials to the times before the mass transition to cloud applications, when attackers could reassemble thousands of accounts over their targets without having to develop custom solutions for each attack.

Fortunately, defense does not require fundamentally new AI protection technologies, but more than ever it is important for organizations to focus on protecting their digital identities, identifying vulnerabilities and eliminating them before attackers can use them.  
  
———————————————————————————————————————-