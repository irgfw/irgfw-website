---
title: "International Bandwidth and TLS Disruptions in Iran"
date: 2024-10-02
toc: false
---
---

In recent hours, noticeable changes in Iran's internet bandwidth and latency to foreign IPs have been observed. Overall, the speed and bandwidth of international connections have decreased, and latency has reached higher than usual.

These changes are primarily evident in TLS connections. IRGFW prevents prolonged TCP-TLS connections, causing them to experience disruptions or restrictions after a few minutes. However, immediately after establishing a new connection and completing the handshake process, the tunnel works correctly, only to face restrictions again after a few minutes. This issue does not affect all foreign IPs but is more prominent with well-known foreign data centers and CIDR ranges monitored by Iran's firewall.

It is difficult to say whether these changes have been implemented deliberately or are due to increased internet traffic load or even the use of Anti-DDoS systems in security-related scenarios. However, the restrictions on TCP-TLS connections seem more likely to result from specific firewall rules (either filtering or DDoS protection rules to prevent cyberattacks) rather than increased traffic load.

<br>

#### Explore
{{< cards >}}
  {{< card link="/blog" title="Posts" icon="annotation" >}}
  {{< card link="/projects" title="Projects" icon="document-text" >}}
  {{< card link="/contact" title="Contact" icon="at-symbol" >}}
{{< /cards >}}
