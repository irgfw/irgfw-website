---
title: "IRGFW Update"
date: 2024-08-07
---
---

Approximately three days ago, the firewalls of the Mobile Telecommunication Company of Iran (MCI) and Iran's Infrastructure Communications Company were updated, resulting in significant changes to their functionality. Instead of completely blocking subdomains, there is a noticeable increase in ping, handshake time, and jitter in HTTP and HTTPS connections. These changes are so impactful that they severely limit WebSocket and gRPC transports for connecting to Cloudflare's CDN or even direct international communications. Previously, the subdomains used in Host/SNI were entirely blocked and filtered, but now they are being throttled in speed and ping.

Earlier, changing the subdomain allowed continued use of the main domain. However, with this new update, the firewalls now restrict all domains equally, including .ir domains and other top-level domains, without distinction—even limiting the root domain.

One way to bypass these restrictions is by using the Fragment in tlshello. This method prevents Iranian firewalls from fully identifying and limiting the subdomain/domain. However, it's important to note that these techniques are not always reliable and may soon be detected and blocked by the firewalls again.


<br>

#### Explore

{{< cards >}}
  {{< card link="/blog" title="Posts" icon="annotation" >}}
  {{< card link="/contact" title="Contact" icon="at-symbol" >}}
{{< /cards >}}