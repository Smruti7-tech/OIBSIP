# Task 4 - Research Report: Common Network Security Threats

## Objective

This report explains common network security threats, how they work, their real-world impact, and methods to prevent them.

## Table of Contents

* Introduction
* DoS/DDoS Attacks
* Man-in-the-Middle (MITM) Attacks
* IP Spoofing
* DNS Poisoning/Spoofing
* Comparison Table
* Conclusion
* References

## INTRODUCTION

Computer netwoks play an important role in our lives and have become one of the biggest challenges in todays digital world.Networks are esstial for Schools,hospitals and even who uses the networks simultaneously so we can communicate,store data and access online services.As technology continues to grow so there are increasing in cyber threats are also becoming more common ans advanced. There are threats such as DoS/DDoS,Man-in-the-Middle(MITM),IP spoofing and DNS poisoning can lead to disruption services,steal sensitive content or cause financial and reputational damage.So understanding these threats and learning how to prevent them is essential for keeps our system secure and protecting valuable data.

## DoS/DDoS Attacks

A Denial of Service(DoS) attack is a type of cyberattack that tries to make websites or any online service unreachable y sending a huge amount of fake traffic. Now a Distributed Denial-of-Service(DDos) this is also a similar way of attack but it's carried out using many infected devices from different locations because the traffic comes from multiple sources so DDoS attacks are much harder to stop.

### Real-World Example

A recent attack happens by Mirai Botnet on DNS service provider Dyn in 2016.That attack affected in popular websites like Twitter,Netflix,Spotify and Reddit that go offline for several hours and affecting millions of users around the world.

### IMPACT

1.Makes website and online services unavailable.

2.Disrupts in business activities leads to financial losses.

3.That cause negative impact on customer trust and organization reputation.

### Mitigation Strategies

1.Use DDoS protection services and CDNs to absorb large amounts of traffic.

2.Implement firewalls and intrusion prevention to protect against the malicious attacks.

3.Continuously montior the traffic and implement rate limiting.

## Man-in-the-Middle(MITM)Attacks

The Man-in-the-Middle(MITM) attack involves cybercriminals inserting to the communcation between two parties without their knowledge.The criminal is capable of monitoring,stealing or modify the data being exchanged.These attacks are more common on unsecured public wi-fi networks or fake websites.

### Real-World Example

The most famous would be the Firesheep attack in 2010.Which showed how easy it was for attackers on the same public wi-fi network to take over other people online sessions.This way hackers were able to get access to other peoples accounts without knowing the password to them.

### Impact

1.Personal information like usernames,passwords and bank details can be stolen.

2.Accesing private information and confidential data may be exposed.

3.Victims may suffer financial loss,identity theft or lose trust in online services.

### Mitigation Strategies

1.Use only websites with HTTPS encryption.

2.Try not to use any sensitive services on a public wifi network so use a trusted VPN.

3.Turn on Multi-Factor Authentication for extra account protection.

## IP Spoofing

IP Spoofing is a method used by attackers to hide their real identity by changing the source IP address of a data packet. Because of this, the traffic appears to come from a trusted device instead of the attacker. This technique is often used to bypass security systems or to support other cyberattacks.

### Real-World Example

IP spoofing has been used in several DDoS attacks where attackers disguise the source of malicious traffic. This makes it much harder for security teams to trace the attack back to its real origin.

### Impact

* Makes it difficult to identify the actual attacker.
* Can help attackers bypass security checks.
* May lead to network disruption and unauthorized access.
* Can be used along with other attacks, such as DDoS.

### Mitigation Strategies

* Configure firewalls and routers to filter suspicious IP addresses.
* Monitor network traffic regularly to detect unusual activity.
* Use ingress and egress filtering to verify that network packets come from legitimate sources.

## DNS Poisoning/Spoofing

DNS Poisoning, also known as DNS Spoofing, is a cyberattack where hackers change DNS information so that users are sent to a fake website instead of the real one. Most people don't notice because the fake website looks very similar to the original. Attackers use this trick to steal usernames, passwords, and other personal information.

### Real-World Example

In 2019, a cyberattack known as Sea Turtle targeted several organizations by changing DNS records. Instead of reaching the real websites, users were redirected to fake pages where attackers tried to collect sensitive information.

### Impact

* Users can unknowingly enter their details on fake websites.
* Personal and financial information may be stolen.
* Organizations can lose customer trust and face financial losses.

### Mitigation Strategies

* Enable DNSSEC to make DNS responses more secure.
* Keep DNS servers and network devices updated.
* Use trusted DNS services and always check the website address before entering sensitive information.

## Comparison Table

| Threat        | Attack Vector                                              | Who Is at Risk                            | Difficulty to Execute | Ease of Mitigation |
| ------------- | ---------------------------------------------------------- | ----------------------------------------- | --------------------- | ------------------ |
| DoS/DDoS      | Flooding a server or network with excessive traffic        | Businesses, websites, and online services | Medium to High        | Medium             |
| MITM          | Intercepting communication between two parties             | Anyone using unsecured networks           | Medium                | High               |
| IP Spoofing   | Sending packets with a fake IP address                     | Organizations and network users           | Medium                | Medium             |
| DNS Poisoning | Redirecting users to fake websites by altering DNS records | Internet users and organizations          | High                  | Medium             |

## Conclusion

Network security attacks have become more sophisticated owing to the advancement in technology. Network security attacks include DDoS/DoS attacks, MitM attack, IP spoofing, and DNS poisoning, among others, which can create security hazards to a network if not properly addressed. Awareness on such attacks is critical since one will be able to know the potential dangers and take adequate measures.

### Key Points

* Knowledge on common network attacks assists in preventing security incidences.
* Security measures such as firewalls, encryption, DNSSEC, and MFA are very vital in securing networks.
* Updates and monitoring are very important in ensuring network security.

## References

* National Institute of Standards and Technology (NIST). https://www.nist.gov
* Cybersecurity and Infrastructure Security Agency (CISA). https://www.cisa.gov
* MITRE ATT&CK Framework. https://attack.mitre.org
* SANS Institute Reading Room. https://www.sans.org/reading-room
* Krebs on Security. https://krebsonsecurity.com
