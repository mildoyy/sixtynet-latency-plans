# Low Latency VPS US West Coast: Los Angeles or Silicon Valley, How Many Milliseconds Can You Actually Feel, and Which SixtyNet Plan Do You Need? (All 12 Plans, Priced)

SixtyNet's US West Coast capacity sits in Los Angeles, and the cheapest plan on its pricing page that can serve a web page is **LAX-STARTER**: 2 cores, 2 GB RAM, 40 GB NVMe, 5 TB of traffic on a 2 Gbps port, listed at $240.00 USD, or $200.00 USD on the annual option. For a small site, an API, or a trading bot aimed at West Coast and Asia-Pacific users, that is the plan to buy. Move up to LAX-MICRO when 2 GB of RAM starts swapping.

One thing on that page needs saying before the table. Twelve plans are listed, and three of them are the identical 2-core / 2 GB / 40 GB box at three different prices with three different IP types. Two of those three block ports 80 and 443 by design, so the box that looks like a straightforward variant cannot serve a web page at all.

> **Quick verdict:** Hosting anything with a domain name: LAX-STARTER at $240.00 USD ($200.00 with annual billing), DDoS protection and 5 TB of traffic included. Need more RAM or disk: LAX-MICRO at $480.00. Choose the Residential or Irvine Pro lines only if you need a US consumer IP address for a specific purpose, and go in knowing 80 and 443 stay closed.
> 👉 [Check SixtyNet's current West Coast plan pricing](https://sixtynet.net/aff.php?aff=39)

## Every SixtyNet plan, sorted by price

Prices are the yearly rates SixtyNet lists, followed by the lower figure that appears next to the annual option. Every plan below runs on NVMe storage with a premium network port.

| Plan | Cores / RAM / NVMe | Port / traffic | Price (USD) | Notes | Order |
| --- | --- | --- | --- | --- | --- |
| LAX-STARTER | 2 / 2 GB / 40 GB | 2 Gbps / 5 TB | $240.00 · $200.00 annual | DDoS protection | [ LAX-STARTER pricing](https://sixtynet.net/aff.php?aff=39) |
| Residential-STARTER | 2 / 2 GB / 40 GB | 2 Gbps / 5 TB | $300.00 · $260.00 annual | Residential IP; 80 & 443 closed | [ Residential-STARTER pricing](https://sixtynet.net/aff.php?aff=39) |
| IRVINE-PRO-STARTER | 2 / 2 GB / 40 GB | 2 Gbps / 5 TB | $420.00 · $350.00 annual | AS9929 China routing, residential IP, scan lockdown | [ IRVINE-PRO-STARTER pricing](https://sixtynet.net/aff.php?aff=39) |
| LAX-MICRO | 4 / 4 GB / 80 GB | 4 Gbps / 10 TB | $480.00 · $400.00 annual | DDoS protection | [ LAX-MICRO pricing](https://sixtynet.net/aff.php?aff=39) |
| LAX-Storage-500G | 4 / 4 GB / 300 GB + 200 GB bonus, RAID 10 | 10 Gbps / 10 TB | $480.00 · $400.00 annual | DDoS protection | [ LAX-Storage-500G pricing](https://sixtynet.net/aff.php?aff=39) |
| Residential-MICRO | 4 / 4 GB / 80 GB | 4 Gbps / 10 TB | $540.00 · $460.00 annual | Residential IP; 80 & 443 closed | [ Residential-MICRO pricing](https://sixtynet.net/aff.php?aff=39) |
| LAX-Storage-1TB | 8 / 8 GB / 700 GB + 300 GB bonus, RAID 10 | 10 Gbps / 15 TB | $840.00 · $700.00 annual | DDoS protection | [ LAX-Storage-1TB pricing](https://sixtynet.net/aff.php?aff=39) |
| LAX-MEDIUM | 8 / 8 GB / 160 GB | 10 Gbps / 20 TB | $960.00 · $800.00 annual | DDoS protection | [ LAX-MEDIUM pricing](https://sixtynet.net/aff.php?aff=39) |
| Residential-MEDIUM | 8 / 8 GB / 160 GB | 10 Gbps / 20 TB | $1,020.00 · $860.00 annual | Residential IP; 80 & 443 closed | [ Residential-MEDIUM pricing](https://sixtynet.net/aff.php?aff=39) |
| LAX-LARGE | 8 / 16 GB / 320 GB | 10 Gbps / 40 TB | $1,920.00 · $1,600.00 annual | DDoS protection | [ LAX-LARGE pricing](https://sixtynet.net/aff.php?aff=39) |
| Residential-LARGE | 16 / 16 GB / 320 GB | 10 Gbps / 40 TB | $1,980.00 · $1,660.00 annual | Residential IP; 80 & 443 closed | [ Residential-LARGE pricing](https://sixtynet.net/aff.php?aff=39) |
| Los Angeles China Unicom-Premium | Bandwidth product, not a per-core VPS tier | 100 Mbps, 3× burst, 95th percentile | $3,000.00 · $2,500.00 annual | AS9929, free BGP session | [ China Unicom-Premium pricing](https://sixtynet.net/aff.php?aff=39) |

Two anomalies in that list are worth catching before you pick. **LAX-LARGE keeps 8 cores**, the same count as LAX-MEDIUM, and doubles only the RAM and traffic while doubling the price; if you need more CPU on the LAX line, there is no tier above it. Meanwhile **Residential-LARGE has 16 cores** for $60 more than LAX-LARGE, which is the better CPU buy only if you can live with the blocked ports. The Irvine Pro line also shows a second tier (4 cores / 4 GB / 80 GB / 10 TB) below Starter without a price attached in the version of the page I checked, so look for it there if you want the Irvine route.

## Three lines, one box, three prices: which one can host a site?

The clearest way to read SixtyNet's catalogue is by IP type, not by size. Take the entry tier:

|  | LAX-STARTER | Residential-STARTER | IRVINE-PRO-STARTER |
| --- | --- | --- | --- |
| Specs | 2 cores / 2 GB / 40 GB NVMe / 2 Gbps / 5 TB | Same | Same |
| IP type | Datacenter IP with DDoS protection | US residential ISP IP | US residential ISP IP |
| Ports 80 & 443 | Open | **Blocked** | **Blocked** |
| Routing | Standard premium | Standard premium | AS9929 optimised for China |
| Extras | DDoS filtering | None listed | Rejects all external probes and scans |
| Price | $240.00 · $200.00 annual | $300.00 · $260.00 annual | $420.00 · $350.00 annual |

Identical hardware, $180 spread. The residential IP costs $60 more than the datacenter one, and the AS9929 China route costs another $120 on top.

The blocked ports decide the use case. A residential IP is a consumer address, useful when a service needs to see a real household connection: streaming unlocks, marketplace and ad accounts, region-restricted apps. SixtyNet's own note says ports 80 and 443 stay closed for IP risk-control reasons, which means no public website, no HTTP API behind a domain, no Let's Encrypt HTTP validation on the default port. Run a personal VPN, a scraper, an automation bot, or a media box on it and the block is irrelevant. Try to host WordPress on it and you will spend an evening learning why it doesn't load.

Irvine Pro adds a second restriction. The product description says it rejects all external probes and scans, so access is limited to whitelisted or port-forwarded devices. That is a deliberate security posture for people who want the box invisible. It also comes with the only refund term stated anywhere on the page, and it is narrower than you might expect: the refund is valid on website balance only, not back to your card. Third-party reviews of the Astound and Cox residential boxes published in October 2025 also reported IPv6 unsupported and ICMP ping blocked, so treat these as IPv4-only machines unless the page says otherwise.

The China Unicom-Premium row is a different product wearing the same label. It is a 100 Mbps port with 3× burst billed on 95th percentile, a free BGP session, and limited BGP support, priced for people who need to announce their own address space over AS9929 rather than rent another virtual machine.

## What 1–5 ms actually buys you on a low latency VPS in the US West Coast

Every millisecond figure in this market comes from the provider, not from an independent test, so treat them as engineering claims. BrainHost, which runs in Los Angeles, publishes 1–5 ms to California, Oregon, Washington, Nevada and Arizona, about 67 ms to the US East Coast, and 112–160 ms to Asia over trans-Pacific cables. NetGrid Host advertises a "5.0 ms regional latency" without saying measured from where. Cloudfanatic and Liquid Web publish no numbers at all.

The bands matter more than the exact figure:

- **1–5 ms** is a same-metro number. Anything in this band is indistinguishable in a browser, and a 3 ms provider is not meaningfully better than an 8 ms one.
- **10–40 ms** covers interstate traffic within the western states. Page loads still feel instant.
- **60–70 ms** is coast to coast. A single request is fine; twenty sequential database round trips turn into 1.3 seconds instead of 0.1.
- **100 ms+** is transpacific. Cached pages survive it, chatty protocols and interactive sessions do not.

Latency compounds per round trip, which is the only real argument for picking a city rather than a spec sheet. A $240 box in Los Angeles with five sequential calls to a database on the same machine beats a faster box in Chicago every time.

One number that does not belong in this discussion: port speed. A 10 Gbps port is a throughput ceiling for concurrent transfers. It does not lower ping. SixtyNet's LAX line starts at 2 Gbps and climbs to 10 Gbps, and that upgrade buys you parallel downloads, backups and traffic spikes, not a faster reply to a single request.

## Los Angeles, Irvine, Silicon Valley, Phoenix: where the box sits matters more than the spec sheet

Inside SixtyNet the choice is Los Angeles or Irvine, roughly 50 km apart in the same metro. Both give you the same regional profile: single-digit milliseconds across Southern California, and the shortest US route to Asia. Pick LAX for standard hosting and Irvine for AS9929 China routing. There is no measurable latency reason to prefer one over the other.

Against other locations the differences are real but smaller than the marketing suggests:

- **Silicon Valley** (LightNode's location) is around 500 km north. Slightly better for Seattle and the Bay Area, slightly worse for San Diego, effectively identical for Tokyo or Sydney.
- **Phoenix** is inland, about 600 km from the coast. Fine for Arizona and Southern California, weaker than LA for Asia-Pacific traffic, and it is not a West Coast location despite appearing in "US West" listings. Liquid Web's western presence is Phoenix, not California.
- **Chicago, Dallas, Michigan** are cross-country from the West Coast. Fine for a national audience, wrong if your users are concentrated in California.

The case against a West Coast box is worth stating plainly: if your users are in Europe or the US East Coast, hosting in Los Angeles adds 60 to 100 ms to every round trip and you should put the server closer to them. Likewise, an audience mostly in Japan or Korea gets 10–30 ms from a Tokyo node and 100 ms+ from Los Angeles. LA is the right compromise for a split US/APAC audience, not the fastest option for either side.

## How SixtyNet compares on price

Competitor figures below are as published on each provider's own page. Billing periods differ, so compare the specs and terms rather than the headline number.

| Provider | Location | Entry price | Billing | What that entry price covers |
| --- | --- | --- | --- | --- |
| SixtyNet | Los Angeles, Irvine | $240.00 USD ($200.00 annual) | Yearly, 13–17% off for annual payment | 2 cores / 2 GB / 40 GB NVMe / 5 TB / 2 Gbps |
| LightNode | Silicon Valley | $21.2 USD/month | Hourly or monthly, switchable on the same instance | 1 vCPU / 2 GB / 50 GB NVMe / 1 TB; four tiers to $158.7 |
| BrainHost | Los Angeles | $7.99 USD/month | Monthly | 10 Gbps port, 1–5 ms West Coast claim, 99.9% SLA |
| Cloudfanatic | Los Angeles | $2.99 USD/month | Monthly | 1 vCPU / 1 GB / 30 GB NVMe, 1 Gbit port (page dated May 2025) |
| NetGrid Host | Los Angeles | €2.98/month | Monthly | 1 core / 1 GB / 10 GB NVMe, 1 Gbps, unlimited transfer (euro pricing) |
| Liquid Web | Michigan, Phoenix | $11 USD/month | Monthly | Cloud VPS; no West Coast data centre (page dated March 2025) |

Two caveats on that table. Cloudfanatic's 10 Gbps line lists Chicago as the only location in its plan selector despite the page being an LA page, so don't count it as a Los Angeles option without checking. And the Cloudfanatic and Liquid Web prices are around eighteen months old at the time of writing, so verify them before using either as a benchmark.

SixtyNet's position is the traffic allowance and the port. Five terabytes and 2 Gbps at the entry tier is a lot of room compared with a 1 TB allowance, and the LAX line includes DDoS filtering rather than selling it separately.

## FAQ

**Will a West Coast server make my site faster for users in Asia?**
Faster than the East Coast or Europe, yes: Los Angeles is the shortest US route across the Pacific, with published figures around 112–160 ms. Faster than an Asian server, no. If most of your traffic is in Japan, Korea or China, host in Asia, or use one of SixtyNet's China-optimised products if the China route is the specific problem.

**Does a 10 Gbps port reduce ping?**
No. Port speed caps throughput for concurrent transfers. A 10 Gbps port with 65 ms of round-trip time still answers in 65 ms. Buy bandwidth for volume, not for responsiveness.

**Can I run WordPress on the cheapest plan?**
On LAX-STARTER, yes: ports 80 and 443 are open, DDoS protection is included, and 2 cores with 2 GB of RAM handles a small site. On Residential-STARTER, no. Cheaper specs are not the issue there; the blocked ports are.

**Should I pay monthly or annually?**
Every plan on the page shows a 13–17% reduction for annual payment. Whether that discount repeats on renewal is not stated, so confirm it before committing a year.

**What is the refund policy?**
The only refund term visible on the pricing page applies to Irvine Pro, and it returns funds to your site balance rather than your payment method. Nothing is stated for the LAX or Residential lines, and no trial is advertised. Ask before you pay.

**Do these plans support Windows or IPv6?**
Neither is documented on the pricing page. Independent reviews of the residential boxes published in October 2025 reported no IPv6 and blocked ICMP, so assume Linux and IPv4 unless SixtyNet confirms otherwise for the specific plan.

## Which plan to buy

Match the line to the job first, then the size:

- **A website, API, or bot that answers on port 80 or 443** → LAX-STARTER at $240.00, or LAX-MICRO at $480.00 once 2 GB of RAM is the bottleneck. Storage-heavy work goes to LAX-Storage-500G at the same $480.00 with 500 GB of RAID 10 disk and a 10 Gbps port.
- **A US consumer IP for streaming, marketplace, or account work, with no public website** → Residential-STARTER at $300.00. Step up only when you need more traffic; the port and RAM scale together.
- **The same, but with China-optimised return routing** → IRVINE-PRO-STARTER at $420.00, accepting the scan lockdown and the balance-only refund.
- **Your own BGP announcement over AS9929** → the China Unicom-Premium product at $3,000.00.

Two things to settle before you enter card details: which billing cycle the listed price refers to and whether the annual discount recurs on renewal, and what the refund terms are for the specific line you chose. Both answers change the real cost of year two.

👉 [Compare all SixtyNet West Coast plans and current pricing](https://sixtynet.net/aff.php?aff=39)
