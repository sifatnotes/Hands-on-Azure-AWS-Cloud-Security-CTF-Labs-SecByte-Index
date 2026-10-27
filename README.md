# Hands-on-Azure-AWS-Cloud-Security-CTF-Labs-SecByte-Index
A curated catalog of practical cybersecurity CTF labs covering Microsoft Azure network security, Entra ID attack paths, VM hardening, and AWS penetration testing, CloudFormation, serverless, ECS security, and cloud incident response.
# Azure & AWS Cloud Infrastructure Security CTF Lab Collection

Welcome to the **Azure & AWS Cloud Infrastructure Security CTF Lab Collection**. This repository provides an organized, searchable catalog of practical cybersecurity labs and Capture The Flag (CTF) challenges hosted on Learn SecByte.

This catalog covers multi-cloud security disciplines across **Microsoft Azure** and **Amazon Web Services (AWS)**, including network security group design, Entra ID identity attack paths, VM access controls, AWS penetration testing, CloudFormation security, serverless trust boundaries, ECS container exposure, and cloud incident response.

---

## Lab Collection Index

### 1. Microsoft Azure Infrastructure & Identity Security
* **Azure Fundamentals for Cybersecurity Analysts**  
  *Lab Link:* [https://learn.secbyte.org/ctf/azure-fundamentals-for-cybersecurity-analysts](https://learn.secbyte.org/ctf/azure-fundamentals-for-cybersecurity-analysts)  
  *Focus:* Core Azure architecture, cloud tenant boundaries, resource management, logging baselines, and security analyst fundamentals.

* **Azure Network Security Fundamentals: Design, Detect, Defend**  
  *Lab Link:* [https://learn.secbyte.org/ctf/azure-network-security-fundamentals-design-detect-defend](https://learn.secbyte.org/ctf/azure-network-security-fundamentals-design-detect-defend)  
  *Focus:* Virtual Network (VNet) design, subnet isolation, VPN gateway security, traffic routing, and network threat detection.

* **Azure Network Security Groups: Designing, Testing, Defending**  
  *Lab Link:* [https://learn.secbyte.org/ctf/azure-network-security-groups-designing-testing-defending-cl](https://learn.secbyte.org/ctf/azure-network-security-groups-designing-testing-defending-cl)  
  *Focus:* Evaluating NSG inbound/outbound rules, application security groups (ASG), rule priority conflicts, and testing perimeter access.

* **Azure Virtual Machines: Secure Deployment, Access, Investigation**  
  *Lab Link:* [https://learn.secbyte.org/ctf/azure-virtual-machines-secure-deployment-access-investigatio](https://learn.secbyte.org/ctf/azure-virtual-machines-secure-deployment-access-investigatio)  
  *Focus:* Bastion host setup, Just-In-Time (JIT) VM access, disk encryption, extension safety, and compromised VM forensics.

* **Microsoft Entra ID Defender: Identity Access and Attack Paths**  
  *Lab Link:* [https://learn.secbyte.org/ctf/microsoft-entra-id-defender-identity-access-attack-paths](https://learn.secbyte.org/ctf/microsoft-entra-id-defender-identity-access-attack-paths)  
  *Focus:* Analyzing Entra ID (formerly Azure AD) identity attack paths, Conditional Access policies, tenant escalation, and Identity Protection alerts.

* **Azure Active Directory Defender: Identity Access and Attack Paths**  
  *Lab Link:* [https://learn.secbyte.org/ctf/azure-active-directory-defender-identity-access-and-attack-p](https://learn.secbyte.org/ctf/azure-active-directory-defender-identity-access-and-attack-p)  
  *Focus:* Investigating legacy protocol risks, OAuth application consents, service principal abuse, and credential harvesting in hybrid identity models.

### 2. Amazon Web Services (AWS) Security, Pentesting & Incident Response
* **AWS Security Assessment: Identity, Logging, Misconfiguration Hunting**  
  *Lab Link:* [https://learn.secbyte.org/ctf/aws-security-assessment-identity-logging-misconfiguration-hu](https://learn.secbyte.org/ctf/aws-security-assessment-identity-logging-misconfiguration-hu)  
  *Focus:* Auditing IAM policies, S3 bucket permissions, CloudTrail configurations, and hunting for cloud security posture misconfigurations.

* **AWS Pentesting: From Recon to Cloud Takeover**  
  *Lab Link:* [https://learn.secbyte.org/ctf/aws-pentesting-from-recon-to-cloud-takeover](https://learn.secbyte.org/ctf/aws-pentesting-from-recon-to-cloud-takeover)  
  *Focus:* Executing cloud reconnaissance, abusing SSRF via IMDSv1/v2, privilege escalation via IAM permissions, and full account takeover scenarios.

* **AWS Incident Response: Detect, Contain, Eradicate**  
  *Lab Link:* [https://learn.secbyte.org/ctf/aws-incident-response-detect-contain-eradicate-cloud](https://learn.secbyte.org/ctf/aws-incident-response-detect-contain-eradicate-cloud)  
  *Focus:* Responding to compromised access keys, GuardDuty alerts, automated isolation via Security Groups, and CloudTrail forensic investigation.

* **AWS CloudFormation Security: From Template Trust to Stack Control**  
  *Lab Link:* [https://learn.secbyte.org/ctf/aws-cloudformation-security-from-template-trust-to-stack-con](https://learn.secbyte.org/ctf/aws-cloudformation-security-from-template-trust-to-stack-con)  
  *Focus:* Securing Infrastructure as Code (IaC) templates, stack policy constraints, secret management in CloudFormation, and drift detection.

* **AWS Serverless Security: Trust Boundaries and Response**  
  *Lab Link:* [https://learn.secbyte.org/ctf/aws-serverless-security-trust-boundaries-response](https://learn.secbyte.org/ctf/aws-serverless-security-trust-boundaries-response)  
  *Focus:* Hardening AWS Lambda functions, API Gateway authorization, environment variable protection, and serverless runtime containment.

* **AWS ECS Security: Identity, Networking, and Container Exposure**  
  *Lab Link:* [https://learn.secbyte.org/ctf/aws-ecs-security-identity-networking-and-container-exposure](https://learn.secbyte.org/ctf/aws-ecs-security-identity-networking-and-container-exposure)  
  *Focus:* Auditing Elastic Container Service (ECS) task execution roles, Fargate network isolation, task definition security, and container exposure mitigation.

---

## Learning Path

### Path A: Azure Infrastructure & Identity Security
1. **Analyst Foundations:** Start with [Azure Fundamentals for Cybersecurity Analysts](https://learn.secbyte.org/ctf/azure-fundamentals-for-cybersecurity-analysts).
2. **Network & Host Isolation:** Hardened boundaries using [Azure Network Security Fundamentals](https://learn.secbyte.org/ctf/azure-network-security-fundamentals-design-detect-defend), [Azure Network Security Groups](https://learn.secbyte.org/ctf/azure-network-security-groups-designing-testing-defending-cl), and [Azure Virtual Machines](https://learn.secbyte.org/ctf/azure-virtual-machines-secure-deployment-access-investigatio).
3. **Identity Protection:** Master identity defense via [Microsoft Entra ID Defender](https://learn.secbyte.org/ctf/microsoft-entra-id-defender-identity-access-attack-paths) and [Azure Active Directory Defender](https://learn.secbyte.org/ctf/azure-active-directory-defender-identity-access-and-attack-p).

### Path B: AWS Cloud Security & Offensive Assessment
1. **Assessment & Infrastructure:** Begin with [AWS Security Assessment](https://learn.secbyte.org/ctf/aws-security-assessment-identity-logging-misconfiguration-hu) and [AWS CloudFormation Security](https://learn.secbyte.org/ctf/aws-cloudformation-security-from-template-trust-to-stack-con).
2. **Serverless & Containers:** Hardened cloud-native workloads via [AWS Serverless Security](https://learn.secbyte.org/ctf/aws-serverless-security-trust-boundaries-response) and [AWS ECS Security](https://learn.secbyte.org/ctf/aws-ecs-security-identity-networking-and-container-exposure).
3. **Offensive Exploitation & Response:** Practice cloud pentesting and defense via [AWS Pentesting: From Recon to Cloud Takeover](https://learn.secbyte.org/ctf/aws-pentesting-from-recon-to-cloud-takeover) and [AWS Incident Response](https://learn.secbyte.org/ctf/aws-incident-response-detect-contain-eradicate-cloud).

---

## How to Use the Labs

1. Select a practice scenario from the **Lab Collection Index**.
2. Click the corresponding link to launch the exercise environment directly on Learn SecByte.
3. Review scenario directives, instruction details, and target goals.
4. Conduct cloud security audits, exploit misconfigurations, or remediate network/identity policies to capture flags.

---

## Target Audience

* **Cloud Security Engineers:** Design secure multi-cloud architectures across AWS and Azure environments.
* **Penetration Testers & Red Teams:** Execute AWS and Azure reconnaissance, IAM privilege escalation, and account takeover scenarios.
* **SOC Analysts & Incident Responders:** Analyze CloudTrail and Azure audit logs, contain compromised resources, and remediate cloud incidents.
* **Cybersecurity Students:** Acquire practical, hands-on experience in cloud infrastructure security.

---

## Disclaimer

All lab links in this repository direct to official training environments hosted on Learn SecByte. These materials are provided strictly for educational purposes, defensive skill building, and authorized research. Unapproved testing against external cloud tenants is strictly prohibited.
