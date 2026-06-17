# Spare Reference Deployments — SE Quick Guide

## How to Use This

Match 1-2 deployments to each prospect's pain. Lead with the reference that maps closest to their situation, and have a secondary ready. Use the quantitative before/after figures as proof points, not just logos.

---

## MBTA / Boston (The RIDE)

**What Spare replaced**: Adept TMS, fragmented eligibility (Mobility Direct, Jotform, Excel), separate NDSP management.

**Scale**: Largest fully automated paratransit in North America. 4,000+ daily trips.

**Key outcomes**:
- OTP: 88% pre-Spare → 95% in 24 hours → stabilized 94%+
- Productivity: 1.07 → 1.2 trips/vehicle-hour
- NDSP trips reduced ~30%, projected millions in savings
- Eligibility: 60% more applications processed, 17→5 day avg processing, 0 cases over 21-day ADA deadline, ~75% more assessments with same staff
- 18% of trips booked via Rider Web in week one (before mobile app launched)

**Status**: Fully live. RIDE Flex (same-day) and EAM pilot in progress.

**Use this when**: Large legacy ADA system on Adept/Trapeze worried about cutover risk and service collapse. Eligibility backlogs. Over-spending on NDSPs. Agency wants a platform (TMS + eligibility + NDSP + EAM), not a single module.

---

## OCTA / Orange County (OC ACCESS)

**What Spare is replacing**: Trapeze PASS suite across 25 on-prem servers, plus separate eligibility system and Same-Day Taxi/OC Flex system.

**Scale**: ~835k trips/year, 261 vehicles, ~4,000 calls/day, ~$78/trip under Trapeze.

**Key outcomes (so far)**:
- Eligibility live Dec 2025: ~1,500 apps/month, 120 appointments/week, <7 day wait, 1,600+ auto-generated letters. Described internally as "one of the smoothest launches" OCTA has experienced.
- Operations go-live targeting July 3, 2026
- AI Voice LOI signed to deploy alongside operations
- Baseline OTP ~60% under Trapeze — significant room for improvement

**Status**: Eligibility live and stable. Operations in configuration/UAT. Access LA watching OCTA as a bellwether.

**Use this when**: Enterprise Trapeze PASS → SaaS migration where IT/finance care about server sprawl and TCO. Paper-based eligibility with contracted external assessors. High-volume call centers exploring AI Voice. Agencies wanting one platform to replace three systems. Note: OCTA scored Spare above RideCo, Via, Ecolane, and HBSS on both features and price in their evaluation.

---

## DART / Dallas (GoLink + Paratransit)

**What Spare replaced**: Legacy on-demand software for GoLink microtransit, now also powering ADA paratransit and Rider Assistance Program (RAP).

**Scale**: 30+ GoLink zones across 13 cities, 200k+ monthly trips, 6,500 daily boardings. ~4,000 paratransit trips/day moving to Spare.

**Key outcomes**:
- Ridership up 724% vs 2019, 68% YoY in FY24
- Average wait: 9-10 minutes vs 15-minute target
- Cost/trip: $20→$14 in early years; blended $16.75/trip (2023), subsidy ~$14 (down from ~$26)
- ~66% of GoLink boardings now on Uber at ~$9.08/trip subsidy (2-3x cheaper than dedicated)
- 30+ low-performing bus routes replaced with GoLink zones
- Branded as "world's largest commingled ADA paratransit and microtransit service"
- Spare consultancy identified $0.7-1.9M/year in additional savings

**Status**: GoLink fully live at scale. Paratransit + RAP migration underway with commingling.

**Use this when**: Route replacement with microtransit. Mixed fleet & Uber economics (prospects afraid TNCs will blow budget — DART proves the opposite). Commingled ADA + microtransit. Open API / MaaS integration (GoPass). Comparing against Via/RideCo/TransLoc.

---

## CapMetro / Austin (MetroAccess + Pickup)

**What Spare replaced**: 20-year-old Trapeze system for MetroAccess paratransit.

**Scale**: ~52k boardings/month, 108 peak vehicles.

**Key outcomes**:
- OTP: 88% pre-Spare → 98% in first 10 days → 95% in first 30 days → sustained ~93-94%, hitting 95% after Watch List
- Co-designed Watch List: unscheduled stops -25.9%, average stop duration -68.6%
- Eligibility (Spare Eligibility): 500-620 cases/month
- AI Voice: growing from ~4,700→5,200 outcomes/month
- Digital booking (app/web/AI Voice) at 12.6-19.7% of non-recurring trips, reducing call center load
- Migrating Pickup microtransit from Via to Spare
- Fixed route pilot and EAM in progress

**Status**: MetroAccess fully live since Oct 2023. Multi-product expansion active.

**Use this when**: Big-bang Trapeze replacement where OTP has stagnated. Agency wants to co-design operations tooling (not just take what's out of the box). Multi-product modernization roadmap (paratransit + microtransit + IVR + EAM + fixed route). Via replacement conversations for microtransit.

---

## PSTA / Pinellas County (Access + MOD)

**What Spare replaced**: Routematch, Tranware, Goin, fragmented TNC/taxi portals, manual TD spreadsheets.

**Scale**: ~1,900 trips/day, 120 peak vehicles, 1.2M+ total trips delivered, 6 fleet providers.

**Key outcomes**:
- OTP: ~92% → 96-97%; productivity: 0.93→1.04 trips/hr, saving ~$497k/year on dedicated fleet
- MOD: 60%+ trips via Open Fleets (Uber, Lyft, UZURV, taxis, WAV), 94-96% OTP and satisfaction
- Two-thirds of ADA riders shifted to lower-cost MOD
- Open Fleets automation saves ~5 min dispatcher time per brokered trip (~$705k labor saved on 314k+ trips)
- AI Voice: 44% of calls handled, 46% reduction in hold times, ~70% drop in abandoned calls, $0.71 vs $1.91-3.35 per call
- Self-serve bookings: $583k in call center savings since launch, $240k in 2025
- Wallet: ~$61k saved in card processing fees
- Total $1M+ annualized cost avoidance

**Status**: Live since Dec 2021. Continuously expanding (MOD, TD services, Grouper/Snapper, AI Voice).

**Use this when**: Routematch/Tranware replacement with messy program collection. Multi-provider brokerage with TNCs/taxis/WAV at scale. Same-day or late-night programs. FTA D&A compliance with TNCs. Call center ROI from AI Voice + self-serve. Coastal/snowbird/tourism market peer.

---

## Cross-Reference: Which Story for Which Prospect

**Large legacy paratransit on Trapeze/Adept, high political risk**:
Primary: MBTA. Secondary: CapMetro, PSTA.

**Enterprise Trapeze PASS replacement, on-prem → SaaS**:
OCTA.

**Paper-heavy eligibility with external assessors**:
OCTA (with MTM). MBTA (high-volume internal).

**Route replacement / large microtransit networks**:
DART. CapMetro (for Via replacement angle).

**Multi-provider brokerage (TNC + taxi + WAV) at scale**:
PSTA. DART. MBTA.

**Call center, AI Voice, and digital self-service modernization**:
PSTA (strongest quantitative ROI). CapMetro. OCTA.

**"One platform / one app / one IVR" buyers**:
CapMetro. OCTA. MBTA.

**Via replacement**:
CapMetro (Pickup migration from Via).

**Operator-led deal (MV, Transdev, etc.) where operator wants to differentiate in rebid**:
OCTA (Transdev involvement). MBTA. Any deployment where Spare helped improve KPIs the operator is measured on.
