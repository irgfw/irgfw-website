---
title: "IRGFW QUIC Protocol Update"
date: 2024-07-27
toc: false
---
---

Since last night _(UTC+3:30)_, according to [CloudFlare Radar](https://radar.cloudflare.com/adoption-and-usage/ir?dateStart=2024-07-21&dateEnd=2024-07-28), QUIC protocol traffic to this datacenter has dropped by approximately half.

In general, the status of the QUIC protocol in Iran is highly fragmented and unstable. In some datacenters and even certain IP ranges, the protocol is either completely blocked, entirely accessible, or disrupted _(e.g., low upload speeds or high jitter)_. Although the protocol was re-enabled in Iran about two years ago following significant efforts by organizations and advocates in this field _(prior to which it was entirely blocked)_, it can now be described as "nominally" open. However, in most datacenters, it remains either disrupted or completely inaccessible. This instability degrades network service quality and leads to an inconsistent user experience for end-users.

Approximately ten days ago, China imposed severe restrictions on the UDP protocol. Chinese users attribute these restrictions to the widespread use of tools like Hysteria2 and the QUIC protocol to bypass the Great Firewall. The Chinese government's measures aim to exert greater control over network traffic and prevent hidden or unauthorized traffic from passing through these protocols. These developments indicate an increasing trend toward employing more sophisticated filtering and deep packet inspection (DPI) techniques in network management.

On the other hand, this also suggests that the authorities have not yet fully mastered identifying QUIC-based bypass methods. Instead of targeting a single protocol for blocking or disruption, they resort to broadly blocking or disrupting QUIC or even UDP entirely.

While QUIC and UDP can provide better performance and speed than TCP-based proxies or VPNs when accessible, it is not advisable to rely solely on UDP for bypassing firewalls. These protocols can be used effectively as long as they remain unblocked, but it is essential to maintain TCP-based methods as a fallback.

During critical or high-security periods, UDP and all protocols based on it are typically the first to be completely blocked.

Cloudflare Radar:
![IRGFW-CF-QUIC](https://github.com/user-attachments/assets/1924f86d-e6ed-44c7-b0d7-f6365d85f2a2)


<br>

#### Explore

{{< cards >}}
  {{< card link="/blog" title="Posts" icon="annotation" >}}
  {{< card link="/contact" title="Contact" icon="at-symbol" >}}
{{< /cards >}}
