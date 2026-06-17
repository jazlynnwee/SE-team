# Spare Product Suite — SE Reference

## How to Use This

Know what to lead with, what to introduce later, and what maturity level each product is at so you don't overpromise. Match products to the prospect's pain — don't show the full suite unless they need it.

---

## The Platform in One Sentence

Spare is a unified transit platform with core products for demand-response operations, optimization, rider experience, analytics, AI automation, multimodal journey planning, eligibility, open-fleet brokerage, and asset management.

**Scale**: 400+ transit services, 25M+ rides annually, 200+ partners.

---

## Product Tiers

### Tier 1 — Core Platform (Lead with these)

These are mature, established, and what most deals are built around.

**Spare Operations Platform**
The core demand-response product for paratransit and microtransit. Includes:
- Admin/operations control center (trip booking, dispatch, rider management, fleet oversight, investigations)
- Driver App with real-time navigation and live traffic-aware routing
- Rider App and Rider Web (booking, tracking, payments, notifications, white-label, SSO)
- Service planning (recurring trips, subscription trips, conditional eligibility rules, vehicle types, manual dispatch intervention)
- Driver management (duty scheduling, breaks, driver-dispatch communications)
- Rider communications (push, email, SMS, bulk messaging)
- Payments via Spare Pay / Stripe (fare passes, promo codes, wallet, digital farepass)
- Automation (Booking CoPilot, Workflows, demand forecasting)

**Spare Engine**
The optimization layer underneath Operations. Continuously optimizes scheduled, recurring, and on-demand trips together with native Google Live Traffic in routing. Key components:
- GO (hourly scheduled optimization)
- GOLD (global optimization of live duties)
- Targeted Optimization (frequent rerouting for OTP)

This is a major differentiator vs. Trapeze (batch every 15 min) and a key comparison point vs. RideCo (who claims patented continuous optimization).

**Spare Analytics**
Dashboards, custom reports, filters by service/date/type, heatmaps, histograms, trip search, and exports for operational and regulatory reporting. Includes Reporting CoPilot (AI-assisted) and Equivalent Fixed Route Time for ADA comparability. Automated reporting emails.

### Tier 2 — Established Adjacent Products (Introduce based on pain)

These are real, actively sold, and have clear proof points. Introduce when the prospect's pain maps to them.

**Spare Eligibility** (formerly Spare Engage)
Paratransit eligibility and case management. Case forms, letters, statuses, assignment, timers. Medical verification, appointment scheduling. AI Scan for digitizing handwritten PDFs. Eligibility analytics and reports. Case status in Rider App. Eligibility AI Voice. Notifications via Workflows.
- *When to introduce*: Prospect has paper-based eligibility, Mobility Direct, Jotform, or spreadsheets. External assessor coordination pain. 21-day ADA deadline pressure.
- *Proof points*: MBTA (60% more apps processed, 17→5 days), OCTA ("smoothest launch ever"), CapMetro (500-620 cases/month).

**Open Fleets Platform**
Brokered / third-party fleet orchestration. Integrates Uber, Lyft, MTI, UZURV, iCabbi, Jagwire, taxis, WAV providers into Spare-managed service. Automates trip assignment to external providers.
- *When to introduce*: Prospect uses or wants TNCs/taxis as part of service. Subcontractor management pain. Cost optimization across fleet types.
- *Proof points*: PSTA (60%+ MOD trips via Open Fleets, $705k dispatcher labor saved), DART (66% of GoLink on Uber at $9.08/trip), MBTA (30% NDSP reduction).

**Spare AI Platform**
AI Voice (natural-language phone booking/cancelling/ETA), AI Chat over SMS in 50+ languages, Spare IVR, payment via AI Voice. Internal copilots (Analyze CoPilot, Booking CoPilot). Outcome-based pricing.
- *When to introduce*: High call center volume, long hold times, abandoned calls. Want to reduce agent load without losing service quality.
- *Proof points*: PSTA (44% of calls handled by AI, 46% reduction in hold times, $0.71 vs $1.91-3.35 per call), CapMetro (4.7k→5.2k AI outcomes/month).

**Spare EAM**
Enterprise asset management for maintenance teams. Preventive maintenance, work order management, vehicle inspections, asset availability, maintenance-triggered status sync back into operations.
- *When to introduce*: Maintenance/ops disconnect (Google Sheet down lists, paper DVIR, mileage tracked manually). Trapeze EAM not integrated with Trapeze PASS.
- *Proof points*: MBTA pilot in progress. LA Access conversation surfaced strong interest from MV's maintenance manager.

### Tier 3 — Strategic / Expansion Products (Introduce carefully)

These are real and being sold but still building depth and proof points. Position as part of the platform roadmap rather than leading with them.

**Spare One / Multimodal**
MaaS and multimodal rider experience. Combines fixed-route, microtransit, and on-demand in one rider app for trip planning, booking, and payment. First/last-mile coordination, walking guidance, transfer support, in-app fare payments.
- *When to introduce*: Agency wants one app for all modes. MaaS vision. First/last-mile is a stated goal.
- *Proof points*: DART GoPass integration. Strategic layer.

**Spare Resolve**
Transit-specific CRM / complaints and incident management. Omnichannel intake (email, phone, SMS, web, QR codes). End-to-end case tracking with operational context (trip, rider, vehicle data). Automated triage / AI. Compliance and audit reporting. Trend/pattern detection.
- *When to introduce*: Compliance-driven agencies (especially Florida with 48-hour investigation requirements). Agencies drowning in complaints with no systematic tracking. Can also cover fixed-route complaints.
- *Maturity*: Real emerging product with growing compliance positioning.

**Spare Conversations / PTT**
Dispatch-driver communications replacing Zello/Orion. Push-to-talk voice, two-way messaging, broadcast, quick reply templates, emergency alerts — all in-platform with a record of communication.
- *When to introduce*: Prospect using fragmented radio/messaging tools. Driver-dispatch communication gaps surfaced during discovery.
- *Maturity*: Newly launched, being sold, still completing positioning. Born from LA World Cup shuttle and demand from MBTA/DART.

**Fixed Route**
Route and stop design, GTFS/GTFS-RT generation, live operations, driver navigation, passenger counting. Changes Spare from demand-response only to unified transit operations (fixed + micro + para).
- *When to introduce*: Agency wants one platform across all modes. Fixed-route pilot conversations (CapMetro senior routes). Don't lead with this unless the prospect specifically asks.
- *Maturity*: Real, demoable, strategic expansion — broad functionality but not yet deep in any single area. Still building proof points.

**Call Centre Operations**
Spare also packages call-center operations as a service (per-minute or FTE-based) for higher-volume programs. Separate from AI Voice.

---

## How to Sequence in a Deal

**Most paratransit deals**: Lead with Operations + Engine + Analytics + Rider App/Web. These are the core replacement story for Trapeze/Routematch/Adept.

**If eligibility pain surfaces**: Introduce Eligibility early — it can be Phase 1 (as OCTA did) or concurrent with ops.

**If call center volume is a problem**: Introduce AI Platform mid-cycle as a cost-savings accelerator. Use PSTA ROI numbers.

**If they use TNCs/taxis/subs**: Introduce Open Fleets when subcontractor management pain surfaces. Use PSTA and DART economics.

**If maintenance/ops disconnect surfaces**: Mention EAM as part of the platform story. Don't oversell — it's real but position as "closing the loop" rather than a standalone sale.

**If the prospect has a "one platform" vision**: Show the full suite diagram. Reference CapMetro (paratransit + eligibility + AI Voice + microtransit migration + EAM + fixed route pilot) as the most comprehensive multi-product deployment.

**What NOT to do**: Don't show the full suite to a prospect who just wants better paratransit dispatch. It overwhelms them. Start with their pain, solve it, then expand.
