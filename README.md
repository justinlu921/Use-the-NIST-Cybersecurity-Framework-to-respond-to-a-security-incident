# Use-the-NIST-Cybersecurity-Framework-to-respond-to-a-security-incident

Review the scenario below. Then complete the step-by-step instructions.

You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 

A new firewall rule to limit the rate of incoming ICMP packets

Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets

Network monitoring software to detect abnormal traffic patterns

An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate through the different steps of analyzing this cybersecurity event and integrate your analysis into a general security strategy. We have broken the analysis into different parts in the template below. You can explore them here:

Identify security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security. 

Protect internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats. 

Detect potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections. 

Respond to contain, neutralize, and analyze security incidents; implement improvements to the security process. 

Recover affected systems to normal operation and restore systems data and/or assets that have been affected by an incident. 

# Incident Report Analysis

Based on the scenario and the provided documents, here's a step-by-step plan to improve your company’s network security using the NIST Cybersecurity Framework (CSF).

### Summary
Your organization recently experienced a DDoS attack that compromised the internal network for two hours. The attack was mitigated by blocking incoming ICMP packets, stopping non-critical network services, and restoring critical network services. The investigation revealed the attack was due to a misconfigured firewall.

### Identify
**Identify security risks through regular audits:**
- **Audits of Internal Networks, Systems, Devices, and Access Privileges:**
  - Perform regular network security audits to identify potential vulnerabilities.
  - Maintain an inventory of hardware and software, including their configurations and updates.
  - Audit access privileges to ensure they align with the principle of least privilege.

### Protect
**Protect internal assets through policies, procedures, training, and tools:**
- **Implement Firewall and IDS/IPS:**
  - Ensure firewalls are correctly configured and regularly updated.
  - Implement IDS/IPS to monitor network traffic and detect suspicious activities.
- **Develop and Enforce Security Policies:**
  - Implement a policy to limit ICMP traffic and other potentially harmful protocols.
  - Establish multi-factor authentication (MFA) for accessing critical systems.
- **Training:**
  - Conduct regular cybersecurity awareness training for all employees.
  - Emphasize the importance of recognizing phishing attacks and proper handling of credentials.

### Detect
**Improve monitoring capabilities:**
- **Network Monitoring:**
  - Implement network monitoring software to detect abnormal traffic patterns.
  - Use Security Information and Event Management (SIEM) tools to aggregate and analyze logs for suspicious activities.
- **Regular Updates:**
  - Regularly update detection tools to recognize the latest threats and vulnerabilities.

### Respond
**Contain, neutralize, and analyze security incidents:**
- **Incident Response Plan:**
  - Develop and regularly update an incident response plan that outlines steps to contain and mitigate attacks.
  - Conduct regular drills to ensure the incident response team is prepared.
- **Communication:**
  - Establish clear communication channels for incident reporting and management.
  - Ensure all stakeholders are informed promptly and appropriately during and after an incident.
- **Post-Incident Analysis:**
  - Analyze incidents to understand their root causes and prevent future occurrences.
  - Document lessons learned and update policies and procedures accordingly.

### Recover
**Restore affected systems and data:**
- **Backup and Recovery:**
  - Maintain regular backups of critical data and systems.
  - Test recovery procedures to ensure they can restore operations quickly after an incident.
- **System Restoration:**
  - Restore systems to normal operation as quickly as possible.
  - Review and improve recovery plans based on lessons learned from each incident.

### Example Analysis

Using the format from the provided documents, here’s how the analysis looks when applied to this specific scenario:

#### Summary
A DDoS attack flooded the network with ICMP packets, causing a two-hour outage.

#### Identify
- **Audits**: Regular audits revealed an unconfigured firewall.
- **Risk Identification**: Identified the need for better firewall configuration and monitoring tools.

#### Protect
- **Firewall Rules**: Implemented new rules to limit ICMP packet rate.
- **Source IP Verification**: Configured firewall to verify source IP addresses.
- **Training**: Conducted training on firewall configuration and DDoS mitigation.

#### Detect
- **Network Monitoring**: Deployed network monitoring software.
- **IDS/IPS**: Implemented IDS/IPS to filter and detect suspicious ICMP traffic.

#### Respond
- **Incident Response**: Blocked ICMP packets, stopped non-critical services, restored critical services.
- **Communication**: Communicated with internal teams and documented the incident.
- **Post-Incident Analysis**: Analyzed the incident to identify gaps and improve the response plan.

#### Recover
- **Backup Restoration**: No data loss reported, so no need for data restoration.
- **Improvement**: Updated firewall configurations and incident response plans based on the analysis.

### Reflections/Notes
- **Continuous Improvement**: Regularly update the security framework to adapt to new threats.
- **Awareness**: Keep all employees informed about the latest security policies and threats.

By following this plan, your company can improve its network security posture and be better prepared to handle future incidents.
