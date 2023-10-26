# Cybersecurity_UseNISTCSF

## Scenario

You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 
- A new firewall rule to limit the rate of incoming ICMP packets.
- Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets
- Network monitoring software to detect abnormal traffic patterns
- An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate through the different steps of analyzing this cybersecurity incident and integrate your analysis into a general security strategy:
- **Identify** security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security.
- **Protect** internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats.
- **Detect** potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections.
- **Respond** to contain, neutralize, and analyze security incidents; implement improvements to the security process.
- **Recover** affected systems to normal operation and restore systems data and/or assets that have been affected by an incident. 

## Tasks have been completed - step by step:
- [x] Review [incident report analysis template](https://github.com/binhnhu1409/Cybersecurity_UseNISTCSF/blob/main/Incident%20report%20analysis%20template.pdf) and read how to apply the [NIST CSF](https://github.com/binhnhu1409/Cybersecurity_UseNISTCSF/blob/main/Applying%20the%20NIST%20CSF%20.pdf) to the case
- [x] Write a summary of the incident into the [report](https://github.com/binhnhu1409/Cybersecurity_UseNISTCSF/blob/main/Incident%20report%20analysis.pdf)
- [x] Identifies the type of attack, including which devices or systems in the network were impacted by the security event. Put this information in the section titled "Identify" in the report.
- [x] Offers a plan to further protect the network from future incidents. Put this information in the section titled "Protect" in the report.
- [x] Determine methods for detecting security events in the future. Put this information in the section titled "Detect" in the report.
- [x] Create a response process for future cybersecurity incidents. Put this information in the section titled "Respond" in the report.
- [x] Lists procedures to recover from a similar security event. Put this information in the section titled "Recover" in the report.
