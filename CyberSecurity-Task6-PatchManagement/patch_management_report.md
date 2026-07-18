# Task 6 - Research Report: The Importance of Patch Management

## Objective

This research report discusses the concept of patch management, the significance of patch management in protecting information systems from threats, and the ways through which organisations can develop a successful patch management plan.

# Table of Contents

1. Introduction
2. Why Patches Matter
3. Consequences of Not Patching
4. Patch Management Lifecycle
5. Best Practices
6. Challenges and Solutions
7. Conclusion
8. References

# 1. Introduction

Patch management is a term used to describe the practice of identifying, testing, installing, and validating software updates provided by software vendors. Patches help to fix any security vulnerabilities, improve software performance and also include additional features.

Patch management plays a very important role in the life cycle of vulnerabilities. Whenever security researchers discover a vulnerability in a particular piece of software, the vendor is notified, and a CVE number is assigned. After this, the vendor provides a patch to resolve this problem. When organizations do not install the patches in time, hackers have the opportunity to exploit the vulnerability and penetrate the system. Consequently, maintaining software is a very simple and effective way to increase cybersecurity.


# 2. Importance of Patches

Software vulnerabilities are discovered on a regular basis by security researchers, ethical hackers, and developers of software. They get entered in the CVE (Common Vulnerabilities and Exposures) database and also receive their respective CVSS (Common Vulnerability Scoring System) scores. Software vendors produce patches to get rid of vulnerabilities before they are exploited by the them.

Sadly, many companies tend to put off updating their systems due to compatibility issues or simply downtime. In doing this, hackers get enough time to attack their systems.

## Example #1: WannaCry Ransomware Attack (2017)

WannaCry ransomware attacked more than 200,000 computers in more than 150 countries. Attackers used EternalBlue vulnerability in Microsoft Windows. Microsoft had already issued the patch for this system, but not all organizations have updated their systems. Hospitals, businesses, and even government agencies faced significant disruption of services.

## Example #2: Equifax Data Breach (2017)

Equifax data breach occurred due to an attack on an unpatched Apache Struts system. Nearly 147 million people became victims as their information like name, Social Security number, and financial information were stolen.

# 3. Implications of Non-Patching

There are a number of implications that can arise due to the lack of security patches:

- Security breaches involving the disclosure of sensitive customer and company data.
- Ransomware attacks that will encrypt files and cause interruptions in business activities.
- Legal and regulatory non-compliance that could entail litigation and regulatory penalties.
- Losses associated with expenses related to recovery, downtime, and compensation of customers.
- Impact on the reputation of the company and its relationships with customers.

Based on the Cost of a Data Breach Report by IBM, on average, a data breach can cost more than USD 4 million.


# 4. Patch Management Lifecycle

Patch management lifecycle involves the following steps:

## 4.1 Discovery

Determining the computers, servers, software applications, operating systems, and network devices that need updates.

## 4.2 Assessment

Analysing the newly released patches and their potential threats by assessing the severity using CVSS scores.

## 4.3 Testing

Applying patches in a testing environment in order to ensure compatibility and proper operation.

## 4.4 Deployment

Deploy validated patches to production environments through automation or manual means.

## 4.5 Verification

Ensure patches have been successfully deployed and conduct vulnerability scanning to keep the system secured.


# 5. Best Practices

## Prioritised 7-Step Patch Management Framework

1. Develop and maintain an accurate hardware/software inventory list.
2. Keep track of vendor announcements regarding new patches.
3. Evaluate and prioritise critical vulnerabilities according to their CVSS scores.
4. Test updates prior to deployment in the production environment.
5. Utilise automation in deployment of patches where possible.
6. Validate successful installation and keep a record of patches.
7. Conduct continuous monitoring and regularly assess vulnerabilities.


# 6. Challenges and Solutions

| Challenge | Solution |
|-----------|----------|
| Legacy systems are not compatible with contemporary patches. | Upgrade the systems or keep them isolated from important networks. |
| Patching might involve downtime. | Conduct the procedure during maintenance periods or after business hours. |
| Some patches might cause compatibility issues. | Test patches in a separate environment prior to deployment. |
| Huge companies have thousands of computers to manage. | Utilise automated patch management tools. |

# 7. Conclusion

The issue of patch management is crucial in cybersecurity. It is evident from cyber attacks like WannaCry and the Equifax incident that not applying software updates poses great risks. Companies and organisations that have a patch management system in place can minimise risks, stay compliant, and protect their clients. It goes without saying that patch management needs to be a vital part of any cybersecurity approach.


# 8. References

1. National Institute of Standards and Technology (NIST). https://www.nist.gov
2. NIST Special Publication 800-40 – Guide to Enterprise Patch Management Technologies. https://csrc.nist.gov
3. Cybersecurity and Infrastructure Security Agency (CISA). https://www.cisa.gov
4. CVE Program. https://www.cve.org
5. MITRE CVE Database. https://cve.mitre.org
6. IBM Cost of a Data Breach Report. https://www.ibm.com/reports/data-breach
