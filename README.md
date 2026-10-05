# soax proxy: What You Actually Pay Per GB, and a Cheaper Pay-As-You-Go Route for Small or Uneven Volumes

SOAX's pricing page opens with a promise: "No sales theatre. No pricing games." The plan table underneath it is honest about how the bill works — which is more than most proxy vendors manage. It's also structured in a way that means the number you saw in a headline is probably not the number you'll pay.

If you're researching SOAX proxies, there are two reasonable questions hiding behind that search: *what does this actually cost me at my volume*, and *is there something cheaper that does the same job*. Both are answerable with the published numbers. So let's do the arithmetic instead of the marketing.

## What SOAX Is, in Plain Terms

SOAX is a proxy provider best known for residential IPs — the network advertises 155M+ residential addresses across 195+ locations, with country-level targeting and finer filters (city, ASN) available depending on your product and plan. It supports rotating and sticky sessions over HTTP/HTTPS and SOCKS5.

Two structural things matter more than the pool size when you're deciding:

**It bills in credits, not gigabytes.** One credit is roughly $1 of usage, and you spend one prepaid credit balance across every product on your account. The plan you buy sets the *rate* at which those credits drain; it doesn't bundle a data allowance.

**It sorts countries into three price tiers.** Tier 1 is the expensive band — 32 countries including the US, UK, Japan, Germany, France and Australia. Tier 2 covers roughly 60 more. Tier 3 is everything else. Per SOAX's own documentation, routing through Tier 1 instead of Tier 3 can cost **up to 8× more per GB on the same plan**.

That last sentence explains almost every confusing SOAX price you'll read online.

## SOAX Pricing: Two Dials, One Bill

Here's the current plan structure from SOAX's pricing page. All figures are per month and exclude VAT.

| Plan | Monthly fee | Tier-1 rate | Roughly what the fee covers in Tier-1 traffic |
| --- | --- | --- | --- |
| Sandbox | $0 | $5.00/GB | Nothing included — you top up first, minimum $25 |
| Builder | $200 | $3.00/GB | ~66 GB |
| Team | $500 | $2.20/GB | ~227 GB |
| Scale | $1,500 | $1.50/GB | ~1 TB |
| Enterprise | $3,000+ | from $0.85/GB | Volume bands: 0.85 credits/GB for the first 5 TB, then 0.75, then 0.50 |

Read the fourth column carefully, because it's where the pricing model becomes concrete. Because the plan fee is prepaid credit rather than a data bundle, $200 on Builder buys you about 66GB of US-targeted traffic at $3/GB — not 200GB. SOAX's own pricing calculator shows the same thing from the other direction: 100GB on Builder, with $100 in extra credits, comes to $300 total. An effective rate of $3/GB at that volume.

A few operational details worth knowing before you build a budget:

- **Credits roll over for 60 days** (360 days on Enterprise). Buy at the end of a quiet month and they don't vanish immediately, but they aren't permanent either.
- **Sandbox is limited to one package and one seat**, with a $25 minimum top-up. It's a testing tier, not a production one.
- **There's no free traffic tier.** The residential page offers a $1.99 trial — three days, 400MB. Small, but enough to check whether your target site actually accepts the IPs before you commit $200.

## The Part Most SOAX Reviews Skip

Divide the plan floor by your usage and the picture changes fast.

At **5GB a month**, you have two options. Sandbox at $5/GB lands you at exactly the $25 minimum top-up. Builder, at $200, would work out to **$40/GB** — the plan fee divided by five gigabytes of traffic. That's not a criticism of SOAX so much as it is a description of what a $200 monthly commitment means at small volume. Third-party cost teardowns that ran the same math reached the same conclusion, which is why SOAX's effective rate appears to swing wildly between "$40/GB" and "$4/GB" depending on whose review you read. Neither number is wrong; they describe different volumes.

At **50GB a month**, Builder still costs $200 for roughly 66GB of headroom. You're paying $4/GB in effect, with spare credits left over.

At **1TB a month**, Scale at $1,500 gets you there at $1.50/GB.

And the low rates at the bottom of the page? Those sit behind the $3,000 Enterprise plan *and* typically Tier-3 geography. Enterprise Tier-1 traffic starts at 0.85 credits/GB on the first 5TB block; Tier-3 traffic is cheaper still — around $0.35/GB on the largest bands. Both numbers are real. Neither is available to someone buying a hundred gigabytes of US residential IPs.

> If your monthly volume is under about 60GB and your targets are in Tier-1 countries, you are paying SOAX's highest effective rate. That's the honest summary of the tool above.

## Where SOAX Genuinely Earns the Money

It would be lazy to end there, because SOAX isn't overpriced for what it is. It's priced for a buyer who needs specific things:

**Targeting depth.** Country, region, city and ASN-level filtering is the real product here. If you're verifying ads in one metro area, testing a carrier-gated signup flow, or need a specific ISP's residential range, that granularity is worth more than $1/GB in saved retries.

**A large residential pool.** 155M+ addresses is bigger than most mid-market pools, and larger pools mean less IP reuse on heavily defended targets.

**Committed-scale pricing.** If you're genuinely routing multiple terabytes a month through Tier-3 geographies, the Enterprise bands undercut most of the market.

**Pay-as-you-go availability without a subscription.** Sandbox has no monthly fee. It's expensive per GB, but there's no recurring charge to cancel.

The mismatch isn't with SOAX's product. It's with the buyer whose monthly traffic swings between 8GB and 40GB, targets US and European sites, and has no interest in a $200 floor. For that person, the plan structure is doing the opposite of what they need.

## The Pay-As-You-Go Alternative: DataImpulse at $1/GB

This is where DataImpulse fits, and the contrast is mostly about *shape* rather than features. It's pay-as-you-go with no monthly minimum — you buy gigabytes, and they don't expire. Nothing resets at the end of a billing cycle, so a quiet month costs you nothing instead of costing you $200.

The network is 90M+ ethically sourced IPs across 195 countries, with a published 99.51% success rate and a 4.8/5 G2 rating. It supports HTTP/HTTPS and SOCKS5, rotating sessions on ports 823/824, and sticky sessions from 1 to 120 minutes (30 by default) on ports 10000–20000.

Here's the full published pricing across all four product types:

| Proxy type | Package | Traffic | Price | Effective rate | Billing | Get it |
| --- | --- | --- | --- | --- | --- | --- |
| Residential | Intro | 5 GB | $5 | $1.00/GB | One-time, no subscription | Start with the $5 intro plan |
| Residential | Basic | 50 GB | $50 | $1.00/GB | One-time | Buy 50 GB of residential traffic |
| Residential | Advanced | 1 TB | $800 | $0.80/GB | One-time, 20% volume discount | Check the 1 TB residential tier |
| Residential | Custom | 5 TB+ | Custom quote | From $0.70/GB | Custom | Request custom residential pricing |
| Datacenter | Intro | 10 GB | $5 | $0.50/GB | One-time | Test datacenter proxies for $5 |
| Datacenter | Standard | 100 GB | $50 | $0.50/GB | One-time | Buy 100 GB of datacenter traffic |
| Datacenter | Volume | 1 TB | $450 | $0.45/GB | One-time | See the 1 TB datacenter tier |
| Datacenter | Custom | 5 TB+ | From $2,250 | Custom | Custom | Ask about datacenter volume pricing |
| Mobile | Intro | 2.5 GB | $5 | $2.00/GB | One-time | Try mobile proxies from $5 |
| Mobile | Standard | 25 GB | $50 | $2.00/GB | One-time | Buy 25 GB of mobile traffic |
| Mobile | Volume | 1 TB | $1,600 | $1.60/GB | One-time | See the 1 TB mobile tier |
| Mobile | Custom | 5 TB+ | From $8,000 | Custom | Custom | Ask about mobile volume pricing |
| Premium residential | Intro | 1 GB | $5 | $5.00/GB | One-time | Try premium residential proxies |
| Premium residential | Standard | 10 GB | $50 | $5.00/GB | One-time | Buy 10 GB of premium residential |
| Premium residential | Custom | 5 TB+ | From $20,000 | Custom | Custom | Request premium residential pricing |

A couple of caveats so this table isn't misleading. **Country targeting is included** in the base rate; state, city, ZIP and ASN filters are billed at double the standard per-GB rate on the standard residential product, according to AIMultiple's pricing breakdown — so a city-level campaign costs you $2/GB, not $1/GB. And premium residential is the tier that includes a dedicated account manager and all targeting options without the surcharge, which is why it starts at $5/GB.

First purchases come with a 7-day money-back guarantee for card payments, provided you've used less than 80% of the traffic. Crypto purchases on intro plans aren't refundable. The minimum purchase is $5 — there's no free tier, and no subscription to forget about.

## Same Job, Different Bill

Put the two side by side at volumes people actually buy. This assumes US or Western European targets, which puts SOAX traffic in Tier 1.

| Monthly volume | SOAX | DataImpulse |
| --- | --- | --- |
| 5 GB | $25 on Sandbox ($5/GB), or $200 on Builder | $5 |
| 50 GB | $200 on Builder → $4/GB effective | $50 |
| 1 TB | $1,500 on Scale → $1.50/GB | $800 |

At 5GB the gap is $20 versus $195. At 50GB it's $50 versus $200. At 1TB it narrows to a bit under 2×, which is roughly what you'd expect once both providers are selling at volume.

The comparison isn't quite apples-to-apples, and it's worth being explicit about why. SOAX's Tier-3 traffic is substantially cheaper than DataImpulse's flat rate — a gigabyte from the Philippines on an Enterprise plan costs a fraction of what a US gigabyte does. If your work is genuinely concentrated in emerging markets and you're buying terabytes, SOAX's tiering works *for* you. DataImpulse charges one rate everywhere, which is a worse deal in that specific scenario and a simpler one in every other.

## Which One Fits Your Workload

Match the tier to the job and both providers make sense in different places:

**Pick SOAX if** you need metro-level or ASN-level targeting as a core capability, you're running five or more terabytes a month through Tier-2 and Tier-3 geographies, or you need an enterprise SLA and compliance documentation.

**Pick DataImpulse if** your monthly traffic varies, your volume is under roughly 60GB, you're targeting US/UK/EU sites, or you want to test residential IPs on your own targets without a recurring charge. The $5 entry point is the practical argument — you can measure your cost per *successful request* before committing anything meaningful.

**Consider both if** you're at scale with mixed geography. Bulk Tier-3 collection and defended Tier-1 targets behave differently enough that routing each to the cheaper provider that clears it is a legitimate strategy, not an awkward compromise.

One note on measuring: cost per gigabyte is the number vendors compete on, and cost per *successful request* is the number that hits your invoice in practice. A pool that gets blocked on half your requests at $1/GB is more expensive than a cleaner pool at $2/GB. Test on your actual targets before you scale either way.

## FAQ

**Is there a free SOAX plan?**
Yes, in a limited sense. The Sandbox plan carries no monthly fee, but traffic is billed from the first gigabyte at $5.00/GB in Tier 1, the minimum top-up is $25, and it's capped at one package and one seat.

**How much does SOAX cost per GB?**
It depends on two variables at once. In Tier-1 countries the rate runs from $5.00/GB on Sandbox down to $3.00 on Builder, $2.20 on Team, $1.50 on Scale, and from $0.85 on Enterprise volume bands. Tier-3 traffic is cheaper — as low as roughly $0.35/GB at the highest volumes.

**Does SOAX have a pay-as-you-go option?**
Sandbox is the closest thing: no monthly fee, credits purchased up front. Above that, every plan charges a monthly fee, and your credits need to be used within 60 days.

**What's the cheapest SOAX alternative for small volumes?**
On published rates, DataImpulse at $1/GB residential with non-expiring traffic and a $5 minimum purchase. At 5GB that's $5 versus a $200 SOAX plan fee — though SOAX's city and ASN targeting is the more capable of the two, so the trade is real rather than free.

**Does DataImpulse have a free trial?**
No free tier. The $5 intro gets you 5GB residential, 10GB datacenter, 2.5GB mobile or 1GB premium residential, and first purchases are covered by a 7-day money-back guarantee if you've used under 80% of the traffic.

Pricing on both sides is published and changes without much notice, so confirm the current rate on the checkout page before you buy. If your requirement is deep geo-targeting at enterprise scale, SOAX is built for that conversation. If your requirement is a hundred gigabytes of US residential traffic this month and possibly nothing next month, 👉 start with the $1/GB pay-as-you-go plan and see what your cost per successful request actually looks like.
