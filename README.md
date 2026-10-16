# racknerd vps review: what the $10.18/year KVM plan actually gets you, how catalog and specials pricing differ, and the fine print before checkout

Most people searching for a RackNerd VPS review are really asking one question: can a host selling KVM servers for roughly the price of a sandwich per year actually be any good? Short answer — yes, within its lane. RackNerd is a Los Angeles company founded in 2019, an Inc. 5000 listee, and the most frequent fixture on LowEndBox deal pages. Its 1 GB KVM plans have repeatedly sold in the $10–13/year range, including a Black Friday plan at **$10.18/year** (768 MB RAM, 15 GB SSD, 1 TB traffic) that has stuck around long enough for thousands of people to treat it as their default always-on box.

The hardware and network are real, and the promo pricing renews at the same rate instead of ballooning in year two. The catches live elsewhere: everything above the hypervisor is self-managed, support is ticket-only, and the cheapest annual specials are non-refundable. Everything below is the detail you need to decide which side of that trade you're on.

> **Quick verdict**
>
> - **Cheapest always-on box** (VPN, Pi-hole, a bot, a staging site): the yearly Specials line, which in August 2026 ran from about $21.99/year (1 vCPU, 1 GB RAM, 20 GB SSD, 3 TB traffic) up to about $119.99/year (7 vCPU, 8 GB RAM, 150 GB SSD, 20 TB). Stock rotates, so [👉 check what's currently in RackNerd's specials store](https://bit.ly/my-rn).
> - **Predictable monthly billing**: the catalog KVM line, $17.99–$55.99/month depending on size.
> - **Need managed support, hourly cloud billing, or guaranteed CPU?** Wrong category — Vultr, DigitalOcean, or a managed host fits better.

## What you're actually buying

Every RackNerd KVM VPS, at every price, ships the same baseline: KVM virtualization, full root access, a SolusVM-class panel that handles reboots, OS reinstalls, console, and rDNS without a ticket, a 1 Gbps network port, a dedicated IPv4 address, instant setup, a 99.9% uptime SLA, and 24/7 ticket support. Storage is RAID-10 SSD on most plans, with a separate Ryzen line on NVMe. IPv6 is available on request in select locations — up to 100 addresses, with Los Angeles DC-02 among them.

What you don't get is management. RackNerd keeps the hypervisor and network up; you pick the OS image, harden SSH, patch packages, and wire your own backups. There's no staging layer, no app-level restores, no migration help — free migration isn't offered at all. Published scorecards consistently rate value far above support; HostProdigy's 2026 card puts value for money at 9.2/10 against 6.6/10 for support, and the pattern in user feedback matches: reboots and network issues get quick ticket answers, OS-level problems are yours.

One more thing explains the price: RackNerd doesn't own its datacenters. It leases space — Multacom in Los Angeles, ColoCrossing in New York and Dallas — spends almost nothing on marketing, and sells mainly through deal channels. Low overhead plus volume is the entire model. It also means location choice is genuine: Los Angeles, San Jose, Seattle, Dallas, Chicago, Atlanta, Ashburn, and the New York area in the US, plus Amsterdam, with some current plans also listed in Dublin, Toronto, and France.

## RackNerd pricing: the catalog and the specials are two different products

The single most useful thing to understand before comparing any RackNerd price: the always-available catalog and the Special Promos page are separate inventories with separate specs, and roundups that paste a special's yearly price next to a catalog monthly price make both look wrong.

A "4 GB RackNerd VPS" can mean either of these:

- **Catalog KVM 4 GB**: 4 vCPU, 130 GB SSD, 3 TB traffic, **$24.59/month** — always available, billed monthly, renews at list price.
- **Specials KVM 4 GB**: 3 vCPU, 60 GB SSD, 7 TB traffic, about **$59.99/year** as of August 2026 — prepaid annually, limited stock.

Annualize the catalog plan and you're near $295/year versus $60 for the special. Same brand, same virtualization, completely different value proposition — and neither price is wrong. The special is the deal; the catalog is the fallback when the stock you want is gone or you won't prepay a year.

### The yearly specials (August 2026 samples)

| Yearly price | vCPU | RAM | Storage | Monthly traffic |
| --- | --- | --- | --- | --- |
| ≈ $21.99 | 1 | 1 GB | 20 GB SSD | 3 TB |
| ≈ $35.99 | 2 | 2 GB | 35 GB SSD | 5 TB |
| ≈ $59.99 | 3 | 4 GB | 60 GB SSD | 7 TB |
| ≈ $89.99 | 6 | 6 GB | 100 GB SSD | 12 TB |
| ≈ $119.99 | 7 | 8 GB | 150 GB SSD | 20 TB |

Treat this as a shape, not a fixed catalog. RackNerd times specials around Black Friday, New Year, Chinese New Year, and random midweek drops; quantities are limited and popular tiers sell out. Older flash deals have gone lower still — 1 GB plans have surfaced at $10.18–$13/year more than once. [👉 See what's in stock right now](https://bit.ly/my-rn)

### Renewal: the part most roundups get wrong

The reassuring half first: long-running reviews consistently report that promo annual plans renew at the same promotional rate. The ~$11/year you paid doesn't become $30 next year, and that renewal consistency is a big reason customers stay for years. The less advertised half is availability — if your exact special gets retired, year two isn't a renewal of that SKU. You either re-buy whichever special is live or move to catalog pricing. Keep a copy of your order page so you know exactly what you signed up for.

## Full RackNerd KVM plan list and pricing

The catalog currently comes in two hardware flavors at identical prices: standard KVM on RAID-10 SSD with bigger volumes, and a Ryzen NVMe line that trades storage for faster disks. Both tables below include KVM virtualization, SolusVM, 1 Gbps ports, dedicated IPv4, and instant setup.

### Standard KVM plans (RAID-10 SSD)

| Plan | vCPU | Storage | Traffic/mo | Price | Order |
| --- | --- | --- | --- | --- | --- |
| Starter (512 MB) | 1 | 30 GB | 500 GB | $26.99/yr | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=1) |
| 1 GB | 2 | 50 GB | 1 TB | $17.99/mo | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=20) |
| 2 GB | 3 | 75 GB | 2 TB | $20.59/mo | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=21) |
| 4 GB | 4 | 130 GB | 3 TB | $24.59/mo | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=22) |
| 6 GB | 5 | 170 GB | 4 TB | $27.59/mo | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=23) |
| 8 GB | 6 | 220 GB | 5 TB | $36.59/mo | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=24) |
| 12 GB | 7 | 300 GB | 6 TB | $55.99/mo | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=25) |

The Starter plan bills annually at $26.99 (about $2.25/month equivalent). Everything above it is the list monthly price — which is precisely why the specials exist. When a special with similar specs is in stock, it's almost always the better buy.

### Ryzen NVMe plans

| Plan | vCPU | Storage | Traffic/mo | Price | Order |
| --- | --- | --- | --- | --- | --- |
| Ryzen 512 MB | 1 | 10 GB NVMe | 500 GB | $26.99/yr | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=500) |
| Ryzen 1 GB | 1 | 15 GB NVMe | 1 TB | $17.99/mo | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=501) |
| Ryzen 2 GB | 2 | 20 GB NVMe | 2 TB | $20.59/mo | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=502) |
| Ryzen 4 GB | 2 | 30 GB NVMe | 3 TB | $24.59/mo | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=503) |
| Ryzen 6 GB | 3 | 45 GB NVMe | 4 TB | $27.59/mo | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=504) |
| Ryzen 8 GB | 3 | 75 GB NVMe | 5 TB | $36.59/mo | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=505) |
| Ryzen 12 GB | 4 | 90 GB NVMe | 6 TB | $55.99/mo | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=506) |

Same prices, less disk, faster disk. For MySQL or PostgreSQL with any real query load, caching layers, or anything else I/O-bound, the NVMe line is the sensible pick — reviewers report the response-time difference is noticeable. For storage-hungry uses (file backups, media, several sites on one box), the standard line's larger volumes win. [👉 Compare both lines' current pricing](https://bit.ly/my-rn)

RackNerd also sells Hybrid and dedicated servers, colocation, shared hosting, and reseller plans, but the KVM line above is what nearly everyone means by "RackNerd VPS."

## Performance: what independent benchmarks show

For the money, performance is solid, with the usual shared-core caveats.

A six-month benchmark run on the $10.18/year Los Angeles plan recorded Geekbench 6 around 1,020 single-core, roughly 380 MB/s sequential disk throughput, a genuine 920 Mbps on the 1 Gbps port, and 99.93% uptime with two brief outages (the longer one lasted 22 minutes). Another reviewer who has run RackNerd servers on and off since 2022 measured Geekbench 5 single-core around 412 on a $1.99/month plan served by Ryzen 9 3900X/5900X nodes with NVMe, 38 ms time-to-first-byte from US West, and 99.84% uptime over 30 days. One review site tallies 4.4/5 across 345 user ratings.

Latency from the Los Angeles datacenter, as measured during that six-month test: 35 ms to San Jose, 60 ms to Seattle, 55 ms to Chicago, 72 ms to New York, 85 ms to London, 180 ms to Tokyo. Serving US East Coast or European users? Ashburn or New York makes more sense. Audience in Asia? LA is the usual choice.

The caveat: these are shared-core nodes packed for economics. KVM isolation keeps the worst noisy-neighbor behavior out of your benchmarks — one tester specifically noted never hitting it — but sustained full-tilt CPU use runs against the spirit, and sometimes the letter, of the acceptable use policy. A VPN endpoint, DNS resolver, or monitoring probe never gets near that line. A game server with 30 players might.

## The fine print before you buy

Three policies cause most purchase regrets here, so read them before clicking order.

**Refunds.** Standard orders carry a 72-hour money-back guarantee for new customers. Promotional annual plans are non-refundable, full stop. The practical rule: if you're unsure you'll keep the box, buy a catalog plan first and decide within the 72-hour window — only buy a special when you already know you want it for a year. If that works for you, [👉 the catalog 4 GB plan is here](https://my.racknerd.com/aff.php?aff=16470&pid=22).

**Backups.** Weekly backups are included; automated daily backups cost extra, around $1.50/month. Whichever you pick, keep an off-site copy. Every long-term review of this company says some version of the same thing, and a non-refundable promo plan won't refund you for your own mistakes.

**Support.** 24/7 tickets and email plus a knowledge base. No phone, no live chat. Reported response times range from about 30 minutes to 8 hours. Network issues and reboots are handled well; application problems are on you.

A few smaller ones worth knowing: sustained heavy CPU use is discouraged, free migration isn't offered, and the cheapest plans carry modest bandwidth (500 GB/month on Starter). None of this bothers the target audience. All of it surprises people who arrived expecting cloud-provider norms.

## Who RackNerd fits, and who should pay more

RackNerd's sweet spot is the "idle hardware replacement" — the cheapest reliable way to keep something running 24/7.

Good fit:

- VPN/WireGuard endpoints, DNS resolvers, Pi-hole, monitoring probes, bots
- Staging and dev servers, hobby projects, learning server administration
- Self-hosted apps like Nextcloud for personal use
- Developers who'd rather run several cheap isolated boxes than one expensive one

Wrong tool:

- E-commerce or anything processing payments on a busy store
- High-traffic WordPress — long-term reviewers put the practical ceiling of small plans at a few thousand daily visitors
- Teams needing phone support, managed patching, or hourly cloud billing
- Sustained CPU-heavy workloads

When the fit is wrong, the usual alternatives are Vultr or DigitalOcean — their comparable 4 GB tiers sit around $24/month with hourly billing and far more regions — or Hostinger's KVM line when its intro-and-renewal math suits you. None of them touch RackNerd's yearly specials on price. That's not their business.

## RackNerd FAQ

**Is the ~$11/year RackNerd VPS a scam?**
No. RackNerd has sold 1 GB KVM plans in the $10–13/year range through deal channels since 2019, runs KVM virtualization with full root, and holds Inc. 5000 listing with a stable ownership record. The realistic caveats are stock limits on specials, self-managed everything, and non-refundable promo terms.

**Do RackNerd promo prices go up on renewal?**
Promo annual plans are widely reported to renew at the same promotional rate — that's the core of the offer. The confusion usually comes from comparing a special's yearly price against the catalog's monthly list, which are different products. If your exact special is retired, you'd re-buy a live one or switch to catalog pricing.

**Can I get a refund?**
Standard orders have a 72-hour money-back guarantee for new customers. Promotional annual plans are excluded from refunds, so treat a special purchase as final.

**Which datacenter should I choose?**
Pick by audience. Los Angeles for West Coast and trans-Pacific traffic, Dallas or Chicago for central US, Ashburn or New York for East Coast and Europe. Measured from LA: 35 ms to San Jose, 72 ms to New York, 85 ms to London, 180 ms to Tokyo. Some plans also list Amsterdam, Dublin, Toronto, and France.

**Is RackNerd okay for a production website?**
For a low-traffic production site with your own backups and monitoring, it's workable — one reviewer runs a small WordPress blog on it at about 1.4-second page loads. For high-traffic or revenue-critical sites, ticket-only support and shared cores argue for paying more elsewhere.

## Which plan to pick, and what to double-check at checkout

A few decision rules based on everything above:

- Want the absolute cheapest box for a light project → whatever 1–2 GB special is in stock (roughly $22–36/year as of August 2026).
- Need bigger tiers, or refuse to prepay a year → catalog 4 GB at $24.59/month is the steady pick.
- Running a database or anything I/O-sensitive → Ryzen NVMe line.
- Want a safety net while you evaluate → catalog plan, then decide within 72 hours.

Before paying, confirm the exact specs and billing term on the order form itself — specials rotate, and the checkout page is the source of truth. Note that promo annual plans are non-refundable, and have a backup plan. Literally.

If that trade sounds right for your situation, [👉 check RackNerd's current plans and live specials](https://bit.ly/my-rn) before the next deal cycle resets the stock.
# racknerd vps review: what the $10.18/year KVM plan actually gets you, how catalog and specials pricing differ, and the fine print before checkout

Most people searching for a RackNerd VPS review are really asking one question: can a host selling KVM servers for roughly the price of a sandwich per year actually be any good? Short answer — yes, within its lane. RackNerd is a Los Angeles company founded in 2019, an Inc. 5000 listee, and the most frequent fixture on LowEndBox deal pages. Its 1 GB KVM plans have repeatedly sold in the $10–13/year range, including a Black Friday plan at **$10.18/year** (768 MB RAM, 15 GB SSD, 1 TB traffic) that has stuck around long enough for thousands of people to treat it as their default always-on box.

The hardware and network are real, and the promo pricing renews at the same rate instead of ballooning in year two. The catches live elsewhere: everything above the hypervisor is self-managed, support is ticket-only, and the cheapest annual specials are non-refundable. Everything below is the detail you need to decide which side of that trade you're on.

> **Quick verdict**
>
> - **Cheapest always-on box** (VPN, Pi-hole, a bot, a staging site): the yearly Specials line, which in August 2026 ran from about $21.99/year (1 vCPU, 1 GB RAM, 20 GB SSD, 3 TB traffic) up to about $119.99/year (7 vCPU, 8 GB RAM, 150 GB SSD, 20 TB). Stock rotates, so [👉 check what's currently in RackNerd's specials store](https://bit.ly/my-rn).
> - **Predictable monthly billing**: the catalog KVM line, $17.99–$55.99/month depending on size.
> - **Need managed support, hourly cloud billing, or guaranteed CPU?** Wrong category — Vultr, DigitalOcean, or a managed host fits better.

## What you're actually buying

Every RackNerd KVM VPS, at every price, ships the same baseline: KVM virtualization, full root access, a SolusVM-class panel that handles reboots, OS reinstalls, console, and rDNS without a ticket, a 1 Gbps network port, a dedicated IPv4 address, instant setup, a 99.9% uptime SLA, and 24/7 ticket support. Storage is RAID-10 SSD on most plans, with a separate Ryzen line on NVMe. IPv6 is available on request in select locations — up to 100 addresses, with Los Angeles DC-02 among them.

What you don't get is management. RackNerd keeps the hypervisor and network up; you pick the OS image, harden SSH, patch packages, and wire your own backups. There's no staging layer, no app-level restores, no migration help — free migration isn't offered at all. Published scorecards consistently rate value far above support; HostProdigy's 2026 card puts value for money at 9.2/10 against 6.6/10 for support, and the pattern in user feedback matches: reboots and network issues get quick ticket answers, OS-level problems are yours.

One more thing explains the price: RackNerd doesn't own its datacenters. It leases space — Multacom in Los Angeles, ColoCrossing in New York and Dallas — spends almost nothing on marketing, and sells mainly through deal channels. Low overhead plus volume is the entire model. It also means location choice is genuine: Los Angeles, San Jose, Seattle, Dallas, Chicago, Atlanta, Ashburn, and the New York area in the US, plus Amsterdam, with some current plans also listed in Dublin, Toronto, and France.

## RackNerd pricing: the catalog and the specials are two different products

The single most useful thing to understand before comparing any RackNerd price: the always-available catalog and the Special Promos page are separate inventories with separate specs, and roundups that paste a special's yearly price next to a catalog monthly price make both look wrong.

A "4 GB RackNerd VPS" can mean either of these:

- **Catalog KVM 4 GB**: 4 vCPU, 130 GB SSD, 3 TB traffic, **$24.59/month** — always available, billed monthly, renews at list price.
- **Specials KVM 4 GB**: 3 vCPU, 60 GB SSD, 7 TB traffic, about **$59.99/year** as of August 2026 — prepaid annually, limited stock.

Annualize the catalog plan and you're near $295/year versus $60 for the special. Same brand, same virtualization, completely different value proposition — and neither price is wrong. The special is the deal; the catalog is the fallback when the stock you want is gone or you won't prepay a year.

### The yearly specials (August 2026 samples)

| Yearly price | vCPU | RAM | Storage | Monthly traffic |
| --- | --- | --- | --- | --- |
| ≈ $21.99 | 1 | 1 GB | 20 GB SSD | 3 TB |
| ≈ $35.99 | 2 | 2 GB | 35 GB SSD | 5 TB |
| ≈ $59.99 | 3 | 4 GB | 60 GB SSD | 7 TB |
| ≈ $89.99 | 6 | 6 GB | 100 GB SSD | 12 TB |
| ≈ $119.99 | 7 | 8 GB | 150 GB SSD | 20 TB |

Treat this as a shape, not a fixed catalog. RackNerd times specials around Black Friday, New Year, Chinese New Year, and random midweek drops; quantities are limited and popular tiers sell out. Older flash deals have gone lower still — 1 GB plans have surfaced at $10.18–$13/year more than once. [👉 See what's in stock right now](https://bit.ly/my-rn)

### Renewal: the part most roundups get wrong

The reassuring half first: long-running reviews consistently report that promo annual plans renew at the same promotional rate. The ~$11/year you paid doesn't become $30 next year, and that renewal consistency is a big reason customers stay for years. The less advertised half is availability — if your exact special gets retired, year two isn't a renewal of that SKU. You either re-buy whichever special is live or move to catalog pricing. Keep a copy of your order page so you know exactly what you signed up for.

## Full RackNerd KVM plan list and pricing

The catalog currently comes in two hardware flavors at identical prices: standard KVM on RAID-10 SSD with bigger volumes, and a Ryzen NVMe line that trades storage for faster disks. Both tables below include KVM virtualization, SolusVM, 1 Gbps ports, dedicated IPv4, and instant setup.

### Standard KVM plans (RAID-10 SSD)

| Plan | vCPU | Storage | Traffic/mo | Price | Order |
| --- | --- | --- | --- | --- | --- |
| Starter (512 MB) | 1 | 30 GB | 500 GB | $26.99/yr | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=1) |
| 1 GB | 2 | 50 GB | 1 TB | $17.99/mo | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=20) |
| 2 GB | 3 | 75 GB | 2 TB | $20.59/mo | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=21) |
| 4 GB | 4 | 130 GB | 3 TB | $24.59/mo | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=22) |
| 6 GB | 5 | 170 GB | 4 TB | $27.59/mo | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=23) |
| 8 GB | 6 | 220 GB | 5 TB | $36.59/mo | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=24) |
| 12 GB | 7 | 300 GB | 6 TB | $55.99/mo | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=25) |

The Starter plan bills annually at $26.99 (about $2.25/month equivalent). Everything above it is the list monthly price — which is precisely why the specials exist. When a special with similar specs is in stock, it's almost always the better buy.

### Ryzen NVMe plans

| Plan | vCPU | Storage | Traffic/mo | Price | Order |
| --- | --- | --- | --- | --- | --- |
| Ryzen 512 MB | 1 | 10 GB NVMe | 500 GB | $26.99/yr | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=500) |
| Ryzen 1 GB | 1 | 15 GB NVMe | 1 TB | $17.99/mo | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=501) |
| Ryzen 2 GB | 2 | 20 GB NVMe | 2 TB | $20.59/mo | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=502) |
| Ryzen 4 GB | 2 | 30 GB NVMe | 3 TB | $24.59/mo | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=503) |
| Ryzen 6 GB | 3 | 45 GB NVMe | 4 TB | $27.59/mo | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=504) |
| Ryzen 8 GB | 3 | 75 GB NVMe | 5 TB | $36.59/mo | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=505) |
| Ryzen 12 GB | 4 | 90 GB NVMe | 6 TB | $55.99/mo | [ Order](https://my.racknerd.com/aff.php?aff=16470&pid=506) |

Same prices, less disk, faster disk. For MySQL or PostgreSQL with any real query load, caching layers, or anything else I/O-bound, the NVMe line is the sensible pick — reviewers report the response-time difference is noticeable. For storage-hungry uses (file backups, media, several sites on one box), the standard line's larger volumes win. [👉 Compare both lines' current pricing](https://bit.ly/my-rn)

RackNerd also sells Hybrid and dedicated servers, colocation, shared hosting, and reseller plans, but the KVM line above is what nearly everyone means by "RackNerd VPS."

## Performance: what independent benchmarks show

For the money, performance is solid, with the usual shared-core caveats.

A six-month benchmark run on the $10.18/year Los Angeles plan recorded Geekbench 6 around 1,020 single-core, roughly 380 MB/s sequential disk throughput, a genuine 920 Mbps on the 1 Gbps port, and 99.93% uptime with two brief outages (the longer one lasted 22 minutes). Another reviewer who has run RackNerd servers on and off since 2022 measured Geekbench 5 single-core around 412 on a $1.99/month plan served by Ryzen 9 3900X/5900X nodes with NVMe, 38 ms time-to-first-byte from US West, and 99.84% uptime over 30 days. One review site tallies 4.4/5 across 345 user ratings.

Latency from the Los Angeles datacenter, as measured during that six-month test: 35 ms to San Jose, 60 ms to Seattle, 55 ms to Chicago, 72 ms to New York, 85 ms to London, 180 ms to Tokyo. Serving US East Coast or European users? Ashburn or New York makes more sense. Audience in Asia? LA is the usual choice.

The caveat: these are shared-core nodes packed for economics. KVM isolation keeps the worst noisy-neighbor behavior out of your benchmarks — one tester specifically noted never hitting it — but sustained full-tilt CPU use runs against the spirit, and sometimes the letter, of the acceptable use policy. A VPN endpoint, DNS resolver, or monitoring probe never gets near that line. A game server with 30 players might.

## The fine print before you buy

Three policies cause most purchase regrets here, so read them before clicking order.

**Refunds.** Standard orders carry a 72-hour money-back guarantee for new customers. Promotional annual plans are non-refundable, full stop. The practical rule: if you're unsure you'll keep the box, buy a catalog plan first and decide within the 72-hour window — only buy a special when you already know you want it for a year. If that works for you, [👉 the catalog 4 GB plan is here](https://my.racknerd.com/aff.php?aff=16470&pid=22).

**Backups.** Weekly backups are included; automated daily backups cost extra, around $1.50/month. Whichever you pick, keep an off-site copy. Every long-term review of this company says some version of the same thing, and a non-refundable promo plan won't refund you for your own mistakes.

**Support.** 24/7 tickets and email plus a knowledge base. No phone, no live chat. Reported response times range from about 30 minutes to 8 hours. Network issues and reboots are handled well; application problems are on you.

A few smaller ones worth knowing: sustained heavy CPU use is discouraged, free migration isn't offered, and the cheapest plans carry modest bandwidth (500 GB/month on Starter). None of this bothers the target audience. All of it surprises people who arrived expecting cloud-provider norms.

## Who RackNerd fits, and who should pay more

RackNerd's sweet spot is the "idle hardware replacement" — the cheapest reliable way to keep something running 24/7.

Good fit:

- VPN/WireGuard endpoints, DNS resolvers, Pi-hole, monitoring probes, bots
- Staging and dev servers, hobby projects, learning server administration
- Self-hosted apps like Nextcloud for personal use
- Developers who'd rather run several cheap isolated boxes than one expensive one

Wrong tool:

- E-commerce or anything processing payments on a busy store
- High-traffic WordPress — long-term reviewers put the practical ceiling of small plans at a few thousand daily visitors
- Teams needing phone support, managed patching, or hourly cloud billing
- Sustained CPU-heavy workloads

When the fit is wrong, the usual alternatives are Vultr or DigitalOcean — their comparable 4 GB tiers sit around $24/month with hourly billing and far more regions — or Hostinger's KVM line when its intro-and-renewal math suits you. None of them touch RackNerd's yearly specials on price. That's not their business.

## RackNerd FAQ

**Is the ~$11/year RackNerd VPS a scam?**
No. RackNerd has sold 1 GB KVM plans in the $10–13/year range through deal channels since 2019, runs KVM virtualization with full root, and holds Inc. 5000 listing with a stable ownership record. The realistic caveats are stock limits on specials, self-managed everything, and non-refundable promo terms.

**Do RackNerd promo prices go up on renewal?**
Promo annual plans are widely reported to renew at the same promotional rate — that's the core of the offer. The confusion usually comes from comparing a special's yearly price against the catalog's monthly list, which are different products. If your exact special is retired, you'd re-buy a live one or switch to catalog pricing.

**Can I get a refund?**
Standard orders have a 72-hour money-back guarantee for new customers. Promotional annual plans are excluded from refunds, so treat a special purchase as final.

**Which datacenter should I choose?**
Pick by audience. Los Angeles for West Coast and trans-Pacific traffic, Dallas or Chicago for central US, Ashburn or New York for East Coast and Europe. Measured from LA: 35 ms to San Jose, 72 ms to New York, 85 ms to London, 180 ms to Tokyo. Some plans also list Amsterdam, Dublin, Toronto, and France.

**Is RackNerd okay for a production website?**
For a low-traffic production site with your own backups and monitoring, it's workable — one reviewer runs a small WordPress blog on it at about 1.4-second page loads. For high-traffic or revenue-critical sites, ticket-only support and shared cores argue for paying more elsewhere.

## Which plan to pick, and what to double-check at checkout

A few decision rules based on everything above:

- Want the absolute cheapest box for a light project → whatever 1–2 GB special is in stock (roughly $22–36/year as of August 2026).
- Need bigger tiers, or refuse to prepay a year → catalog 4 GB at $24.59/month is the steady pick.
- Running a database or anything I/O-sensitive → Ryzen NVMe line.
- Want a safety net while you evaluate → catalog plan, then decide within 72 hours.

Before paying, confirm the exact specs and billing term on the order form itself — specials rotate, and the checkout page is the source of truth. Note that promo annual plans are non-refundable, and have a backup plan. Literally.

If that trade sounds right for your situation, [👉 check RackNerd's current plans and live specials](https://bit.ly/my-rn) before the next deal cycle resets the stock.
