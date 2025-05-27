# Cybersecurity-
With a strong background in Computer Science from Delta State Polytechnic Nigeria, I am excited to launch my career in cybersecurity. My interests in content creation, graphics, and technology have prepared me to tackle the challenges of this field. While I am new to cybersecurity, my certification and passion for technology position me well for an entry-level role. I am eager to apply my skills, learn from experienced professionals, and contribute to the security and innovation of digital assets.




---

Portfolio Incident Report: DDoS Attack Response Using NIST CSF

Analyst Role: Cybersecurity Analyst
Organization: Multimedia Company (Web Design, Graphic Design, Social Media Marketing)
Incident: Distributed Denial of Service (DDoS) Attack
Impact: Internal network compromised for two hours


---

1. Identify (ID) – Identify Security Risks

Risk Assessment:
Conducted an audit and discovered an unconfigured firewall rule that allowed unrestricted ICMP traffic into the internal network.

Asset Management:
Mapped critical systems including internal servers used for web hosting and internal file sharing.

Vulnerability Management:
Recognized that lack of firewall configuration left the network exposed to ICMP flooding attacks.

Governance:
Determined a gap in oversight of firewall rules and change management procedures.

Recommendations:

Schedule quarterly internal network audits.

Implement automated vulnerability scanning tools.

Enforce change management policies for firewall and network rule modifications.




---

2. Protect (PR) – Safeguard Internal Assets

Access Control:
Verified and adjusted access privileges to ensure only authorized personnel can modify firewall settings.

Awareness and Training:
Initiated internal training for the IT team on DDoS mitigation and proper firewall configuration.

Data Security:
Reviewed network segmentation to isolate critical services from general internal traffic.

Protective Technology:
Implemented a firewall rule to limit the rate of incoming ICMP packets and verify source IP addresses to mitigate spoofing.

Recommendations:

Formalize network security policies.

Install configuration management systems to track changes.

Review firewall rules monthly.




---

3. Detect (DE) – Enhance Detection Capabilities

Anomalies and Events:
Integrated network monitoring software to detect abnormal traffic patterns.

Security Continuous Monitoring:
Deployed an IDS/IPS system to flag and potentially block suspicious ICMP traffic.

Detection Processes:
Created and tested detection runbooks for DDoS attacks and abnormal ICMP traffic.

Recommendations:

Use behavioral analytics to detect outlier network activity.

Enable alerting thresholds for ICMP traffic volumes.

Regularly test detection systems with simulated traffic anomalies.




---

4. Respond (RS) – Incident Response and Containment

Response Planning:
Followed the incident response plan to stop non-critical services and block ICMP packets.

Analysis:
Conducted a root cause analysis identifying the attack entry point via the misconfigured firewall.

Mitigation:
Blocked ICMP packets and restored critical services; added source verification and traffic limiting controls.

Improvements:
Documented the incident, updated the response plan, and improved firewall configuration standards.

Recommendations:

Run regular tabletop exercises simulating DDoS attacks.

Assign roles and responsibilities clearly in the IR plan.

Archive logs for forensic analysis and pattern identification.




---

5. Recover (RC) – Return to Normal Operations

Recovery Planning:
Restored network services in a phased manner after ensuring attack traffic had ceased.

Improvements:
Added redundancy in network routes and reinforced firewall controls to prevent similar future incidents.

Communications:
Notified internal stakeholders of the incident and outlined steps taken to prevent recurrence.

Recommendations:

Implement a disaster recovery plan (DRP) specific to network-based attacks.

Establish backup communication channels for stakeholders during network disruptions.

Monitor post-recovery for potential residual threats.




---

Conclusion

Using the NIST CSF, this report outlines the organization's proactive steps to identify, protect, detect, respond, and recover from a DDoS attack. Continued adherence to these practices will strengthen the organization’s cybersecurity posture and improve resilience against future attacks.


---

