## 🚨 Cybersecurity Incident Report - DDoS Attack

### 📜 Project Description
This project presents an analysis of a security incident involving a DDoS (Distributed Denial of Service) attack on a multimedia company. The attack caused a significant disruption to the network, leading to a two-hour downtime. The goal was to assess how the cybersecurity team responded and identify areas for improvement following the NIST Cybersecurity Framework (CSF).

---

| **Action Phases**    | **Action Taken**                                                                                                 |
|----------------------|-------------------------------------------------------------------------------------------------------------------|
| **📋 Summary**        | The company suffered a DDoS attack where the internal network stopped responding due to a flood of incoming ICMP packets. This attack caused a disruption in normal network traffic and led to a two-hour downtime. The attack was traced back to a firewall misconfiguration, which allowed an attacker to overload the system. The cybersecurity team responded by blocking the malicious traffic, restoring critical services, and implementing additional protective measures. |
| **🧭 Identify**       | The network was suddenly overwhelmed by an influx of ICMP packets, causing a complete disruption of network services. All critical network resources were affected, and the immediate priority was to isolate the attack and begin restoring functionality to the most crucial services. The team quickly identified the vulnerability in the firewall configuration that allowed the DDoS attack to succeed. |
| **🛡️ Protect**        | The team implemented several protective measures for internal assets, including a new firewall rule to limit the rate of incoming ICMP packets, source IP address verification, and an IDS/IPS system to filter out suspicious traffic based on specific characteristics. |
| **🔍 Detect**         | Detection capabilities were enhanced by configuring network monitoring software to identify abnormal traffic patterns, as well as ensuring the firewall checked for spoofed IP addresses in incoming ICMP packets. |
| **⚡ Respond**         | The team responded by isolating affected systems to prevent further disruptions, restoring critical network services, and analyzing network logs for abnormal activity. All incidents were reported to upper management and, if applicable, to legal authorities. |
| **🔄 Recover**        | For recovery, the team restored network services to normal operation and implemented measures to block future ICMP flood attacks at the firewall. Non-critical services were brought back online once the ICMP flood subsided. |

<table>
  <tr>
    <th>📋 Summary</th>
    <td>The company suffered a DDoS attack where the internal network stopped responding due to a flood of incoming ICMP packets. This attack caused a disruption in normal network traffic and led to a two-hour downtime. The attack was traced back to a firewall misconfiguration, which allowed an attacker to overload the system. The cybersecurity team responded by blocking the malicious traffic, restoring critical services, and implementing additional protective measures.</td>
  </tr>
  <tr>
    <th>🧭 Identify</th>
    <td>The network was suddenly overwhelmed by an influx of ICMP packets, causing a complete disruption of network services. All critical network resources were affected, and the immediate priority was to isolate the attack and begin restoring functionality to the most crucial services. The team quickly identified the vulnerability in the firewall configuration that allowed the DDoS attack to succeed.</td>
  </tr>
  <tr>
    <th>🛡️ Protect</th>
    <td>The team implemented several protective measures for internal assets, including a new firewall rule to limit the rate of incoming ICMP packets, source IP address verification, and an IDS/IPS system to filter out suspicious traffic based on specific characteristics.</td>
  </tr>
  <tr>
    <th>🔍 Detect</th>
    <td>Detection capabilities were enhanced by configuring network monitoring software to identify abnormal traffic patterns, as well as ensuring the firewall checked for spoofed IP addresses in incoming ICMP packets.</td>
  </tr>
  <tr>
    <th>⚡ Respond</th>
    <td>The team responded by isolating affected systems to prevent further disruptions, restoring critical network services, and analyzing network logs for abnormal activity. All incidents were reported to upper management and, if applicable, to legal authorities.</td>
  </tr>
  <tr>
    <th>🔄 Recover</th>
    <td>For recovery, the team restored network services to normal operation and implemented measures to block future ICMP flood attacks at the firewall. Non-critical services were brought back online once the ICMP flood subsided.</td>
  </tr>
</table>


<table>
  <tr>
    <th style="text-align: left; padding-right: 10px;">📋 Summary</th>
    <td>The company suffered a DDoS attack where the internal network stopped responding due to a flood of incoming ICMP packets. This attack caused a disruption in normal network traffic and led to a two-hour downtime. The attack was traced back to a firewall misconfiguration, which allowed an attacker to overload the system. The cybersecurity team responded by blocking the malicious traffic, restoring critical services, and implementing additional protective measures.</td>
  </tr>
  <tr>
    <th style="text-align: left; padding-right: 10px;">🧭 Identify</th>
    <td>The network was suddenly overwhelmed by an influx of ICMP packets, causing a complete disruption of network services. All critical network resources were affected, and the immediate priority was to isolate the attack and begin restoring functionality to the most crucial services. The team quickly identified the vulnerability in the firewall configuration that allowed the DDoS attack to succeed.</td>
  </tr>
  <tr>
    <th style="text-align: left; padding-right: 10px;">🛡️ Protect</th>
    <td>The team implemented several protective measures for internal assets, including a new firewall rule to limit the rate of incoming ICMP packets, source IP address verification, and an IDS/IPS system to filter out suspicious traffic based on specific characteristics.</td>
  </tr>
  <tr>
    <th style="text-align: left; padding-right: 10px;">🔍 Detect</th>
    <td>Detection capabilities were enhanced by configuring network monitoring software to identify abnormal traffic patterns, as well as ensuring the firewall checked for spoofed IP addresses in incoming ICMP packets.</td>
  </tr>
  <tr>
    <th style="text-align: left; padding-right: 10px;">⚡ Respond</th>
    <td>The team responded by isolating affected systems to prevent further disruptions, restoring critical network services, and analyzing network logs for abnormal activity. All incidents were reported to upper management and, if applicable, to legal authorities.</td>
  </tr>
  <tr>
    <th style="text-align: left; padding-right: 10px;">🔄 Recover</th>
    <td>For recovery, the team restored network services to normal operation and implemented measures to block future ICMP flood attacks at the firewall. Non-critical services were brought back online once the ICMP flood subsided.</td>
  </tr>
</table>



---

### 📝 Reflections/Notes:
- The firewall misconfiguration was a critical vulnerability that allowed the DDoS attack to succeed. Future audits should prioritize identifying and addressing such vulnerabilities to strengthen network security.
- The response was effective in restoring critical services, but a quicker isolation of the affected systems could have reduced downtime and prevented further disruption.
- Implementing continuous monitoring and regularly updating the security infrastructure are essential steps to detect future threats more rapidly and ensure faster response times.

---
