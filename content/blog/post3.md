---
title: "IRGFW Update"
date: 2024-09-11
toc: false
---
---

Since around 10 PM Iran time, there has been a major disruption in the infrastructure affecting some foreign data centers, including Akamai and Vultr. This disruption can be seen on [Arvancloud’s radar](https://arvancloud.lgbt) and also on [Mahsa’s radar](https://www.mahsaserver.com/radar/).

These disruptions are affecting both non-TLS and TLS connections. On some Iranian servers (with infrastructure firewalls), it’s not possible to establish any protocol connection to these foreign ranges. However, QUIC and UDP traffic seem to connect relatively well.

A few days ago, the main infrastructure firewall was updated, and it has become much stricter with foreign IPs. It doesn’t matter what protocol you use; after a few handshakes and a very small amount of data, foreign IPs are completely and fundamentally blocked.

Considering the upcoming anniversary of [Mahsa Amini](https://en.wikipedia.org/wiki/Death_of_Mahsa_Amini), this behaviour from Iran’s internet and firewalls is somewhat expected, and we are not in a normal or stable period.


**Cloudflare Radar:**
![Cloudflare-Radar](https://github.com/user-attachments/assets/4d690182-c93d-49fb-9a8f-567d1b61178b)

**MahsaServer Radar:**
![Mahsa-Radar](https://github.com/user-attachments/assets/69d2b853-d5cf-4903-b169-d828346e441b)

**ArvanCloud Radar:**
![Arvancloud-Radar](https://github.com/user-attachments/assets/705af567-334d-4f4a-ac7d-77a4beb4c226)


<br>

#### Explore
{{< cards >}}
  {{< card link="/blog" title="Posts" icon="annotation" >}}
  {{< card link="/projects" title="Projects" icon="document-text" >}}
  {{< card link="/contact" title="Contact" icon="at-symbol" >}}
{{< /cards >}}
