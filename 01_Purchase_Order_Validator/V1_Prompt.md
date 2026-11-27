# P01 – Purchase Order Validator

## Version 1 – Original Prompt

Act as a garment merchandising assistant working for a medium-sized apparel manufacturer in Bangladesh.

Review the purchase order provided below and identify any missing information, errors, inconsistencies, or potential problems that could affect order processing and production.

Summarise the purchase order details, highlight the issues you identify, and suggest appropriate corrective actions.

Present your findings clearly so that a merchandising manager can understand them.

PURCHASE ORDER DATA:

PO Number: PO-2026-1045
Buyer: NorthStar Fashion Ltd.
Manufacturer: Meridian Apparels Ltd., Bangladesh
PO Date: 10 November 2026
Style Number: NSF-LG-225
Product: Ladies' Cotton Leggings
Fabric Composition: 95% Cotton, 5% Elastane
Colour: Black
Size Breakdown: S: 2,000; M: 3,000; L: 2,500; XL: 1,500
Declared Total Quantity: 10,000 pieces
Unit Price: US$4.50
Declared Order Value: US$45,000
Shipment Date: 15 December 2026
Delivery Destination: Hamburg, Germany
Payment Terms: Not specified
Packing Instructions: Not provided
Approved Sample Status: Pending

## Version 1 – Claude Response

# Purchase Order Review: PO-2026-1045

## 1. PO Summary

| Item | Detail |
|---|---|
| Buyer | NorthStar Fashion Ltd. |
| Manufacturer | Meridian Apparels Ltd. |
| PO Date | 10 Nov 2026 |
| Style | NSF-LG-225, Ladies' Cotton Leggings |
| Fabric | 95% Cotton / 5% Elastane |
| Colour | Black |
| Size breakdown | S 2,000 / M 3,000 / L 2,500 / XL 1,500 = **9,000 pcs** |
| Declared quantity | 10,000 pcs |
| Unit price | US$4.50 |
| Declared value | US$45,000 |
| Ship date | 15 Dec 2026 |
| Destination | Hamburg, Germany |
| Payment terms | Not specified |
| Packing instructions | Not provided |
| Sample approval | Pending |

## 2. Issues Identified

### Critical (resolve before accepting the PO)

**1. Quantity mismatch.** The size breakdown adds up to 9,000 pcs, but the PO declares 10,000. That is a 1,000 pc gap (10%).
- Financial impact: at US$4.50, the difference is US$4,500. The value is US$40,500 on 9,000 pcs, or US$45,000 on 10,000 pcs.
- Production impact: fabric, trims and capacity planning all depend on which figure is right. It is unclear whether a size (or an XS/XXL) was left out or the total is simply wrong.

**2. Unrealistic lead time.** The PO is dated 10 Nov and ships 15 Dec, which is only **35 days** (about 5 weeks) from PO date to ex-factory/shipment.
- Knit fabric sourcing and production (yarn, knitting, dyeing, finishing) typically takes 3 to 5 weeks on its own for a stretch cotton/elastane fabric.
- That leaves little or no time for sampling, approvals, lab tests, cutting, sewing, finishing, packing, inspection and export documentation.
- If Hamburg delivery is required by 15 Dec, the position is worse. Sea freight from Chittagong to Hamburg takes roughly 30 to 40 days, so this would effectively require air freight.
- The PO does not say whether 15 Dec means ex-factory, FOB (port of loading) or delivery in Hamburg. Each leads to a very different schedule.

**3. Approved sample pending.** Without an approved pre-production sample, fit, colour and construction are not confirmed. Fabric booking and bulk cutting are risky until sample approval, yet the clock is already running toward a tight ship date.

**4. Payment terms not specified.** There is no information on L/C, TT, payment days or deposits. This creates credit and cash-flow exposure, especially as fabric and yarn must be bought up front. It also affects whether back-to-back L/C can be opened, and a missing L/C could delay the whole process.

### Major

**5. Packing instructions missing.** Packing method, carton specification, ratio per carton, labels, hangtags, polybag requirements and shipping marks are all unspecified. This affects costing (packing material), carton count and shipment planning. Missing instructions are a common cause of late-stage rework and claims.

**6. Incoterms and shipping mode not stated.** FOB, CIF, DDP or air/sea is not defined. This affects cost, responsibility for freight, insurance and the timeline.

**7. Missing technical specifications.** The PO has no tech pack or spec sheet, size measurements, tolerances, fabric weight (GSM) or construction details (waistband, stitching, seam type). Also missing are label/trim details (care label, size label, country of origin, composition label) and Pantone/colour reference for "Black" (reactive dyed? colour fastness requirements?).

**8. Compliance and testing requirements not stated.** For the EU/German market, the PO should reference:
- REACH / restricted substances (e.g., azo dyes, formaldehyde)
- Textile labelling regulation (EU Regulation 1007/2011) for fibre composition
- Buyer-specific tests (colour fastness, pilling, shrinkage, elastane recovery)
- Third-party inspection or audit requirements (e.g., social compliance)

Failing to confirm these early risks failed tests and shipment holds.

### Minor / Clarification

**9. Unit price basis unclear.** It is not stated whether US$4.50 is FOB, CM-only or includes trims and packing. At this price, the margin for cotton/elastane leggings is likely thin, and any added requirements (testing, special packing, air freight) could erode it.

**10. Missing commercial details.** No buyer contact/signature or PO authorisation, no tolerance allowance (e.g., ±5% quantity), no penalty or delay clauses, and no delivery address detail (consignee, notify party) beyond "Hamburg". No packing ratio (solid size vs assorted) is given.

## 3. Corrective Actions

| # | Action | Owner | Priority |
|---|---|---|---|
| 1 | Ask the buyer to confirm the correct total (9,000 vs 10,000) and issue an amended PO, including a revised value | Merchandiser | Immediate |
| 2 | Clarify the meaning of the 15 Dec date (ex-factory/FOB/delivered) and negotiate a realistic date or agree air freight with cost responsibility | Merchandiser / Manager | Immediate |
| 3 | Do a time-and-action (T&A) calendar check against the capacity plan and fabric lead time before confirming | Merchandiser / Planning | Immediate |
| 4 | Expedite sample submission and approval; get written confirmation on timing, and avoid bulk fabric booking until approved (or obtain written buyer risk acceptance) | Merchandiser / Sampling | Immediate |
| 5 | Obtain payment terms in writing; confirm L/C or TT details before purchasing | Merchandiser / Commercial | Immediate |
| 6 | Request packing instructions, carton specifications and labelling/hangtag details | Merchandiser | High |
| 7 | Request a full tech pack, measurement spec, GSM, colour standard and trim list | Merchandiser / Technical | High |
| 8 | Confirm compliance and testing requirements and any inspection plan | Merchandiser / QA | High |
| 9 | Re-check cost sheet against the confirmed specs, quantity and shipping mode | Merchandiser / Costing | High |
| 10 | Confirm quantity tolerance, delay penalties and any other commercial terms | Manager | Medium |

## 4. Recommendation

**Do not confirm this PO as it stands.** The quantity discrepancy, tight lead time, pending sample approval and missing payment terms are all serious enough to put delivery, cash flow and profitability at risk. I suggest sending the buyer a consolidated query list now and holding fabric booking until the quantity, ship date, payment terms and sample status are settled in writing.

I can also draft the query email to NorthStar Fashion Ltd. or a time-and-action calendar if that would help.

## Version 2 – Improved Prompt

ROLE
You are an AI Purchase Order Validation Assistant supporting the merchandising department of Meridian Apparels Ltd., a fictional garment manufacturer in Bangladesh. Your role is to assist a human merchandiser with preliminary order validation, not to approve or reject purchase orders.

OBJECTIVE
Analyse the purchase order below, verify numerical consistency, identify missing or conflicting information, and produce a structured validation report suitable for a merchandising manager.

TASK 1 — EXTRACT AND VALIDATE
1. Extract the PO number, buyer, manufacturer, PO date, style, product, fabric, colour, size breakdown, declared quantity, unit price, declared order value, shipment date, destination, payment terms, packing instructions and sample approval status.
2. Independently calculate the sum of the size quantities.
3. Compare the calculated quantity with the declared total.
4. Calculate the order value using both the declared quantity and the size-breakdown total.
5. Clearly distinguish mathematically verified discrepancies from missing information.

TASK 2 — CLASSIFY ISSUES
Use these severity definitions:
CRITICAL: A confirmed numerical contradiction or missing approval/information that prevents reliable order confirmation.
HIGH: Missing operational or commercial information that could materially affect production, costing, quality or shipment planning.
MEDIUM: Information requiring clarification but not demonstrated to prevent immediate preliminary review.

Do not classify an issue as a confirmed delay or breach unless the supplied data demonstrates it.

TASK 3 — EVIDENCE AND CONSTRAINTS
- Use the purchase order as the only source of confirmed facts.
- Do not invent supplier lead times, freight transit times, payment arrangements, margins, buyer requirements or approvals.
- Label industry-based possibilities as "Potential risk — requires verification".
- Distinguish "Missing from supplied PO" from "Confirmed absent from the business".
- Cite the relevant PO field or calculation for every finding.
- If information is insufficient, write "Not provided — requires confirmation".
- Do not claim that an action has been performed.

TASK 4 — OUTPUT FORMAT
Produce the following sections:

A. PURCHASE ORDER SUMMARY
A concise table of extracted PO fields.

B. NUMERICAL VALIDATION
A table containing: Check | Source Values | Calculation | Result | Status.

C. ISSUE REGISTER
A table containing: Issue ID | Finding | PO Evidence | Severity | Recommended Action | Responsible Human Role.

D. MANAGEMENT RECOMMENDATION
Provide a concise recommendation identifying which issues should be resolved before order confirmation. Explicitly state that final decisions require authorised human review.

E. VALIDATION LIMITATIONS
List information that cannot be verified from the supplied PO and explain what additional evidence would be needed.

PURCHASE ORDER — SYNTHETIC TEST DATA
PO Number: PO-2026-1045
Buyer: NorthStar Fashion Ltd.
Manufacturer: Meridian Apparels Ltd., Bangladesh
PO Date: 10 November 2026
Style Number: NSF-LG-225
Product: Ladies' Cotton Leggings
Fabric Composition: 95% Cotton, 5% Elastane
Colour: Black
Size Breakdown: S: 2,000; M: 3,000; L: 2,500; XL: 1,500
Declared Total Quantity: 10,000 pieces
Unit Price: US$4.50
Declared Order Value: US$45,000
Shipment Date: 15 December 2026
Delivery Destination: Hamburg, Germany
Payment Terms: Not specified
Packing Instructions: Not provided
Approved Sample Status: Pending

## Version 2 – Claude Response

# Preliminary Time and Action (T&A) Review: PO-2026-1045 / NSF-LG-225

*Preliminary planning aid for management review. It does not confirm the order or the shipment date.*

## 1. Summary

**As supplied, the planned production sequence cannot support a 15 December 2026 shipment.**

- With production starting 25 Nov and the stages run back-to-back, final inspection finishes on **17 Dec**. That is already two days after the target, before any export documentation or ex-factory handling.
- Fabric, trims and sample approval are all unconfirmed, and the plan starts in two days (today is 23 Nov).
- Overlapping the stages could bring inspection completion to about 10 Dec. That recovers the date, but only if every pre-production item is cleared by 24 Nov and capacity supports the overlap.

## 2. Assumptions

| # | Assumption | Basis |
|---|---|---|
| A1 | Durations are working days. The factory works Sunday to Thursday (Fri/Sat off). | Supplied |
| A2 | No public holidays are applied. | None supplied. See risk R7. |
| A3 | Planned production start (25 Nov, Wednesday) is Day 1 of cutting. | Supplied |
| A4 | The baseline runs stages **sequentially** (each starts the next working day after the previous one ends). | My assumption: no overlap policy supplied |
| A5 | Export documentation, stuffing and ex-factory handling need **at least 1 working day** after inspection. | My assumption: not supplied |
| A6 | The 15 Dec target is treated as **ex-factory** for scheduling. | My assumption: date definition not confirmed |
| A7 | The stage durations apply to whichever quantity is finally confirmed (9,000 or 10,000). | My assumption: see risk R3 |
| A8 | No lead times were supplied for pre-production items, so they appear as **required-by dates**, not planned durations. | Data gap |

## 3. Time and Action Calendar

### 3.1 Pre-production activities (required-by dates)

| # | Activity | Required by | Responsible | Key dependency | Status in supplied data |
|---|---|---|---|---|---|
| 1 | Resolve PO queries with the buyer: quantity (9,000 vs 10,000), ship-date definition, payment terms, packing instructions | Tue 24 Nov | Merchandiser / Manager | Buyer response | Open |
| 2 | Pre-production sample approval (fit, construction, colour) | Tue 24 Nov | Merchandiser / Sampling | Buyer approval | **Pending** |
| 3 | Colour and fabric quality approval (black, 95/5 cotton/elastane) | Tue 24 Nov | Merchandiser / Dyeing / QA | Fabric supplier, buyer standard | Not provided |
| 4 | Fabric in-house, inspected, with shrinkage/relaxation check | Tue 24 Nov | Fabric Store / QA | Item 3, quantity confirmation (1) | **Not confirmed** |
| 5 | Sewing trims in-house (thread, labels, waistband/elastic, etc.) | Sun 29 Nov (before sewing starts Mon 30 Nov) | Sourcing / Merchandiser | Tech pack, trim list | **Not confirmed** |
| 6 | Packing trims in-house (polybags, hangtags, cartons) | Wed 9 Dec (before finishing starts Thu 10 Dec) | Sourcing / Merchandiser | Packing instructions (1) | Instructions not provided |
| 7 | Capacity confirmation, cut-plan and pre-production meeting | Tue 24 Nov | Production Planning / Merchandiser | Items 2, 4 | No capacity data supplied |
| 8 | Compliance and testing plan | Not determinable | QA / Merchandiser | Buyer requirements | Not provided, requires confirmation |

### 3.2 Production and shipment activities (baseline: sequential, as supplied)

| # | Activity | Start | Finish | Duration | Responsible | Depends on |
|---|---|---|---|---|---|---|
| 9 | Cutting | Wed 25 Nov | Sun 29 Nov | 3 WD | Cutting | Items 2, 4, 7 |
| 10 | Sewing (with in-line QC) | Mon 30 Nov | Wed 9 Dec | 8 WD | Sewing / QC | Items 5, 9 |
| 11 | Finishing and packing | Thu 10 Dec | Tue 15 Dec | 4 WD | Finishing / Packing | Items 6, 10 |
| 12 | Final inspection | Wed 16 Dec | Thu 17 Dec | 2 WD | QA | Item 11 |
| 13 | Export documents, stuffing, ex-factory (A5) | Sun 20 Dec | Sun 20 Dec | 1 WD (assumed) | Shipping / Commercial | Item 12, payment terms and docs |

Working-day check for Item 9: 25 Nov, 26 Nov, then 29 Nov. Fri 27 and Sat 28 Nov are off.

## 4. Feasibility Assessment

| Scenario | Basis | Inspection complete | Earliest ex-factory | Against 15 Dec |
|---|---|---|---|---|
| **A. Sequential (baseline)** | Supplied durations, no overlap | 17 Dec | 20 Dec | **3 working days late** (5 calendar days) |
| **B. Overlapped (illustrative)** | Sewing starts 26 Nov, one day into cutting. Finishing starts 3 Dec and runs 4 days. Inspection follows. | 10 Dec | 13 Dec | About 2 working days of buffer |
| **C. Back-calculated latest start** | Work backwards from 15 Dec ex-factory, no overlap, no buffer | n/a | n/a | Cutting would have needed to start **22 Nov**, which is already past |

Scenario B dates:
- Sewing: 26 Nov to 7 Dec.
- Finishing: 3 Dec to 8 Dec.
- Inspection: 9 Dec to 10 Dec.
- Ex-factory: 13 Dec.

Scenario B is **not a confirmed plan**. It rests on unverified assumptions about overlap, line allocation and early fabric arrival.

**Conclusion:**
- On the supplied data, a 15 Dec ex-factory date is **not supported** under a sequential flow.
- It becomes possible only with stage overlap plus all pre-production items cleared by 24 Nov.
- If "shipment" means FOB port or delivery in Hamburg, extra time is needed. That time is not quantified here because no transit or port data was supplied.

**Implied output rates** (derived, not supplied):

| Stage | At 9,000 pcs | At 10,000 pcs |
|---|---|---|
| Cutting (3 days) | 3,000 pcs/day | 3,333 pcs/day |
| Sewing (8 days) | 1,125 pcs/day | 1,250 pcs/day |
| Finishing (4 days) | 2,250 pcs/day | 2,500 pcs/day |

Planning must confirm these rates are achievable on actual lines.

## 5. Risk Summary

| ID | Risk | Evidence | Impact | Rating |
|---|---|---|---|---|
| R1 | Fabric availability unconfirmed. Cutting starts 25 Nov. Any shortfall (knit, dyeing, testing) delays everything downstream. Potential risk, requires verification: fabric processing lead time. | "Fabric Availability: Not yet confirmed" | Direct delay to all later stages | **Critical** |
| R2 | Sample approval pending. Bulk cutting before approval risks rework or rejection. | "Sample Approval Status: Pending" | Fit, colour or construction changes after cutting | **Critical** |
| R3 | Quantity conflict (9,000 vs 10,000). It is not stated which quantity the durations assume. If durations were set for 9,000 and output scales linearly, 10,000 pcs adds roughly 1 to 2 working days across the chain (my estimate). | Declared total vs calculated size total | Wrong fabric and trim volumes, schedule shift | **Critical** |
| R4 | Sequential flow already overshoots 15 Dec by 3 working days (Scenario A). | Section 4 | Late shipment, or air freight and overtime cost | **High** |
| R5 | Trims unconfirmed, and packing trims cannot be ordered without packing instructions. | "Trim Availability: Not yet confirmed"; packing instructions not provided in the PO | Stoppage at sewing or finishing | **High** |
| R6 | Shipment date definition not confirmed. | "Shipment Date Definition: Not confirmed" | The target could mean ex-factory, FOB or delivered, which changes the schedule | **High** |
| R7 | Public holidays not supplied. Potential risk, requires verification: 16 Dec (Victory Day) is normally a national holiday in Bangladesh and would fall inside the baseline inspection window, with further impact on documentation days. | "Public Holidays: Not supplied" | Pushes Scenario A beyond 20 Dec | **High** |
| R8 | No capacity figures, so overlap and daily output cannot be validated. | No capacity data | Scenario B cannot be relied on | **High** |
| R9 | Compliance/testing requirements unknown (Germany destination). Test time is not in the calendar. Potential risk, requires verification. | No compliance data | Possible inspection or release delays | **Medium** |
| R10 | Payment terms unspecified. Could affect fabric purchase timing and export documentation. Potential risk, requires verification. | "Payment Terms: Not specified" | Material purchase and documentation delays | **Medium** |
| R11 | No buffer for rework, re-inspection or machine downtime. | Calendar has zero float | Any slip goes straight into shipment date | **Medium** |

## 6. Recommendations and Priorities

**Immediate (by 24 Nov, before committing to 25 Nov cutting)**
1. **Fabric and trims:** Merchandising and Sourcing to confirm in writing whether fabric and sewing trims will be in-house and inspected by 24 Nov. If not, **move the cutting start** and re-run this calendar.
2. **Sample:** Obtain the buyer's approval date. The Manager should decide whether to cut at risk and, if so, obtain written buyer risk acceptance.
3. **Quantity and ship date:** Get written confirmation of the correct total (9,000 or 10,000) and what "15 Dec" means. Do not finalise fabric quantities until both are settled.
4. **Date decision:** Management should decide now whether to (a) ask the buyer for a later date, (b) negotiate a split shipment, or (c) cost and approve an acceleration plan. Scenario A already shows a miss.

**Within 48 hours**
5. Production Planning to validate Scenario B against actual line allocation, daily output and cutting-to-sewing overlap. Confirm whether the implied rates in Section 4 are achievable.
6. Confirm the holiday calendar (including 16 Dec) and add the dates to the T&A.
7. Obtain packing instructions and the trim list so packing trims can be ordered for the 9 Dec required-by date.

**This week**
8. QA to confirm test and inspection requirements and add them to the calendar.
9. Commercial to confirm payment terms and the documentation timeline.
10. Add a float or buffer for re-inspection and rework, and agree a mitigation plan (overtime, extra lines) in case of delay. Costs are not estimated here.
11. Re-issue the T&A with actual fabric and trim arrival dates once they are available.

**Priority order:** fabric and trims, then sample and quantity, then date definition, then capacity validation.

## 7. Information Needed to Finalise the T&A

- Confirmed quantity and amended PO
- Fabric supplier lead time, booking status and expected arrival date
- Trim list with arrival dates
- Sample approval date
- Line-wise capacity and efficiency data
- Holiday calendar
- Shipment date definition, shipping mode and Incoterms
- Test and compliance requirements

This is a preliminary planning analysis. Dates in Scenarios A and B are calculated from the supplied durations and my stated assumptions, and any decision to confirm the PO or the ship date rests with authorised human reviewers.

I can also build this as an Excel T&A tracker with a status column and automatic date recalculation if you'd like.

## Evaluation and Improvements

Version 1 generated a useful preliminary production schedule but introduced unsupported assumptions about overlapping activities and export processing times. Version 2 improved accuracy by introducing explicit working-day calculations, clearer production dependencies and evidence-based scheduling constraints. It also distinguished calculated dates from unverified assumptions. Version 2 was selected because it provides more reliable critical path planning, reduces misleading delivery forecasts and supports informed management decisions while maintaining human oversight.



