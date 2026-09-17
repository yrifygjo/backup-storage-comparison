# best online backup and storage: how to choose the right setup for your files and servers, from a $4/month Acronis backup to S3 storage at $4.90/TB

Type "best online backup and storage" into a search engine and you'll get two very different product categories pretending to be the same thing. One is backup software that quietly copies your laptop or server to someone else's data center. The other is raw storage space you can dump files into. The marketing copy from both camps blurs the line on purpose, because each wants to sell you the other's product.

So before comparing prices, it helps to know which problem you're actually solving. This article walks through that distinction, what reviewers consistently recommend for personal use, and when it makes sense to skip consumer backup apps entirely and buy storage and backup straight from a hosting provider — including the full current lineup from Sharktech, whose Acronis-based backup starts at $4/month for 200GB and whose S3-compatible object storage runs at a flat $4.90/TB.

## Backup and storage are not the same product

Here's the short version: **cloud storage** is built for access. You put files in, you pull files out, you share them, you sync them across devices. **Online backup** is built for recovery. It keeps historical copies of your data so that when a drive dies, a file gets overwritten, or ransomware encrypts everything, you can roll back to yesterday.

The difference shows up in features that matter only when things go wrong:

- **Versioning and retention.** A good backup service keeps multiple older copies of a file. Plain storage usually keeps only the latest version, which is useless if the latest version is the corrupted one.
- **Automatic scheduling.** Backup tools run on their own, hourly or daily. Storage requires you to remember to upload things.
- **Restore paths.** Backup services offer file-level restore, full-system restore, and sometimes bare-metal disaster recovery. Storage gives you a download link and good luck.
- **Encryption in transit and at rest.** Both categories usually offer this now, but backup services tend to make it the default rather than a settings menu you have to find.

Plenty of services do both jobs — a sync folder plus a backup engine — but almost none do both equally well. Figure out which failure you're insuring against first, then shop.

One framework worth knowing before spending anything: the **3-2-1 rule**. Keep three copies of your data, on two different media, with one copy off-site. It's been standard advice in the IT world for years precisely because it survives the failure modes people actually experience: the dead drive, the accidental deletion, the house-level disaster. Any online service you pick is most likely going to be that "one off-site copy," so it's worth choosing one you'd trust with the only surviving version of your files.

## What the big review roundups recommend

The major tech publications re-test these services regularly, and their conclusions are remarkably stable.

**iDrive** shows up as the best overall pick in roundups from PCWorld and appears in The New York Times' Wirecutter coverage, which notes that for a typical price of about $100 a year it covers unlimited devices with 5TB of storage. The appeal is breadth: one account backs up PCs, Macs, phones, and tablets, and it includes features like disk-image cloning and physical drive shipping for large transfers.

**Backblaze** is the budget pick, at $6 a month or roughly $60 a year for unlimited backup of one computer. If your situation is "one laptop, everything on it, don't want to think about gigabytes," it's hard to beat that simplicity.

**Carbonite** gets recommended as the most streamlined option — less configurability than iDrive, but a gentler setup for people who don't want to make decisions. **Livedrive** earns mentions for unlimited storage plans, and **Sync.com** for a usable free tier.

These are all consumer-grade tools, and for backing up a personal machine they're the right first stop. Where they get awkward is servers, virtual machines, databases, and business infrastructure. That's when the pricing math changes and a hosting provider enters the picture.

## When a hosting provider makes more sense than a backup app

Sharktech is a Las Vegas-based hosting company that's been around since 2003, with data centers in Los Angeles, Las Vegas, Denver, Chicago, and Amsterdam. Their main business is infrastructure — bare-metal servers, OpenStack-based cloud hosting, VPS plans — but two of their services map directly onto the backup and storage question:

- **Acronis Cloud Backup**, built on Acronis Cyber Protect, aimed at backing up machines, servers, and VMs.
- **S3 Object Storage**, aimed at archives, media libraries, and off-site copies of data that rarely changes.

The consumer apps above charge per device or per terabyte with a consumer feature set. Sharktech's approach is closer to what an MSP or a sysadmin would buy: per-GB pricing, API access, and no per-device licensing games. Whether that's better depends entirely on what you're protecting.

## Sharktech's backup and storage plans, side by side

Here is the full current lineup relevant to backup and storage, pulled from Sharktech's store and product pages at the time of writing. Prices are in USD.

| Plan | What it covers | Price | Billing | Get started |
| --- | --- | --- | --- | --- |
| **Acronis Cloud Backup** | Backup & protection from 200GB (scalable to 100TB), optional Files Sync & Share add-on; 5 locations | From **$4.00** (200GB, $0.02 per extra GB) | Monthly, quarterly, semi-annual, annual | [View Acronis backup plans](https://bit.ly/SharKTech) |
| **Object Storage (S3)** | S3-compatible object storage from 1TB, bandwidth from 1TB (store listing); flat rate $4.90/TB per product page | From **$6.00** per the store listing; product page advertises $4.90/TB with 1TB transfer included | Monthly | [Check S3 storage pricing](https://bit.ly/SharKTech) |
| **Smart VPS** | 2–128 vCPU, 4–256GB RAM, 40GB–2TB NVMe storage, 4–304TB transfer, 60Gbps DDoS protection, 1 IPv4 included | From **$7.95** ($3.98/mo effective on annual billing, 50% off; 25% off quarterly, 35% off semi-annual) | Monthly / quarterly / semi-annual / annual | 👏 [Deploy a Smart VPS](https://bit.ly/SharKTech) |
| **Public Cloud — Small** | Resource pool: 4–16 vCPU, 8–32GB RAM, SSD 300–2400GB, HDD up to 4800GB, NVMe up to 1200GB, 20TB+ bandwidth, unlimited VMs | From **$39.00** | Monthly (hourly overage billing) | [See Public Cloud Small](https://bit.ly/SharKTech) |
| **Public Cloud — Medium** | 8–32 vCPU, 16–64GB RAM, SSD 800–6400GB, HDD up to 12800GB, NVMe up to 3200GB, 20TB+ bandwidth | From **$79.00** | Monthly (hourly overage billing) | [See Public Cloud Medium](https://bit.ly/SharKTech) |
| **Public Cloud — Large** | 32–128 vCPU, 64–256GB RAM, SSD 1500–12000GB, HDD up to 24000GB, NVMe up to 6000GB, 20TB+ bandwidth | From **$249.00** | Monthly (hourly overage billing) | [See Public Cloud Large](https://bit.ly/SharKTech) |
| **Public Cloud — Enterprise** | 64+ vCPU, 128GB+ RAM, 5000GB+ SSD, HDD and NVMe scalable without fixed caps, 20TB+ bandwidth | From **$499.00** | Monthly (custom configuration available) | [See Public Cloud Enterprise](https://bit.ly/SharKTech) |

A few honest notes on that table. The S3 pricing has a wrinkle: Sharktech's S3 product page advertises a flat **$4.90/TB** rate with 1TB of bandwidth included at no charge, while their store listing currently shows the 1TB package starting at $6.00/month. Final checkout price depends on the configuration you select, so treat $4.90/TB as the advertised rate and verify the exact figure in the cart. That's still dramatically below hyperscaler object storage, where standard tiers run roughly $0.018–$0.023 per GB — which works out to $18–$23 per terabyte per month before egress fees.

Sharktech also sells dedicated bare-metal servers (custom hardware configurations, priced per setup), colocation, CDN services, and a managed Cloud Applications Platform. Those are priced on a quote basis rather than fixed tiers, so if your archive has outgrown anything on the table, that's the conversation to have — 👉 [you can request a custom quote through their portal](https://bit.ly/SharKTech).

## Acronis Cloud Backup: the details that matter

The headline number is $4.00/month for 200GB of cloud backup storage. What that actually buys is Acronis Cyber Protect, which is a full backup platform rather than a simple sync tool: disk imaging, file-level backup, encryption, deduplication, and — the part consumer apps charge extra for — active anti-ransomware and anti-malware protection, URL filtering, and patch management. It backs up Windows, Linux, and macOS machines, plus mobile devices, and restores work through a web interface or mobile app.

The pricing structure rewards longer commitments, and it's worth reading carefully because the overage rates move inversely to the base price:

- **Monthly:** $4.00 for 200GB, then $0.02 per additional GB
- **Quarterly:** $8.00 per 3 months (about $2.67/month), then $0.04 per additional GB
- **Semi-annual:** $12.00 per 6 months ($2.00/month), then $0.06 per additional GB
- **Annual:** $24.00 per year ($2.00/month), then $0.12 per additional GB

Notice the trade-off. Committing annually halves your base cost but raises the per-GB overage rate sixfold. If you know your data footprint will stay under 200GB, the annual plan is straightforwardly cheaper. If you're backing up a growing file server and expect to blow past 200GB, the monthly plan's low $0.02/GB overage is the safer bet — 1TB of data on the monthly plan costs roughly $4 + 800GB × $0.02 = about $20/month, whereas the same 1TB on the annual plan runs $2 + 800GB × $0.12 ≈ $98/month in overage. That's the kind of invoice detail people discover after the fact, so it belongs in the decision up front.

A Files Sync & Share add-on is available if you also want storage-style behavior — file syncing and sharing across devices — priced at $0.03 per GB monthly (rising to $0.24 per GB on annual billing, with quarterly and semi-annual rates in between). Storage scales up to 100TB, and backups land in whichever of the five data center locations suits you.

For comparison: Liquid Web, a well-known managed hosting provider, lists Acronis Cyber Backups at $6/month for 100GB and $62/month for 1TB. Sharktech's $4 for 200GB undercuts that entry point considerably, which is presumably what they mean by "half the cost of competitors." Whether the gap holds at larger storage sizes depends on your overage mix, but at small scale it's real. If that fits your situation, 👉 [the Acronis backup plans are orderable directly through the portal](https://bit.ly/SharKTech).

## S3 Object Storage: for archives, media, and off-site copies

Object storage is the right tool when your data is write-once, read-rarely: photo libraries, video archives, database dumps, log retention, compliance copies. Sharktech's S3 service is API-compatible with the S3 standard, which matters more than it sounds — it means restic, Duplicacy, Veeam, rclone, Minio clients, and every backup tool that speaks S3 can point at it without custom integration work.

The flat per-TB rate (advertised $4.90/TB) with bandwidth included is the whole pitch. Hyperscalers charge by the gigabyte and then add egress fees when you pull data back out, which is how companies end up effectively trapped with a provider — moving 50TB out of AWS S3 costs over $1,000 in egress alone at standard rates. Sharktech's approach of charging for storage and including a bandwidth allowance (1TB–1PB depending on package, per their store listing) avoids that trap, and their cloud FAQ explicitly calls out ingress being free and egress fees being far below the major clouds.

There's also a durability angle: the S3 clusters are redundant across Sharktech's own data centers, and the service page notes 40G inbound and outbound connectivity, so restore speeds are limited by your own connection, not theirs.

## Rolling your own: VPS and Public Cloud as a backup backbone

There's a third approach the review roundups never mention: buy a cheap server and run your own backup stack. If you're comfortable with a command line, tools like restic, borg, or Syncthing on a $7.95/month VPS give you unlimited-ish control, and Sharktech's VPS plans are built for exactly this kind of tinkering — NVMe storage, Xeon Gold CPUs, 60Gbps DDoS protection included, 1TB+ of transfer.

The billing terms deserve attention: quarterly billing takes 25% off, semi-annual 35%, and annual 50%, which brings the entry VPS to an effective $3.98/month. One caveat from their own store: stock availability on specific configurations can run out, so a particular plan may show as unavailable at times — worth checking the portal for what's currently deployable.

The Public Cloud tiers are the scaled-up version of the same idea. Instead of a fixed VPS, you get a resource pool (CPU, RAM, and three storage tiers — NVMe for speed, SSD for balance, HDD for cheap bulk) that you carve into as many virtual machines as you like. Two details make it genuinely backup-friendly:

- **No vendor lock-in on your data.** You can download your server disk images at any time — for off-site backup, disaster recovery, or just to leave. That's rarer than it should be.
- **Bounded overage.** Public Cloud plans (except Enterprise and Custom) carry a maximum resource cap so an accidental runaway workload can't generate a surprise four-figure bill. Overage is billed hourly (for example, $0.0025/hr per CPU core, $0.00009/hr per GB of NVMe), the first public IPv4 is free, and egress beyond the included 5,000GB costs $0.002/GB with unlimited ingress.

For a self-managed backup server holding a few terabytes, a Small tier at $39/month with its 20TB+ bandwidth allowance covers more data movement than most people will ever need, and the HDD tier storage at up to 4800GB is the cheapest place to put bulk archives inside the cloud platform. If that route appeals, 👉 [the Public Cloud tiers are all configurable in the cloud portal](https://bit.ly/SharKTech).

## What customers actually say

Public reviews for Sharktech exist but the sample is small, so treat it accordingly. Trustpilot shows a 3.4/5 average across 13 reviews, and HostAdvice shows 3.5/5 across a similar-sized pool. The distribution skews toward the extremes: on the positive side, customers specifically praise the DDoS protection (one game-server operator reported absorbing 3–8Gbps attacks without downtime) and the responsiveness of the 24/7 support team, including one low-end forum review describing a year of DDoS protection with attacks successfully filtered. A HostAdvice benchmark review of the VPS product reported 6,000+ random IOPS and sub-millisecond network latency, backing up the NVMe claims.

On the negative side, there are dissatisfied customers too, including a scathing old forum complaint about the network. The honest read: individual experiences vary, the review base is too small to form a statistical consensus either way, and the strongest recurring positive theme is DDoS filtering and support access rather than marketing polish. The company's SLA guarantees 99.99% network uptime, and their VPS platform is advertised at 99.999% uptime with triple-redundant infrastructure.

## How to decide in sixty seconds

Strip away the feature lists and the decision mostly comes down to what you're protecting:

- **One personal laptop, budget first:** Backblaze at $6/month is the simplest answer in the consumer market.
- **Multiple devices, phones included, want disk imaging:** iDrive's ~$100/year for 5TB is the reviewers' consensus pick.
- **Servers, VMs, databases, or a business fleet:** Acronis Cloud Backup at $4/month for 200GB with $0.02/GB overage undercuts consumer business tiers on price and adds anti-ransomware tooling they mostly don't have. Choose the monthly plan if your data grows; annual if it won't.
- **Huge cold archives, media libraries, compliance retention:** S3 Object Storage at a flat per-TB rate with no per-device licensing, pointed at by whatever S3-compatible backup tool you already use.
- **Full control, comfortable with Linux:** a Smart VPS from $7.95/month (or $3.98 effective annually) running your own backup stack, with the option to export disk images whenever you want out.
- **Multiple sites, hybrid setups, MSP workloads:** the Public Cloud resource pools from $39/month, with multi-region deployment across five data centers.

And regardless of which service wins: keep the 3-2-1 rule intact. Whatever you buy online is the "one off-site copy" — make sure there's still a local backup on a second medium. The off-site copy is for the day everything else fails at once, not for everyday restores.

Whatever direction you lean, 👉 [you can compare all of Sharktech's backup, storage, and cloud plans directly in their portal](https://bit.ly/SharKTech) — the Acronis backup trial ordering takes a couple of minutes, and their support team answers configuration questions before you commit, which is more than most consumer backup services offer.

## Frequently asked questions

**Is Acronis backup from Sharktech the same as buying Acronis directly?** The underlying engine is Acronis Cyber Protect, but Sharktech resells it as a hosted service with their own per-GB pricing and their data centers as the storage backend. You manage backups through the standard Acronis interface and mobile apps; Sharktech handles the storage infrastructure and support.

**How much does 1TB of backup actually cost?** On the monthly Acronis plan, roughly $4 for the first 200GB plus about $16 for the additional 800GB — call it around $20/month. Compare that against your total across devices on consumer per-device pricing to see which side of the line you fall on.

**Can I use S3 storage with backup software I already have?** Yes, if it supports the S3 API, which covers most modern backup tools — restic, borg wrappers, Duplicacy, rclone, and the backup modules in most NAS and server software. The bandwidth allowance in each package matters more here than raw storage price, since backup jobs move a lot of data on schedule.

**Do I have to manage a server to use any of this?** No. The Acronis Cloud Backup and S3 Object Storage plans are managed services — you install the Acronis agent or point your tools at an S3 endpoint, and Sharktech runs the infrastructure. The VPS and Public Cloud tiers are the self-managed options for people who want that control.

**What happens to my data if I cancel?** Sharktech's cloud platform lets you download your server disk images at any time, and the S3 service is API-accessible for bulk retrieval, so you're not stuck exporting through a proprietary tool. Consumer backup services vary widely on this, and it's a fair question to ask any provider before committing a terabyte of your life to them.
