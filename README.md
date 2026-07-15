# BandwagonHost Tokyo VPS Full Guide: Which Tokyo Plan Should You Buy? CN2 GIA vs Softbank E-Commerce Compared — Specs, Pricing, China Latency, Setup & Promo Codes (All Plans Tabled)

If you've been typing "BandwagonHost Tokyo VPS" into a search box lately, you're probably in one of two boats: either you want a Japan-located box that hugs the Chinese mainland with embarrassingly low latency, or you've heard the name "搬瓦工" whispered in enough forums that you finally caved. Either way, you're in the right place. Let's walk through what BandwagonHost actually sells in Tokyo, how the plans differ, which one is worth your money, and how to not overpay at checkout.

## Why a BandwagonHost Tokyo VPS in the First Place?

Here's the honest reason Tokyo is such a crowded keyword: geography. A server sitting in Equinix TY8 is roughly 50–60 ms away from eastern China over a clean route, which is close enough that web pages feel local, SSH doesn't make you age in real time, and a small game server or proxy doesn't stutter. BandwagonHost (the brand behind the well-known "搬瓦工") runs not one but **two** distinct Tokyo datacenters, plus a third limited-edition Tokyo location that shows up in periodic restocks — and they're not the same product at all.

So when people search "BandwagonHost Tokyo VPS," they're really asking a bundle of smaller questions: *CN2 GIA or Softbank?* *E-Commerce or Ultra?* *Is the $49.99/quarter plan enough?* *Why is the CN2 GIA one $89.99/month?* This guide answers all of them, plan by plan, with the full official pricing pulled from BandwagonHost's order pages.

## The Three Tokyo Locations, Explained Simply

This is the part most articles gloss over, and it's the single most important thing to understand before you spend a dime.

| Tokyo Location | ID | Tier | Headline Network | Vibe |
|---|---|---|---|---|
| Equinix TY8 (E-Commerce) | JPTY_1 | E-Commerce | AMD+NVMe, Softbank + China Direct, 2.5–10 Gbps | The "value" Tokyo — big bandwidth, decent China routes |
| Equinix TY8 (Ultra / CN2 GIA) | JPTY_8 | Ultra | CN2 GIA peering, 1.2 Gbps | The "premium" Tokyo — best stability to China, lowest latency |
| Tokyo DC39v2 (Limited) | DC39v2 | Limited Edition | Mixed upstream, CMI tri-network return | The "flash sale" Tokyo — cheap annual, when in stock |

The short version: **JPTY_1 (E-Commerce)** gives you fat pipes and Softbank/China-direct routing at friendly prices. **JPTY_8 (Ultra)** is the no-compromise CN2 GIA box — stable as a rock to China, but priced like premium transit because, well, CN2 GIA transit genuinely costs that much (BandwagonHost openly notes CN2 GIA IP transit can run up to $120/Mbps in some markets). **DC39v2** is the limited-edition bargain that pops up in restocks and sells out fast.

## BandwagonHost Tokyo E-Commerce VPS Plans (JPTY_1, Equinix TY8)

This is the workhorse Tokyo line — AMD + NVMe storage, Softbank and China Direct peering, and link speeds climbing from 2.5 Gbps all the way to 10 Gbps on the bigger boxes. Billing starts quarterly on the small plans and goes monthly on the larger ones. Here's the full set, straight from the official order page:

| Plan | RAM | CPU | SSD | Transfer/mo | Link | Starting Price | Order |
|---|---|---|---|---|---|---|---|
| 20G E-Commerce | 1 GB | 2 vCore | 20 GB | 1 TB | 2.5 Gbps | $49.99 / quarter | [Order 20G Tokyo](https://bwh81.net/aff.php?aff=79616&pid=87) |
| 40G E-Commerce | 2 GB | 3 vCore | 40 GB | 2 TB | 2.5 Gbps | $89.99 / quarter | [Order 40G Tokyo](https://bwh81.net/aff.php?aff=79616&pid=88) |
| 80G E-Commerce | 4 GB | 4 vCore | 80 GB | 3 TB | 2.5 Gbps | $56.99 / month | [Order 80G Tokyo](https://bwh81.net/aff.php?aff=79616&pid=89) |
| 160G E-Commerce | 8 GB | 6 vCore | 160 GB | 5 TB | 5 Gbps | $86.99 / month | [Order 160G Tokyo](https://bwh81.net/aff.php?aff=79616&pid=90) |
| 320G E-Commerce | 16 GB | 8 vCore | 320 GB | 8 TB | 5 Gbps | $159.99 / month | [Order 320G Tokyo](https://bwh81.net/aff.php?aff=79616&pid=91) |
| 640G E-Commerce | 32 GB | 10 vCore | 640 GB | 10 TB | 10 Gbps | $289.99 / month | [Order 640G Tokyo](https://bwh81.net/aff.php?aff=79616&pid=92) |
| 1TB E-Commerce (12 TB) | 64 GB | 12 vCore | 1 TB | 12 TB | 10 Gbps | $549.99 / month | [Order 1TB Tokyo](https://bwh81.net/aff.php?aff=79616&pid=93) |
| 1TB E-Commerce (15 TB) | 64 GB | 12 vCore | 1 TB | 15 TB | 10 Gbps | $679.00 / month | [Order 15TB Tokyo](https://bit.ly/BandwagonHost) |
| 1TB E-Commerce (20 TB) | 64 GB | 12 vCore | 1 TB | 20 TB | 10 Gbps | $899.00 / month | [Order 20TB Tokyo](https://bit.ly/BandwagonHost) |

A couple of things worth pointing out. The two smallest plans bill **quarterly**, which is nice if you hate committing a year upfront. From the 80G plan upward it switches to monthly billing, and the link speed jumps to 5 Gbps at the 160G tier and 10 Gbps at 640G — so you're not just buying more RAM, you're buying a fatter pipe. The three 1 TB / 64 GB boxes at the top are essentially the same machine with progressively more monthly transfer (12 → 15 → 20 TB); pick the one that matches your actual bandwidth burn.

If you just want a Tokyo box for a personal site, a proxy, or light dev work, the **20G or 40G E-Commerce plan** is honestly enough. The 👉 [40G Tokyo E-Commerce plan](https://bwh81.net/aff.php?aff=79616&pid=88) at $89.99/quarter is the sweet spot most people land on.

## BandwagonHost Tokyo Ultra VPS — CN2 GIA Plans (JPTY_8, Equinix TY8)

This is the "I will pay for peace and quiet" tier. Ultra is BandwagonHost's no-compromise China connectivity line — same Equinix TY8 building, but routed over **CN2 GIA peering** (AS4809) for the steadiest possible path into mainland China. The trade-off is bandwidth: it's capped at **1.2 Gbps**, and the prices are roughly double the E-Commerce equivalents. That's not BandwagonHost being greedy; that's literally what CN2 GIA transit costs to deliver.

| Plan | RAM | CPU | SSD | Transfer/mo | Network | Price | Link |
|---|---|---|---|---|---|---|---|
| Tokyo Ultra 1 | 2 GB | 2 vCore | 40 GB | 500 GB | 1.2 Gbps | $89.99 / month | [Order Ultra 1](https://bwh81.net/aff.php?aff=79616&pid=95) |
| Tokyo Ultra 2 | 4 GB | 4 vCore | 80 GB | 1 TB | 1.2 Gbps | $155.99 / month | [Order Ultra 2](https://bwh81.net/aff.php?aff=79616&pid=96) |
| Tokyo Ultra 3 | 8 GB | 6 vCore | 160 GB | 2 TB | 1.2 Gbps | $299.99 / month | [Order Ultra 3](https://bit.ly/BandwagonHost) |
| Tokyo Ultra 4 | 16 GB | 8 vCore | 320 GB | 4 TB | 1.2 Gbps | $589.99 / month | [Order Ultra 4](https://bit.ly/BandwagonHost) |
| Tokyo Ultra 5 | 32 GB | 10 vCore | 640 GB | 6 TB | 1.2 Gbps | $989.99 / month | [Order Ultra 5](https://bit.ly/BandwagonHost) |
| Tokyo Ultra 6 | 64 GB | 12 vCore | 1 TB | 8 TB | 1.2 Gbps | $1,889.99 / month | [Order Ultra 6](https://bit.ly/BandwagonHost) |

A nice quirk of the Ultra tier: these same products can be migrated between **Hong Kong, Tokyo, Osaka and Singapore** CN2 GIA datacenters for free from the KiwiVM panel, with no data loss. So if Tokyo latency isn't quite right for your users, you're not locked in — you can hop to HK or Singapore later. (The E-Commerce JPTY_1 box, by contrast, lives in that Tokyo building but migrates within the E-Commerce location set.)

## The Limited-Edition "The Tokyo Plan" (DC39v2)

Every so often BandwagonHost drops a flash-sale Tokyo box in the **DC39v2** location, branded "The Tokyo Plan" and "The Tokyo Plan v2." These are absurdly cheap for what you get — but they're genuinely limited, sell out in hours, and **cannot be migrated** to other datacenters. Treat them as a bonus, not your production backbone.

| Plan | RAM | CPU | SSD | Transfer/mo | Link | Price | Order |
|---|---|---|---|---|---|---|---|
| The Tokyo Plan (v1) | 1 GB | 1 vCore | 20 GB | 500 GB | 2.5 Gbps | $79 / year | [Check Tokyo Plan](https://bit.ly/BandwagonHost) |
| The Tokyo Plan v2 | 2 GB | 2 vCore | 40 GB | 1 TB | 5 Gbps | $99 / year | [Check Tokyo Plan v2](https://bit.ly/BandwagonHost) |

The v2 doubled the v1's specs for only $20/year more — 2 GB RAM, 40 GB SSD, 1 TB transfer on a 5 Gbps port, with a return route that runs over **CMI tri-network direct** (China Mobile International) into the mainland. If you see either of these in stock, the v2 is the obvious grab. The catch is exactly what you'd expect from a flash sale: by the time you finish reading this sentence, it might already be gone. The BandwagonHost real-time stock tracker is your friend here.

## CN2 GIA vs Softbank vs CMI: Which Route Do You Actually Need?

This is where a lot of Tokyo VPS buyers freeze, so let's make it concrete.

- **CN2 GIA (Ultra, JPTY_8)** — China Telecom's premium AS4809 network. The most stable, lowest-packet-loss path into China. Best for VoIP, video calls, gaming, anything where a dropped packet is visible. Expensive because the underlying transit is expensive. If your users are mostly on China Telecom and quality matters more than price, this is the one.
- **Softbank + China Direct (E-Commerce, JPTY_1)** — Softbank peering for Japan-side and a "China Direct" blend for the mainland. Cheaper, much fatter bandwidth (up to 10 Gbps), and perfectly fine for web hosting, CDN origins, and most general use. Peak-hour jitter is a bit higher than CN2 GIA but rarely a dealbreaker for sites.
- **CMI tri-network (DC39v2 limited)** — the return path lands on China Mobile International, which is great for Mobile users and decent for the others. It's the budget pick and performs above its price when it's available.

Real-world latency from the DC39v2 limited box, as measured by community route tests, lands around **42–55 ms to Shanghai Mobile**, **48–56 ms to Beijing Unicom**, and climbs to **170+ ms on congested Telecom routes during peak hours** — a reminder that no single Tokyo route wins all three carriers simultaneously. That's exactly why the Ultra CN2 GIA box exists: it sacrifices bandwidth to buy consistent Telecom performance.

## How to Pick the Right BandwagonHost Tokyo VPS

Here's a non-exhaustive map from "what you're doing" to "what you should buy":

1. **Personal blog / proxy / light dev** → 20G or 40G E-Commerce (JPTY_1). Cheap, quarterly billing, 2.5 Gbps is plenty. Start 👉 [here with the 40G plan](https://bwh81.net/aff.php?aff=79616&pid=88).
2. **Small business site or app for Chinese users, budget-conscious** → 80G or 160G E-Commerce. The 5 Gbps pipe at the 160G tier ($86.99/mo) is genuinely good value.
3. **VoIP, video, game server, or anything latency-sensitive to China Telecom** → Tokyo Ultra CN2 GIA. Start with 👉 [Ultra 1 ($89.99/mo)](https://bwh81.net/aff.php?aff=79616&pid=95) and scale up only if you need the resources.
4. **High-traffic site / CDN origin / multiple services** → 320G E-Commerce and up, or Ultra 3+ if China stability is the priority over raw bandwidth.
5. **"I just want the cheapest Tokyo box that exists"** → Watch for the The Tokyo Plan v2 restock at $99/year. Don't build a business on it, but for a side project it's unbeatable.

## Promo Codes: Don't Pay Full Price at Checkout

BandwagonHost runs a recurring promo code system, and the one that has held up the longest across multiple independent trackers is **`BWHCGLUKKB`**, good for a **6.77% recurring discount** on all VPS plans — new purchases *and* renewals. That "recurring" part matters: it's not a one-time first-invoice discount, it sticks around for the life of the service, which adds up over years on an annual plan.

A few other codes float around (variations in the 5.5%–6.77% range), but `BWHCGLUKKB` is the most consistently verified. Enter it on the checkout page before paying. If a code stops working, it's usually been rotated — the discount ceiling has hovered around 6.77% for a while, so don't expect anything dramatically bigger.

Combined with quarterly billing on the small E-Commerce plans, that 6.77% off makes the entry-level Tokyo box genuinely cheap for what it is.

## Setup and Management: KiwiVM in a Nutshell

Every BandwagonHost VPS is managed through **KiwiVM**, their in-house control panel, and it's refreshingly competent for a self-managed provider. After activation you get:

- Start/stop, OS reload (AlmaLinux, RockyLinux, CentOS, Debian, Ubuntu, CentOS Stream, Fedora — plus a large ISO library on request)
- Emergency console access, instant rDNS/PTR setup
- **Free datacenter migration** between locations in your tier (no data loss) — especially handy on the Ultra CN2 GIA products
- Snapshots, usage stats, and an API for the automation-inclined

The service is **self-managed**, which is how BandwagonHost keeps prices down — there's no cPanel hand-holding, but if you're comfortable in a terminal you'll feel right at home. All plans include full root access, tun/tap (PPP and VPN support), 1–10 Gbps uplinks, 99.9% uptime guarantee, and a 30-day refund policy if it's not for you.

## Frequently Asked Questions

**Is the BandwagonHost Tokyo VPS good for users in China?** Yes — that's literally its reason for existing. The Ultra (CN2 GIA) tier is the most stable choice for China Telecom users; the E-Commerce tier is the value choice with much more bandwidth; the limited DC39v2 box is the budget pick when it's in stock.

**What's the difference between Tokyo E-Commerce and Tokyo Ultra?** Same building (Equinix TY8), different network tier. E-Commerce (JPTY_1) gives you up to 10 Gbps over Softbank + China Direct at lower prices. Ultra (JPTY_8) gives you CN2 GIA peering at 1.2 Gbps for the steadiest China path, at roughly double the cost.

**Can I move my Tokyo VPS to another city later?** E-Commerce plans migrate within the E-Commerce location set; Ultra CN2 GIA plans can migrate freely between Hong Kong, Tokyo, Osaka and Singapore. The limited DC39v2 "Tokyo Plan" boxes **cannot** be migrated — they're locked to that datacenter.

**Does the promo code work on renewals?** `BWHCGLUKKB` is recurring, so yes — it applies on every renewal, not just the first invoice.

**Why is CN2 GIA so much more expensive?** Because CN2 GIA transit itself is expensive (BandwagonHost cites figures up to $120/Mbps in some markets) and capacity is limited. You're paying for stability and low packet loss into China, not for raw megabytes.

## The Bottom Line

If you searched "BandwagonHost Tokyo VPS," the honest summary is this: there isn't one Tokyo VPS, there are three, and the right one depends on whether you're optimizing for **price and bandwidth** (E-Commerce JPTY_1), **stability to China** (Ultra CN2 GIA JPTY_8), or **a bargain that might vanish tomorrow** (the DC39v2 limited Tokyo Plan). For most readers, the 👉 [40G Tokyo E-Commerce plan](https://bwh81.net/aff.php?aff=79616&pid=88) is the sensible default; for anyone running something latency-sensitive into mainland China, the 👉 [Tokyo Ultra CN2 GIA entry plan](https://bwh81.net/aff.php?aff=79616&pid=95) is worth every extra dollar. Whichever you pick, paste `BWHCGLUKKB` at checkout and let the 6.77% recurring discount do its quiet little work on every renewal after that.
