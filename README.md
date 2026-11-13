# Cheap Singapore VPS: What $1.77 a Month Buys on JustHost, Which Plan Fits, and Where Budget Hosting Gets Expensive (Full Plan Table)

JustHost's smallest KVM VPS runs **$1.77 per month** if you pay for a year: 1 core, 1 GB RAM, 10 GB NVMe, and a 100 Mbit fair-share port. That is enough for a single low-traffic site, a proxy, a cron-driven script box, or a staging server. It is not enough for a WooCommerce store with a control panel, a database, and image uploads.

One detail to settle before the prices below mean anything. JustHost sells one VPS line with the location chosen at order time, so there is no separate "Singapore price list" on the page. A third-party test of JustHost's Tokyo node documents one-click data-center and IP switching after deployment, and a Trustpilot reviewer describes moving a server from Amsterdam to Helsinki to fix routing. Treat the plan prices below as the price of the hardware you configure, with Singapore as one of the locations you select, and confirm the Singapore total in the configurator before paying.

The rest of this page covers the full lineup, four cost traps that decide whether $1.77 stays $1.77, and what the same job costs at OVHcloud, Contabo, ByteVirt and LightNode.

> **Quick pick.** For one real website, take **Vega**: 2 cores, 4 GB RAM, 80 GB NVMe, 500 Mbit port, **$6.23/mo** on 12-month billing ($7.79 month-to-month). A single small site or a proxy fits **Arcturus** at $3.21. A disposable test box starts at **$1.77**, with a three-month minimum order on that tier.
>
> 👉 [See every JustHost VPS plan and the current 12-month price](https://justhost.asia/en/services/vps/tariffs?ref=196392)

## The full JustHost VPS lineup (KVM, IPv4 + IPv6, storage selectable)

Prices are as displayed on JustHost's price page. The lower figure is the rate when you prepay 12 months; the figure in brackets is the monthly rate shown alongside it.

| Plan | vCPU / RAM | NVMe | Port (fair-share) | 12-month price | Order |
| --- | --- | --- | --- | --- | --- |
| Sirius | 1 core / 1 GB | 20 GB | 300 Mbit | $2.25/mo ($2.81) | [Sirius](https://justhost.asia/en/services/vps/tariffs?ref=196392) |
| Arcturus | 1 core / 2 GB | 30 GB | 300 Mbit | $3.21/mo ($4.01) | [Arcturus](https://justhost.asia/en/services/vps/tariffs?ref=196392) |
| Alpha Centauri | 2 cores / 2 GB | 40 GB | 400 Mbit | $4.17/mo ($5.21) | [Alpha Centauri](https://justhost.asia/en/services/vps/tariffs?ref=196392) |
| Vega | 2 cores / 4 GB | 80 GB | 500 Mbit | $6.23/mo ($7.79) | [Vega](https://justhost.asia/en/services/vps/tariffs?ref=196392) |
| Capella | 4 cores / 4 GB | 120 GB | 750 Mbit | $8.49/mo ($10.61) | [Capella](https://justhost.asia/en/services/vps/tariffs?ref=196392) |
| Rigel | 4 cores / 8 GB | 200 GB | 750 Mbit | $12.96/mo ($16.20) | [Rigel](https://justhost.asia/en/services/vps/tariffs?ref=196392) |
| Antares | 5 cores / 8 GB | 300 GB | 750 Mbit | $15.36/mo ($19.20) | [Antares](https://justhost.asia/en/services/vps/tariffs?ref=196392) |
| Betelgeuse | 6 cores / 12 GB | 400 GB | 750 Mbit | $21.12/mo ($26.40) | [Betelgeuse](https://justhost.asia/en/services/vps/tariffs?ref=196392) |
| Altair | 8 cores / 24 GB | 600 GB | 750 Mbit | $37.92/mo ($47.40) | [Altair](https://justhost.asia/en/services/vps/tariffs?ref=196392) |

The configurator also carries an 8-core / 16 GB / 500 GB tier that didn't display a comparable price across the two JustHost pages I checked, so I left it out rather than quote a number I can't tie to a billing cycle.

**Three separate cheaper lines** sit below that table, and they are where the "$0.99 / $1.16" headline numbers come from.

| Line | Spec | Price | Order |
| --- | --- | --- | --- |
| New Star (special offer, 3-month minimum) | 1 core / 1 GB / 10 GB NVMe / 100 Mbit | $1.77/mo ($2.21) | [New Star](https://justhost.asia/en/services/vps/tariffs?ref=196392) |
| Double Star (special offer) | 2 cores / 2 GB / 20 GB NVMe / 200 Mbit | $3.28/mo ($4.11) | [Double Star](https://justhost.asia/en/services/vps/tariffs?ref=196392) |
| Bright Star (special offer) | 4 cores / 4 GB / 30 GB NVMe / 300 Mbit | $4.54/mo ($5.68) | [Bright Star](https://justhost.asia/en/services/vps/tariffs?ref=196392) |
| HDD VPS Start | 1 core / 512 MB / 5 GB HDD | $2.60/mo ($3.25) | [HDD Start](https://justhost.asia/en/vps?ref=196392) |
| SSD VPS Start+ | 1 core / 512 MB / 5 GB SSD | $3.12/mo ($3.90) | [SSD Start+](https://justhost.asia/en/vps?ref=196392) |
| NVMe VPS Start++ | 1 core / 512 MB / 5 GB NVMe | $3.38/mo ($4.22) | [NVMe Start++](https://justhost.asia/en/vps?ref=196392) |
| HDD VPS Standard | 2 cores / 2 GB / 25 GB HDD | $8.80/mo ($11.00) | [HDD Standard](https://justhost.asia/en/vps?ref=196392) |
| SSD VPS Standard+ | 2 cores / 2 GB / 25 GB SSD | $10.56/mo ($13.20) | [SSD Standard+](https://justhost.asia/en/vps?ref=196392) |
| NVMe VPS Standard++ | 2 cores / 2 GB / 25 GB NVMe | $11.44/mo ($14.30) | [NVMe Standard++](https://justhost.asia/en/vps?ref=196392) |
| HDD VPS Super | 4 cores / 4 GB / 50 GB HDD | $17.60/mo ($22.00) | [HDD Super](https://justhost.asia/en/vps?ref=196392) |
| SSD VPS Super+ | 4 cores / 4 GB / 50 GB SSD | $21.12/mo ($26.40) | [SSD Super+](https://justhost.asia/en/vps?ref=196392) |
| NVMe VPS Super++ | 4 cores / 4 GB / 50 GB NVMe | $22.88/mo ($28.60) | [NVMe Super++](https://justhost.asia/en/vps?ref=196392) |

There is also an IPv6-only line starting at $1.60, with no IPv4 address. Skip it unless every visitor and every API you call is reachable over IPv6.

## What "cheap" hides: four numbers to check before you pay

### 1. An unmetered port is a speed limit, not a traffic allowance

JustHost labels each plan's port "UNMETERED … (fair-share)" and prints a conversion next to it: 300 Mbit "equals to 93+ TB monthly". That bracket is arithmetic. A 300 Mbit/s port running flat out for 30 days moves roughly 90 TB. The number tells you the ceiling if nothing else on the host is busy. "Fair-share" tells you the ceiling is shared with other tenants on that machine, so a busy neighbour can push your real throughput down during peak hours.

Whether that matters depends on what you do with the box. Serving a few thousand page views a month, it never comes up. Running a mirror, a video proxy, or a backup target, it decides everything, and the fair-share wording is the part to ask about.

Other Singapore hosts show why this deserves a check rather than an assumption. OVHcloud's Singapore page advertises unlimited traffic on all four VPS plans, and a footnote underneath sets a monthly quota of 500 GB on VPS-1, 1 TB on VPS-2 and VPS-3, and 3 TB on VPS-4, after which the port drops to 10 Mbps. ByteVirt's Singapore plans cut the port to 1 Mbps once the monthly allowance is used up. Contabo's "unlimited traffic" is subject to its own fair-usage policy. Exabytes splits bandwidth 80% for Singapore-local access and 20% for international visitors, which catches out anyone whose audience sits outside the region.

Ask what happens at twice your expected monthly traffic. A plan that throttles to 1 Mbps is a different product from one that bills you for the overage, and the headline speed doesn't tell you which you bought.

### 2. The 20% exists only on 12-month prepayment

Every discount on the JustHost page is tied to "when paying for 12 months". New Star's $1.77 is the 20%-off version of $2.21, and that tier also carries a three-month minimum order. Budget on the bracketed rate for anything you plan to keep, and treat the discounted rate as a first-term number until the checkout page shows you what the second term costs.

The industry gives plenty of reasons for that caution. Contabo's Singapore prices are marked "for the first 24 months", with a higher figure listed beside them, and its contract renews for a term equal to your initial one. Exabytes states that promotional pricing applies to new registrations only and reverts to the default price on renewal.

### 3. Storage type moves the price of identical RAM

The configurator lets you choose HDD, SSD, or NVMe on the same RAM and core count, and the gap is not small. 1 core / 512 MB / 5 GB costs $2.60 on HDD, $3.12 on SSD, $3.38 on NVMe. At 4 cores / 4 GB / 50 GB the same compute runs $17.60, $21.12, and $22.88. Roughly 30% separates the cheapest and dearest storage on identical specs.

For a database or a panel-driven site, NVMe is the one to take; the disk is usually the first bottleneck on a budget box. For a file dump or a download node, HDD is fine and saves real money.

### 4. Currency, tax and refunds aren't stated on the plan page

Prices carry a dollar sign without naming the currency, and the plan pages I checked don't state whether tax is included, whether there's a refund window, or whether a trial exists. That is normal for this segment and it is also why you should ask support in writing before a long prepay. A no-refund policy on a 12-month term turns a $2.25 plan into a $27 commitment you can't walk away from.

👉 [Check the 12-month and monthly totals side by side in the JustHost configurator](https://justhost.asia/en/services/vps/tariffs?ref=196392)

## Who should not buy the $1.77 plan

**Anyone installing a control panel.** A panel plus PHP plus MySQL plus a mail stack on 1 GB RAM means swapping. Vega's 4 GB and 80 GB NVMe at $6.23 is the realistic floor for a panel-managed site, and Capella at $8.49 buys 4 cores and 120 GB for the same money if you expect build processes or image-heavy uploads.

**Anyone running more than one site.** Ten GB of NVMe fills with logs, backups, and a couple of WordPress installs faster than you expect. Arcturus at $3.21 doubles RAM to 2 GB and storage to 30 GB for $1.44 more per month.

**Anyone who needs Windows or RDP.** The JustHost plan pages describe KVM virtualization and root access; they don't advertise Windows licences or RDP on this lineup. Confirm in writing before you buy if that's the requirement.

**Anyone who needs managed backups.** DDoS protection is advertised on the plan pages. A backup or snapshot policy for the Singapore location is not stated there, so assume you're responsible for your own copies until support tells you otherwise.

👉 [Compare Vega and Capella against the rest of the lineup](https://justhost.asia/en/services/vps/tariffs?ref=196392)

## How JustHost compares on the same job

All four competitors below were checked on their own Singapore pages. Currencies differ (SGD, EUR, USD) and tax treatment is not consistent across them, so read the notes column rather than the raw numbers.

| Provider / plan | Spec | Price | What the fine print says |
| --- | --- | --- | --- |
| JustHost Vega | 2 cores / 4 GB / 80 GB NVMe / 500 Mbit | $6.23/mo on 12-month prepay | Unmetered port on fair-share; 20% tied to annual payment |
| OVHcloud VPS-1 | 2 vCores / 4 GB / 40 GB NVMe / 500 Mbps, daily backup | S$5.78/mo ex GST | "Unlimited traffic" but a 500 GB monthly quota in Asia-Pacific, then 10 Mbps |
| Contabo CLOUD VPS 4 | 4 vCPU / 8 GB / 100 GB SSD / 200 Mbit | €4.40/mo for the first 24 months (€5.50 listed) | Fair-usage policy on traffic; renewal term equals initial term |
| ByteVirt VPS-4096-KVM-SG | 2 cores / 4 GB / 40 GB NVMe / 2 TB at 500 Mbps | $5.00/mo | Port limited to 1 Mbps after the monthly allowance; cheapest annual plans showed 0 in stock |
| LightNode Start | 1 vCPU / 2 GB / 50 GB NVMe / 1 TB | $7.71/mo or $0.012/hour | Traffic-based and bandwidth-based billing can't be switched after creation |

Two things that table won't tell you. OVHcloud's page both advertises one-click Windows and cPanel installs and footnotes that Local Zones don't support Windows, cPanel, Plesk or additional IPs, so verify per region. LightNode's own page lists both $7.70 and $7.71 in different places. Neither discrepancy is fatal, but both are reasons to read the checkout page instead of the marketing copy.

JustHost's argument inside this group is the 80 GB of NVMe and 500 Mbit port at $6.23, plus a configurator that lets you buy exactly the RAM/storage ratio you want instead of a fixed ladder. OVHcloud wins on included daily backups and a documented SLA. Contabo wins on raw cores per euro for the first two years. ByteVirt wins on price per gigabyte if you can find stock, and its two cheapest annual plans were unavailable when I looked.

## What buyers report

Trustpilot reviews for JustHost.Asia are mixed, and the pattern is worth knowing before you commit a year. The negative reviews centre on support: a live-chat bot that failed to recognise a customer's own server IP, and a 2 March 2026 outage where several customers report 15 hours or more without a status update. One reviewer describes download speeds collapsing to around 20 Mbit/s with 1500 ms ping until the server was moved to another location. Positive reviews praise the price and describe the control panel as easy to use.

The practical reading: this is a self-managed budget host where you should keep your own off-server backups, set up external uptime monitoring, and expect to solve problems yourself. If a two-hour support response is a hard requirement for your project, budget three to five times more per month and buy from a host that sells a support contract.

## FAQ

**Is $1.77 the amount that leaves my account?**
It's the 12-month rate for the New Star offer tier, which requires a minimum three-month order. The monthly rate on the same plan is listed at $2.21. Tax and the Singapore-specific total are shown at checkout, not on the plan page.

**Will the price jump after the first year?**
The page shows a discounted rate tied to 12-month payment and a higher monthly rate beside it. Whether the discount repeats on renewal isn't stated on the plan pages, so ask before prepaying more than one term.

**Can it run WordPress or WooCommerce?**
WordPress on 1 GB with 10 GB of storage works for a small blog. WooCommerce adds a database, plugins, and order data; take Vega (4 GB / 80 GB) as the minimum and Capella (4 cores / 120 GB) if you also run staging or image processing. Nothing in this lineup is managed, so you handle updates, security, and backups.

**Do I get IPv6?**
Yes on the main and special-offer lines, which ship IPv4 plus a /64 IPv6 block. The cheapest line is IPv6-only and starts at $1.60.

## Which plan to pick

- One small site, a bot, or a proxy: **Arcturus**, $3.21/mo on annual billing.
- One real site with a panel and a database: **Vega**, $6.23/mo. This is the plan most readers should buy.
- Several sites or heavier builds: **Capella** at $8.49, or **Rigel** at $12.96 if you want 8 GB.
- Testing, scraping, or a throwaway endpoint: **New Star** at $1.77, accepting the three-month minimum.
- Storage-heavy, compute-light: the HDD line at $2.60–$17.60 beats the NVMe line on price for the same RAM.

Two things to confirm before you pay. Check the actual Singapore total at checkout, including currency and tax, and confirm in writing what happens if you exceed the fair-share port speed or need a refund inside the first month.

👉 [Open the JustHost VPS configurator and price your Singapore plan](https://justhost.asia/en/services/vps/tariffs?ref=196392)
