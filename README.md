# $5 VPS: What You Actually Get, Which Plans Double at Renewal, and the Right Pick for a Blog, VPN or Bot

Five dollars a month buys 1–2 vCPU, 1–4 GB of RAM, 20–60 GB of SSD or NVMe and 1–2 TB of transfer as of November 2026. That covers a small WordPress site, a personal VPN, a Discord bot or a box for learning Linux. It does not cover a busy store, a large database or anything that pins a core for minutes at a time.

LightLayer sits at the front of that range. Its entry plan is **$4.00/mo** for 1 core, 1 GB RAM and 50 GB SSD with unmetered transfer on a 100 Mbps port, and its annual plans in Manila and Taiwan come to **$24.99/year**, roughly $2.08 a month. Same specs, one twelfth of the monthly bill if you can commit to a year.

The number that decides whether a cheap VPS stays cheap is the renewal price. A2 Hosting's $3.49/mo plan renews at $8.99/mo, a 2.6× jump. AccuWebHosting's $4.80/mo plan renews at $9.71/mo. Both look like $5 VPS plans on the pricing page and neither is one after the first term. Below you'll find the plans that hold their price, the ones that don't, and how to tell which is which before you pay.

> **Quick pick:** LightLayer Startup at $4.00/mo (1 core, 1 GB, 50 GB SSD, unmetered 100 Mbps) for a first VPS, or the Manila/Taiwan annual plans at $24.99/year if you're keeping it a year. Both are published as flat rates rather than first-term teasers.
> 👉 [See LightLayer's current plans and locations](https://account.lightlayer.net/?affid=74)

## LightLayer's plans at this budget

LightLayer sells by location and network route, so the same 1 core / 1 GB / 50 GB box shows up at several prices. The route decides the price and the latency to your users.

| Plan | Cores / RAM / Disk | Transfer | Price | Order |
| --- | --- | --- | --- | --- |
| Startup | 1 core / 1 GB / 50 GB SSD | 100 Mbps, unmetered | $4.00/mo | [ Order Startup](https://account.lightlayer.net/index.php?/cart/los-angeles/&affid=74) |
| Pay As You Go | 2+ cores / 2 GB+ / scalable | 200 Mbps+ | from $5.60/mo | [ Configure a larger box](https://account.lightlayer.net/index.php?/cart/specialoffer/&affid=74) |
| Manila annual | 1 core / 1 GB / 50 GB SSD | Unmetered | $24.99/yr (~$2.08/mo) | [ Order the Manila annual plan](https://account.lightlayer.net/index.php?/cart/manila/&affid=74) |
| Taiwan annual | 1 core / 1 GB / 50 GB SSD | Unmetered | $24.99/yr (~$2.08/mo) | [ Order the Taiwan annual plan](https://account.lightlayer.net/index.php?/cart/taiwan/&affid=74) |
| Los Angeles annual, Global / Standard / Premium route | 1 core / 1 GB / 50 GB SSD | Unmetered | $29.99 / $39.99 / $49.99 per year ($2.50–$4.17/mo) | [ Compare the Los Angeles routes](https://account.lightlayer.net/index.php?/cart/los-angeles/&affid=74) |

The Los Angeles Premium route is the one to look at if your traffic comes from Asia and the Global route tests poorly for you. Standard BGP transit is cheaper and fine for a worldwide audience with no particular Asia weighting.

One plan falls outside this budget and is worth naming so you don't go hunting for it: the Taiwan premium-network cart lists a 1 vCPU / 1 GB / 50 GB SSD configuration with 10 Mbps unmetered transfer from **$9.00/mo**. Premium routing costs more than the $5 line, and on a 10 Mbps port it is aimed at a different job than a $4 blog box.

Two things to check before you pay. LightLayer's published refund policy covers provider-side faults only, so a change of mind after setup is not a refund event. And the annual rate is quoted per year, which makes the monthly equivalent easy to compare but also means the whole year is committed up front. Confirm the renewal rate with support before you stack multiple terms.

## What $5 buys across the market right now

Prices below were checked on 12 November 2026 by VPSScouter and StackRates, and refreshed on 12 November 2026 at 05:03 PM UTC by ServerSearcher. Euro plans are shown at the 11 November 2026 conversion rate and before tax.

| Provider · plan | RAM / vCPU / Disk | Transfer | Price | Billing |
| --- | --- | --- | --- | --- |
| RackNerd 4 GB KVM | 4 GB / 3 / 60 GB SSD | 7 TB | $5.00/mo | $60/yr up front, renews at the same price |
| Database Mart Express Linux | 4 GB / 2 / 60 GB SSD | Unmetered, 100 Mbps | $4.19/mo | Monthly, shared IP |
| RackNerd 2 GB KVM | 2 GB / 2 / 35 GB SSD | 5 TB | $3.00/mo | $36/yr, renews at the same price |
| InterServer 1 Slice | 2 GB / 1 / 40 GB SSD | 2 TB | $3.00/mo | Billed monthly, $1.50 first month |
| InterServer KVM Storage 1 Slice | 2 GB / 1 / **1 TB HDD** | 2 TB | $3.00/mo | Billed monthly, $1.50 first month |
| Vultr vc2-1c-0.5gb-v6 | 0.5 GB / 1 / 10 GB SSD | 0.5 TB | $2.50/mo | Hourly/monthly |
| netcup VPS nano G11.5s | 2 GB / 2 / 60 GB SSD | Unmetered | €3.10/mo (~$3.45) | Monthly, before tax |
| RackNerd 1 GB KVM | 1 GB / 1 / 20 GB SSD | 3 TB | $1.83/mo | $21.96 up front for a year |

RackNerd's 1 GB plan shows $21.96 up front on VPSScouter and $21.99 on StackRates, both checked the same day. The three-dollar-cent gap is a listing difference, not a promo, so don't treat either figure as more authoritative than the other.

The same core count and RAM can land you a very different machine. Database Mart gives 4 GB of RAM for $4.19 but caps you at a 100 Mbps shared port. InterServer gives you a terabyte of storage for $3.00 but it's a mechanical disk, and low IOPS on an HDD is one of the specific warnings HostAdvice raises about ultra-cheap plans. netcup gives 2 GB and 60 GB SSD with unmetered transfer for about $3.45 before tax. You get to pick one of memory, disk or bandwidth at this price. You don't get all three.

### Why the "cheapest" number changes depending on who you ask

Three trackers published three different minimum prices on the same day, and all three are correct within their own scope.

StackRates leads with $0.91/mo from DediRock's yearly promo, a flash-sale annual plan with no published renewal price. VPSScouter's floor is $1.83/mo on RackNerd's 1 GB plan, which is a 24-month average including renewal. ServerSearcher starts at $2.50/mo because it only tracks 11 plans from 6 providers and excludes promo-only sellers entirely.

If you're shopping on the headline number, you're comparing three different definitions. Pick the definition that matches how long you plan to keep the server, then compare inside that.

## Renewal is where the $5 plan stops being $5

This is the part that rarely makes it into the comparison table. Every figure below is from VPSScouter's listing checked 12 November 2026.

| Plan | Intro price | Renewal | Multiple |
| --- | --- | --- | --- |
| A2 Hosting Self Managed Linux 2 GB | $3.49/mo, 3-year term, $125.64 up front | $8.99/mo | 2.6× |
| AccuWebHosting VPS Edge | $4.80/mo, 2-year term, $115.20 up front | $9.71/mo | 2.0× |
| IONOS VPS S+ | $5.00/mo, 1-year term, $60.00 up front | $6.00/mo | $5.50/mo averaged over 24 months |
| Bluehost NVMe 2 | $4.49/mo, 2-year term | $5.69/mo | 1.3× |
| HostGator Snappy 1000 | $3.82/mo, 2-year term | $4.95/mo | 1.3× |
| Time4VPS Linux 2 | $2.50/mo, 1-year term, $30.00 up front | Not published; estimated $5.63/mo | $4.07/mo averaged over 24 months |

Run the arithmetic over five years and A2 Hosting's $3.49 plan costs $125.64 for the first 36 months plus $215.76 for the next 24, which is $341.40 total, or **$5.69/mo**. AccuWebHosting's $4.80 plan comes to $464.76 over the same period, **$7.75/mo**. Both started under five dollars.

The conversion is the same one HostAdvice spells out: $48 a year is $48 ÷ 12 = $4 a month. Do that for year one and for year two separately, and the cheap plan that isn't cheap shows up immediately.

Plans that renew at the same price are worth paying a little more for up front. RackNerd's 1 GB, 2 GB and 4 GB plans all renew at their initial rate. So do Raff Technologies' Cost-Optimized 1 vCPU / 2 GB at $3.74/mo and Namecheap's Spark at $3.88/mo. LightLayer quotes its annual plans as a yearly rate, which lets you budget the term exactly; ask support what happens at renewal before you prepay more than one year.

👉 [Check the LightLayer Startup plan at $4.00/mo](https://account.lightlayer.net/index.php?/cart/los-angeles/&affid=74)

## Which plan fits the job

**Personal VPN or learning Linux.** 1 GB of RAM is enough. LightLayer Startup at $4.00/mo, RackNerd 1 GB at $1.83/mo effective, or Vultr at $2.50/mo if you want hourly billing and 30-second deploys. You will not notice the difference between 1 GB and 2 GB running WireGuard and a shell.

**A small WordPress site or blog.** 1–2 GB with NVMe or SSD and a caching layer. HostAdvice's guidance is 1–2 GB for PHP apps with proper caching and a tuned MySQL config, and that matches the plan sizes here. LightLayer's $24.99/year Taiwan or Manila plan fits this if your readers are in Asia; the $29.99 Los Angeles Global plan fits a mixed audience. Pick a plan with NVMe over one with more disk on an HDD.

**Docker, self-hosted apps, a test lab.** 2 GB is the practical floor once you run a database alongside an app, and 4 GB saves you from swapping. Database Mart's Express plan at $4.19 gives 4 GB and 60 GB SSD; RackNerd's 4 GB at $5.00/mo adds three cores, 60 GB SSD and 7 TB of transfer with a same-price renewal. Those two are the strongest $5-and-under options for memory.

**Bulk storage.** InterServer's KVM Storage plan at $3.00/mo is the only sub-$5 plan here with a terabyte of disk, and it's an HDD. Fine for backups, archives and media dumps. Bad for a database.

**Unmetered transfer.** netcup's nano G11.5s gives 2 cores, 2 GB and 60 GB SSD with unmetered bandwidth for about €3.10/mo before tax. Database Mart and LightLayer both ship unmetered plans too, with the port speed as the real limit.

**Traffic from Asia-Pacific.** This is the case for LightLayer over the US-centric budget hosts. Taiwan, Manila, Hong Kong and Los Angeles routes exist as separate order pages, and the Los Angeles Premium route is priced at $49.99/year specifically because the transit is better into Asia.

## What to skip

DediRock appears four times in StackRates' under-$5 list at $0.91 to $2.92/mo. The same page carries a reader note stating that DediRock servers lost customer data more than once in late 2025 and early 2026, and that the flash-sale plans publish no renewal price. That's a third-party reader warning rather than a test result, and it's enough to keep your data somewhere else.

HostAdvice's red flags for this price band are worth memorising: HDD instead of SSD or NVMe, old CPU generations, very low IOPS, and uptime promises that no budget provider can back. Add a renewal price that isn't published anywhere.

Whatever you pay, keep your own backups off the server. VPSScouter says it plainly at the end of its list, and a $3 plan with a $0 backup habit is the most expensive combination in this article.

## FAQ

**Can a $5 VPS run WordPress?** Yes, with 1–2 GB of RAM and a caching plugin. Expect CPU throttling during traffic spikes on shared cores, and keep the database small.

**How much cheaper is annual billing?** On LightLayer, $24.99/year works out to about $2.08/mo against $4.00/mo monthly. On RackNerd, $60/year for the 4 GB plan is $5.00/mo with no monthly option priced lower.

**Will the price go up when I renew?** Sometimes by a lot. A2 Hosting renews at 2.6× the intro rate and AccuWebHosting at 2.0×. RackNerd, Raff Technologies and Namecheap renew at the same rate they sell at.

**Do shared cores get throttled?** They can, under sustained load. Light workloads like a blog or a VPN rarely trigger it; compiling, transcoding and scraping do.

**Is $5 enough for Docker?** For two or three small containers, yes. Watch the disk more than the RAM, because images and volumes fill 20–30 GB faster than you expect.

## Before you order

Match the plan to the job rather than to the headline price. A VPN or a learning box needs 1 GB and nothing more, so LightLayer Startup at $4.00/mo or the $24.99/year Manila and Taiwan plans are the sensible defaults, and paying more buys you nothing you'll use. Running a database alongside an app means 2 GB minimum, which puts Database Mart's $4.19 plan or RackNerd's $5.00 plan ahead. Needing a terabyte of disk means accepting a mechanical drive.

Three things to confirm at checkout: the billing cycle you're actually signing (monthly versus a multi-year prepay), the renewal price in writing, and whether the quoted figure includes tax. Euro-denominated plans in this price range are usually quoted before tax.

👉 [Start with the LightLayer plan that matches your budget](https://account.lightlayer.net/?affid=74)
