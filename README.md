# data center colocation: Real Prices, Hidden Fees, and How to Place Your Servers Without Overpaying

Colocation means you own the hardware and rent the space, power, cooling, and bandwidth for it inside a third-party data center. If you've already bought servers and just need a reliable, well-connected home for them, it's usually far cheaper than building your own facility. The problem most people hit when researching data center colocation is pricing: most guides explain what colocation is, then stop before telling you what it actually costs or which gotchas show up on the invoice.

This guide covers both. We'll use Sharktech as the worked example — a hosting provider that runs colocation out of five data centers (Los Angeles, Las Vegas, Denver, Chicago, and Amsterdam) inside enterprise facilities from operators like Equinix, CoreSite, H5 Data Centers, and CrownCastle — and go through its plans, real cost math, and the fees that rarely make it into marketing pages.

> **Quick answer for readers in a hurry:** Sharktech's colocation starts at **$79/month for 1–6U** and **$449/month for a 10–42U cabinet**, both with 10Gbps–100Gbps network ports and 300TB+ of traffic. If you own your own servers and want DDoS-protected, redundant infrastructure, that entry tier is the practical starting point. 👉 [Check Sharktech colocation pricing for your preferred location](https://bit.ly/SharKtech)

## Sharktech colocation plans at a glance

Sharktech publishes two standard colocation tiers, plus custom options for anything beyond them. Here's the full lineup as shown on the official colocation page:

| Plan | Space | Power | Network & traffic | Starting price | Order |
| --- | --- | --- | --- | --- | --- |
| Entry colocation | 1–6U | 200–1200W | 10–100Gbps, 300TB+ | $79/mo | [Order 1–6U colocation](https://bit.ly/SharKtech) |
| Full cabinet | 10–42U | 1600–5500W | 10–100Gbps, 300TB+ | $449/mo | [Order a 10–42U cabinet](https://bit.ly/SharKtech) |
| Partial rack / private cage / multi-rack | Custom | Custom | Custom | Custom quote | [Request a custom colocation quote](https://bit.ly/SharKtech) |

Two things worth noticing. First, both standard tiers include the same network ceiling — up to 100Gbps ports with traffic starting at 300TB — so you're paying for space and power, not a crippled connection at the low end. Second, the entry tier tops out at 1200W, which is plenty for one or two modern servers but will pinch if you're racking GPU boxes. Anything above the published tiers goes through sales as an itemized quote.

## What colocation actually costs across the five locations

Price is the part most colocation guides dodge, so let's do the math. Sharktech's official page lists the two tiers starting at $79 and $449 per month, and third-party compilations of its per-location rates show meaningful spread between cities: Chicago has historically been listed as the cheapest at $35/month for 1–6U and $280/month for a full 42U cabinet, Las Vegas and Denver at $65/$520, and Los Angeles and Amsterdam at $99/$792. Those per-location figures come from third-party tracking rather than the current official page, so treat them as directional and confirm the exact rate for your city with sales before signing.

Even taking the official starting prices alone, the annual numbers are concrete:

- **1–6U tier:** $79/month → about **$948/year** for a single server or small stack.
- **10–42U cabinet:** $449/month → about **$5,388/year** for a full rack with up to 5500W.

For context, retail 1U colocation in major US markets typically runs $85–150/month, and full racks with power and bandwidth commonly land between $1,000 and $2,000+ per month. US colocation prices also rose roughly 17–21% in the six months heading into recent market conditions, with power — rather than floor space — driving most of the increase. Against that backdrop, a full cabinet with 5.5kW of power headroom at $449/month sits well below the typical tier-one market rate, and Sharktech's Chicago pricing reflects favorable power contracts there that the company passes through.

One promotion worth asking about: new colocation contracts have been reported to include 10% off for the first six months, applied automatically without a coupon code. That would bring the first six months of the entry tier down to roughly $71/month. It's not listed on the main product page, so confirm it applies to your contract before you sign. 👉 [See current colocation rates for all five data centers](https://bit.ly/SharKtech)

## The fees that show up after you sign

Sharktech commits to showing you power, connectivity, installation, and remote-hands charges before you order, which is more transparent than most. Still, anyone comparing colocation providers should know the standard list of surcharges in this industry, because they're where the "cheap" headline price grows up:

- **Power overages** — exceeding your allocated wattage, which matters more than ever now that power is the scarce resource in data centers.
- **Premium bandwidth tiers** — the base plan includes 10Gbps ports and 300TB+ traffic; pushing port speed or committed bandwidth upward costs extra.
- **Setup and installation fees** — charged for racking and initial provisioning.
- **Cross-connects** — a per-link fee for connecting to a specific carrier or partner inside the facility.
- **IP assignments** — allocations beyond a /29 (five usable IPv4 addresses) typically cost more.
- **Remote-hands work** — Sharktech offers 24/7 on-site technicians, but the scope of hands-on work is agreed with the team in advance, and non-standard or after-hours requests can carry fees.

None of these are unique to Sharktech — every colocation provider bills this way. The difference is whether they tell you up front. Sharktech's ordering flow makes those charges visible in the customer portal before payment, and custom deployments get an itemized quote. Published pricing, as the sales team will tell you, is the floor rather than the ceiling.

## Five locations, and how to pick between them

Sharktech operates colocation in **Los Angeles, Las Vegas, Denver, Chicago, and Amsterdam**, all inside carrier-grade facilities from established operators (Equinix, CoreSite, H5 Data Centers, CrownCastle). Every location runs on fully redundant power, backup generators, and cooling, with a DDoS-protected, multi-100-Gigabit redundant network.

Which one should you choose? A few practical rules:

- **Follow your users.** Amsterdam makes sense if most of your traffic is European; Los Angeles or Las Vegas for West Coast audiences; Chicago or Denver for central US.
- **Chicago is the value play.** It has historically been Sharktech's cheapest location by a wide margin, thanks to local power contracts.
- **Think about distance, not just latency.** Sharktech's own guidance for colocation buyers: pick a site away from flood and earthquake zones, and close enough that you can physically reach your hardware when something can't be fixed remotely.
- **Gaming and attack-exposed workloads** do fine anywhere on the list — the network includes DDoS protection by default, and a long-standing client, Dingdian Network, reports absorbing 3–8Gbit attacks on their game servers "without skipping a beat."

## How ordering works, step by step

Colocation onboarding is more hands-on than spinning up a VPS, and Sharktech's process reflects that. It runs in four steps:

1. **Choose a location** — compare the five cities against your users and network requirements.
2. **Specify your hardware** — share rack units, power draw, port requirements, and expected growth. This is where the team matches the service to your equipment, so be honest about the power numbers.
3. **Coordinate shipping and installation** — arrange delivery details with Sharktech *before* you put hardware on a truck. Sending equipment unannounced is the classic first-time mistake.
4. **Review and order** — check power, connectivity, installation, and remote-hands charges in the portal, then confirm.

For standard 1–6U or cabinet deployments this is self-service through the customer portal. Private cages and multi-rack builds go through a human, and you'll get an itemized quote rather than a package price. If you already know your rack unit count and power draw, the whole thing starts in the portal: 👉 [Configure your rack space and power in the Sharktech portal](https://bit.ly/SharKtech)

## When colocation is the wrong choice

Honest guidance includes the cases where you shouldn't buy this at all.

If you don't own hardware, colocation has nothing to offer you — you'd be buying servers first, which only pays off at scale. Rent a dedicated server or a VPS instead; Sharktech sells those too, and for a single workload they're almost always cheaper than buying hardware and housing it.

If your workload is elastic or you can't predict capacity, colocation locks you into physical space and power allocations. Cloud fits spiky demand better, at a higher steady-state price.

If you need zero hands-on involvement with the machines, remember that with colocation the hardware is yours to maintain. Sharktech's 24/7 on-site technicians handle emergencies and agreed remote-hands tasks, but OS-level administration stays on your side unless you negotiate managed coverage.

Where colocation clearly wins: you already own capable servers, you want them in redundant, DDoS-protected facilities instead of a closet or an office, and you'd rather pay $79 a month than $85–150 in a tier-one market for a worse-connected rack. Wings Technology, one of Sharktech's long-term colocation clients, chose it on price five years ago and has stayed.

## FAQ

**How much bandwidth is included?** Both standard tiers include 10Gbps to 100Gbps ports with traffic starting at 300TB per month. Higher commitments and port speeds are quoted on request.

**Is DDoS protection included with colocation?** Yes. All five Sharktech data centers operate a DDoS-protected network, which is one of the main reasons attack-prone workloads like game servers end up there.

**Do I need a coupon code for the colocation discount?** The reported 10%-off-first-six-months promotion on new colocation contracts applies automatically — no code required. Dedicated server and VPS promotions do use coupon codes, but those codes don't apply to colocation. Confirm eligibility with sales before signing.

**Colocation vs. cloud — which is cheaper?** For steady, predictable workloads on hardware you already own, colocation is almost always cheaper month over month. For unpredictable or bursty demand, cloud wins on flexibility. The crossover point is usually whether your servers run near capacity all month.

## Final advice before you order

Match the plan to your situation:

- **One or two servers, under 1200W total** → the 1–6U tier at $79/month is all you need; don't pay for cabinet space you won't fill.
- **Rack-worthy deployment or growth plans** → the 10–42U cabinet at $449/month, especially in Chicago where power is cheapest.
- **Private cage, partial cabinet, or multi-site redundancy** → skip the published tiers and get an itemized quote.

Before signing anything, ask two questions: what the exact per-location rate is for your city and tier (published figures vary by location), and whether the first-six-months discount applies to your contract. Then pick your city, get your power numbers straight, and 👉 [get a colocation quote for your hardware](https://bit.ly/SharKtech).
