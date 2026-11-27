# P02 – Requirements and Critical Path Planner

## Version 1 – Original Prompt

ROLE
You are an AI-assisted garment production planning analyst supporting Meridian Apparels Ltd., a fictional apparel manufacturer in Bangladesh. You support human planners; you cannot approve production schedules, purchase orders, shipment commitments or material releases.

OBJECTIVE
Prepare an evidence-based preliminary Time and Action (T&A) calendar for purchase order PO-2026-1045. Calculate the known production sequence, identify dependencies and determine what can and cannot be concluded about the shipment target.

TASK 1 — VALIDATE THE INPUT
1. Extract the order date, target date, planned production start, quantities, production-stage durations, working calendar and approval/material status.
2. Recalculate the size-breakdown quantity and identify any discrepancy.
3. Identify missing information that could affect the schedule.
4. Clearly distinguish supplied facts, derived calculations and unverified assumptions.

TASK 2 — BUILD THE BASELINE SCHEDULE
1. Use a Sunday–Thursday working calendar. Friday and Saturday are non-working days.
2. Treat 25 November 2026 as the first working day of cutting.
3. Count both the start date and finish date when calculating stage durations.
4. Assume the four supplied production stages run sequentially, with each following stage beginning on the next working day after the preceding stage finishes.
5. Do not apply public holidays because none were supplied. Explicitly flag the holiday calendar as unverified.
6. Do not invent durations for material sourcing, sample approval, testing, export documentation or transportation.
7. For each stage, show its start date, finish date, duration, predecessor, responsible department and scheduling status.

TASK 3 — ANALYSE DEPENDENCIES AND CRITICAL PATH
1. Identify which production-stage dependencies are confirmed by the supplied data and which are baseline scheduling assumptions.
2. Calculate the total sequential duration of the four production stages.
3. Explain the earliest completion of the four-stage sequence under the stated baseline assumptions.
4. Identify approval, material and commercial dependencies whose completion dates are unknown.
5. Distinguish the calculated production-stage chain from a fully validated end-to-end critical path.
6. Do not claim that an end-to-end critical path or float has been established if necessary activity durations and dependencies are missing.
7. Do not create an accelerated or overlapping schedule without verified overlap rules and production capacity.

TASK 4 — ASSESS THE SHIPMENT TARGET
1. Compare the calculated final-inspection date with 15 December 2026.
2. State whether the sequential production-stage baseline finishes before, on or after that date.
3. Explain that shipment feasibility cannot be fully verified because the target-date definition, material readiness, approvals, capacity and post-inspection requirements are unknown.
4. Do not invent supplier lead times, freight transit times, holiday dates, productivity improvements or additional production days.
5. Do not assume that 15 December means ex-factory, FOB or arrival at destination.

TASK 5 — RISKS AND MANAGEMENT ACTIONS
1. Prepare a concise risk register showing issue, supporting evidence, potential schedule impact, required information, responsible department and priority.
2. Distinguish confirmed scheduling conflicts from potential risks.
3. Prioritise clarification of the quantity discrepancy, sample approval, fabric/trims availability, capacity and shipment-date definition.
4. Recommend actions for authorised human planners and managers.
5. Do not present recommendations as actions already completed.

REQUIRED OUTPUT

A. Input Validation and Data Gaps
B. Baseline T&A Calendar — table with Activity, Start, Finish, Working Days, Predecessor, Owner and Status
C. Working-Day Calculation — explain the date calculation for each stage
D. Dependency and Critical-Path Assessment — clearly distinguish known production sequence from unknown end-to-end critical path
E. Shipment Target Assessment — confirmed findings versus unverified feasibility
F. Risk Register and Management Actions
G. Limitations and Required Human Approvals

Keep the analysis concise, professionally formatted and suitable for a merchandising manager. Do not add unrelated commercial or regulatory assumptions.

SYNTHETIC TEST DATA

Company: Meridian Apparels Ltd., Bangladesh
Buyer: NorthStar Fashion Ltd.
PO Number: PO-2026-1045
Style Number: NSF-LG-225
Product: Ladies' Cotton Leggings
Fabric Composition: 95% Cotton, 5% Elastane
Order Date: 10 November 2026
Shipment Target: 15 December 2026
Declared Order Quantity: 10,000 pieces
Size Breakdown: S 2,000; M 3,000; L 2,500; XL 1,500
Calculated Size Total: 9,000 pieces
Unit Price: US$4.50
Sample Approval Status: Pending
Fabric Availability: Not yet confirmed
Trim Availability: Not yet confirmed
Planned Production Start: 25 November 2026
Cutting Duration: 3 working days
Sewing Duration: 8 working days
Finishing and Packing Duration: 4 working days
Final Inspection Duration: 2 working days
Factory Working Days: Sunday to Thursday
Public Holidays: Not supplied
Shipment Date Definition: Not confirmed
Payment Terms: Not specified

Additional context:
The purchase order has not been fully validated. The declared quantity conflicts with the size breakdown. No confirmed supplier lead times, material arrival dates, production capacity figures, overlapping-production rules or post-inspection activity durations have been provided.

Generate the preliminary planning report now.

## Version 1 – Claude Response

# Supplier Communication: Eastern Knit Textiles Ltd.

## 1. Draft Email

**To:** [Supplier contact name], Eastern Knit Textiles Ltd.
**Cc:** [Merchandising Manager]; [Sourcing/Fabric Store]
**Subject:** Request for Fabric Status Update: 95% Cotton / 5% Elastane, Black (Our Ref: PO-2026-1045 / Style NSF-LG-225)

Dear [Name],

I hope you are well. Thank you for your quotation of 12 November 2026 for black 95% cotton / 5% elastane knit fabric for our Ladies' Cotton Leggings (Style NSF-LG-225, our ref. PO-2026-1045).

We are finalising our production plan, and our factory cutting is currently planned to start on **25 November 2026**. We have not yet finalised the fabric order quantity, and the dispatch date and testing status are not yet confirmed on our side. To plan accurately, we would be grateful if you could confirm the following by **close of business on Tuesday, 24 November 2026**.

**1. Production status**
- Is any fabric for this style already in production (knitting, dyeing or finishing)? If so, at which stage, and what quantity?
- If production has not started, what is the earliest start date and expected completion date?

**2. Available stock**
- Do you hold any ready black 95/5 cotton/elastane fabric that could be allocated to this style? Please include quantity, specification (GSM, width) and whether it matches the specification quoted.
- Could this stock be reserved for us while we confirm our order?

**3. Testing and quality**
- What testing has been completed or is planned for this fabric (for example shrinkage, GSM, colour fastness, composition)? Please share any available test reports.
- How long does testing take, and can any be done in parallel with production?

**4. Delivery**
- What is your earliest possible dispatch date, and the expected arrival at our factory?
- Can you supply in partial lots, and if so, what quantity could be dispatched first and when?

**5. Quantity and minimums**
- Our final requirement is being confirmed and is currently indicative at about 9,000 to 10,000 garments. Please confirm your minimum order quantity and the latest date by which you need our final quantity to hold your delivery timing.

Timely confirmation matters because our cutting schedule, line loading and later production stages all depend on when approved fabric reaches us. Without your dates, we cannot confirm our plan or commit to the delivery schedule. We would also like to be sure that any order we place is based on dates you can support.

Please note that this email is a status request and does not constitute a purchase order or confirmation of quantity. Any order will follow our formal written confirmation.

If a call would be easier, I would be happy to arrange one at your convenience. Thank you for your support and quick response.

Kind regards,
[Name]
Merchandising Executive
Meridian Apparels Ltd., Bangladesh
[Phone] | [Email]

## 2. Outstanding Supplier Information

| # | Information needed | Status in supplied data |
|---|---|---|
| 1 | Fabric production status (stage, quantity, completion date) | Not confirmed |
| 2 | Available ready stock and specification match | Not provided |
| 3 | Fabric testing status and test reports | Not confirmed |
| 4 | Dispatch date and expected arrival at factory | Not confirmed |
| 5 | Partial shipment capability | Not provided |
| 6 | Minimum order quantity and the latest date for final quantity | Not provided |
| 7 | Confirmation that the quotation of 12 Nov still stands (price, specification, validity) | Not provided |

## 3. Recommended Next Steps for the Merchandising Team

1. **Manager review before sending.** Confirm the reply deadline and the wording on quantity. The email deliberately shares only an indicative 9,000 to 10,000 range and does not mention the buyer's name, sample status or the PO discrepancy. Adjust if you prefer different disclosure.
2. **Follow up by phone** on the morning of 24 Nov if no reply has come, as cutting is planned for 25 Nov.
3. **Resolve the quantity discrepancy** (10,000 declared vs 9,000 in the size breakdown) with NorthStar, so the fabric requirement can be finalised. Fabric quantity must be calculated by Costing/Technical from confirmed consumption, which was not supplied.
4. **Get a management decision** on whether to place or reserve fabric before buyer sample approval, and record who authorised it.
5. **Record the supplier's reply** in the T&A tracker and re-run the calendar. If fabric arrival is later than 24 Nov, the 25 Nov cutting start needs to be reviewed by Production Planning.
6. **Involve QA** to compare the supplier's test information with the buyer's requirements once those are confirmed.
7. **Prepare a fallback.** If the supplier cannot meet the dates, ask Sourcing to identify alternatives, and ask the Manager whether to raise the schedule issue with the buyer.
8. **Update the supplier** promptly once quantity and approvals are settled, and issue a formal purchase order only after authorised approval.

I can also draft a short follow-up email or a WhatsApp/phone call script for the 24 Nov chase if that would help.

## Version 2 – Improved Prompt

ROLE
You are an AI Supplier Communication Assistant supporting the merchandising and sourcing departments of Meridian Apparels Ltd., a fictional apparel manufacturer in Bangladesh.

Your role is to draft professional supplier correspondence for authorised human review. You must not send emails, issue purchase orders, approve fabric purchases, confirm quantities or make binding delivery commitments.

OBJECTIVE
Prepare a concise, professional supplier-status enquiry for Eastern Knit Textiles Ltd. concerning fabric required for style NSF-LG-225. The communication should obtain the information needed to assess material readiness without disclosing unnecessary buyer or commercial information.

TASK 1 — IDENTIFY ESSENTIAL INFORMATION
Identify the most important supplier confirmations required:
1. Current fabric production status and any available stock.
2. Fabric specification, including GSM and width where available.
3. Fabric testing status and available reports.
4. Earliest achievable dispatch date and estimated arrival at the factory.
5. Partial delivery options, minimum order quantity and quotation validity.

Do not assume the fabric is already ordered, reserved, approved, manufactured or dispatched.

TASK 2 — DRAFT SUPPLIER EMAIL
Produce a professional email with:
- A clear subject line referencing style NSF-LG-225.
- A polite introduction referencing the quotation received on 12 November 2026.
- A concise explanation of why the information is needed.
- A numbered list of no more than five essential questions.
- A courteous closing requesting a timely response.

Keep the email body between 150 and 220 words, excluding subject line and signature.

TASK 3 — CONFIDENTIALITY AND COMMERCIAL CONTROLS
- Do not disclose the buyer's identity.
- Do not disclose buyer order values, unit prices, payment terms or the unresolved garment quantity discrepancy.
- Do not convert garment quantity into fabric metres or kilograms without confirmed fabric consumption data.
- Do not state that a purchase order has been issued to the fabric supplier.
- Do not promise to reserve or purchase stock.
- Do not confirm any delivery or production dates on the supplier's behalf.
- The factory cutting target of 25 November 2026 is an internal planning target, not a confirmed supplier commitment.
- No authorised supplier-response deadline was supplied. If a deadline would be useful, recommend one separately for manager approval rather than inserting it into the email as an agreed deadline.
- Use placeholders for unknown contact names and email addresses.

TASK 4 — INTERNAL FOLLOW-UP
After the email, provide:
A. An outstanding-information checklist.
B. A short internal action plan showing action, responsible department and priority.
C. A human-review checklist covering confidentiality, accuracy, deadline approval and purchase authority.

TASK 5 — QUALITY CONTROL
Before finalising, check that:
- All claims are supported by the supplied data.
- Unknown information is presented as a question rather than a fact.
- The email is concise and actionable.
- No supplier commitment or commercial authorisation is invented.
- Final sending remains subject to human approval.

REQUIRED OUTPUT
1. Supplier Email — Ready for Human Review
2. Outstanding Supplier Information
3. Internal Follow-Up Actions
4. Human Approval Checklist

SYNTHETIC BUSINESS DATA

Manufacturer: Meridian Apparels Ltd., Bangladesh
Supplier: Eastern Knit Textiles Ltd.
Buyer: NorthStar Fashion Ltd. (CONFIDENTIAL — do not disclose)
Internal PO Reference: PO-2026-1045
Style: NSF-LG-225
Product: Ladies' Cotton Leggings
Fabric: 95% Cotton, 5% Elastane
Colour: Black
Supplier Quotation Received: 12 November 2026
Fabric Order Quantity: Not finalised
Supplier Production Status: Not confirmed
Available Stock: Not confirmed
Fabric Dispatch Date: Not confirmed
Fabric Testing Status: Not confirmed
Planned Factory Cutting Start: 25 November 2026
Buyer Sample Approval: Pending
Declared Garment Quantity: 10,000 pieces
Size Breakdown Total: 9,000 pieces
Shipment Target: 15 December 2026
Authorised Supplier Response Deadline: Not supplied
Supplier Contact Name: Not supplied
Supplier Email Address: Not supplied

Generate the supplier communication package now.

## Version 2 – Claude Response
# Material Readiness Assessment: PO-2026-1045 / NSF-LG-225

*Preliminary analysis dated 23 Nov 2026, for authorised human review. It does not approve purchases, release stock, authorise cutting or confirm a schedule.*

**Correction to my earlier draft.** It broke several of your rules:
- It calculated how many garments the current stock could support.
- It rescaled requirements to 9,000 garments.
- It assumed linear scaling and carton ratios.
- It suggested evaluating a partial cutting plan.
- It labelled some items "not at risk".

This version removes all of these.

## A. Executive Readiness Summary

- **Quantity coverage:** 2 of 7 materials (sewing thread, care labels) reach 100% of their provisional requirement. The other 5 are short.
- **Actual readiness:** no material can be called production-ready. Physical receipt, inspection, buyer approval and allocation to this PO are all "Not confirmed". The one exception is main fabric testing, which is confirmed as pending.
- **Arrival dates:** none of the 5 outstanding balances has a confirmed date.
- **Immediate cutting concern:** main fabric. It is 600 kg short with testing pending, and buyer sample approval is also pending. Cutting is planned for 25 Nov.
- **Requirement basis:** all figures are provisional and based on the declared 10,000 garments. The size breakdown totals 9,000, so the final requirements cannot be set until the quantity and the approved BOM are confirmed.

## B. Material Quantity Validation Table

Units are kept separate and never summed across materials.

| # | Material | Unit | Required | Reported available | Shortage (calculated) | Coverage | Reported outstanding | Agrees? |
|---|---|---|---|---|---|---|---|---|
| 1 | Main fabric | kg | 1,800 | 1,200 | **600** | 66.7% | 600 | Yes |
| 2 | Waistband elastic | pcs | 10,000 | 8,000 | **2,000** | 80.0% | 2,000 | Yes |
| 3 | Sewing thread | cones | 120 | 120 | 0 | 100.0% | 0 | Yes |
| 4 | Care labels | pcs | 10,000 | 10,000 | 0 | 100.0% | 0 | Yes |
| 5 | Size labels | pcs | 10,000 | 7,000 | **3,000** | 70.0% | 3,000 | Yes |
| 6 | Polybags | pcs | 10,000 | 6,000 | **4,000** | 60.0% | 4,000 | Yes |
| 7 | Cartons | pcs | 200 | 150 | **50** | 75.0% | 50 | Yes |

Shortage = MAX(required − available, 0). All reported outstanding figures agree with the calculations.

**Quantity discrepancy (unresolved):** declared 10,000 vs size-breakdown sum 2,000 + 3,000 + 2,500 + 1,500 = 9,000 (difference 1,000 pcs). The report does not say which quantity governs, so the provisional requirements above are unverified.

## C. Physical, Quality and Allocation Status Assessment

| Material | A. Quantity coverage | B. Physical stock | C. Quality / buyer approval | D. Allocation to this PO | E. Balance arrival date |
|---|---|---|---|---|---|
| Main fabric | Short (66.7%) | Not confirmed | Testing **Pending**; buyer approval Not supplied | Not confirmed | Not confirmed |
| Waistband elastic | Short (80.0%) | Not confirmed | Not supplied | Not confirmed | Not confirmed |
| Sewing thread | Covered (100.0%) | Not confirmed | Not supplied | Not confirmed | None outstanding |
| Care labels | Covered (100.0%) | Not confirmed | Not supplied | Not confirmed | None outstanding |
| Size labels | Short (70.0%) | Not confirmed | Not supplied | Not confirmed | Not confirmed |
| Polybags | Short (60.0%) | Not confirmed | Not supplied | Not confirmed | Not confirmed |
| Cartons | Short (75.0%) | Not confirmed | Not supplied | Not confirmed | Not confirmed |

Thread and care labels have full reported quantity coverage only. "Available" is a reported figure and does not establish that stock is received, inspected, approved or reserved. They are **not** classed as production-ready.

## D. Production-Stage Dependency Analysis

The stage links below are potential operational dependencies. They are not stated in the report. No delay duration is claimed because no arrival dates exist.

| Stage | Materials involved | Confirmed quantity gap | Open verification |
|---|---|---|---|
| **Cutting** (planned 25 Nov) | Main fabric | 600 kg short | Testing pending; receipt, inspection and allocation of the 1,200 kg not confirmed; balance arrival not confirmed. Buyer sample approval is also pending. |
| **Sewing** | Waistband elastic; sewing thread | Elastic 2,000 pcs short; thread none | Elastic arrival not confirmed. Thread has full quantity coverage but its status is unverified. |
| **Finishing** | Size labels; care labels | Size labels 3,000 pcs short; care labels none | Size label arrival not confirmed. Care labels have full coverage but unverified status. |
| **Packing** | Polybags; cartons | Polybags 4,000 pcs short; cartons 50 pcs short | Arrival dates not confirmed. |

Fabric availability and testing are the immediate cutting concerns. Elastic and labels are potential sewing and finishing concerns. Polybags and cartons are potential packing concerns.

## E. Risk Register and Prioritised Actions

**Confirmed quantity shortages**

| ID | Material | Evidence | Confirmed gap | Stage affected | Missing verification | Priority | Owner | Recommended next action |
|---|---|---|---|---|---|---|---|---|
| M1 | Main fabric | 1,200 of 1,800 kg; testing pending; arrival not confirmed | 600 kg | Cutting, then later stages | Receipt, inspection, allocation, test result date, arrival date | **Critical** | Merchandising / Sourcing / Fabric Store / QA | Obtain confirmed arrival date and test timeline. Report both to Production Planning and the Manager for the cutting decision. |
| M2 | Waistband elastic | 8,000 of 10,000 pcs | 2,000 pcs | Sewing | Arrival date, receipt, approval | **High** | Sourcing / Merchandising | Obtain confirmed arrival date and approval status. |
| M3 | Size labels | 7,000 of 10,000 pcs | 3,000 pcs | Sewing / finishing | Arrival date, size-wise split, approval | **High** | Sourcing / Merchandising | Obtain arrival date; Warehouse to report size-wise stock if size-specific. |
| M4 | Polybags | 6,000 of 10,000 pcs | 4,000 pcs | Packing | Arrival date, packing specification (not supplied) | **High** | Sourcing / Packing | Obtain arrival date and confirm the specification. |
| M5 | Cartons | 150 of 200 pcs | 50 pcs | Packing / shipment | Arrival date, carton specification (not supplied) | **Medium** | Sourcing / Packing | Obtain arrival date. |

**Potential operational risks (require verification)**

| ID | Issue | Evidence | Stage affected | Priority | Owner | Recommended next action |
|---|---|---|---|---|---|---|
| R1 | Buyer sample approval pending | "Buyer Sample Approval: Pending" | Cutting onwards | **Critical** | Merchandising Manager | Obtain approval status and timing. Authorised management decides on any cutting before approval. |
| R2 | Quantity discrepancy (10,000 vs 9,000) | Declared vs size total | All materials | **Critical** | Merchandiser / Manager | Obtain written buyer confirmation. Finalise requirements only against the confirmed quantity and the approved BOM. |
| R3 | "Available" stock not verified as received, inspected or allocated | Not confirmed for all 7 items | Cutting through packing | **High** | Warehouse / QA | Physically verify on-hand quantity, inspection status and allocation. |
| R4 | Thread and care labels: full quantity, status unverified | 100.0% coverage; approval not supplied | Sewing / finishing | Medium | Warehouse / QA / Merchandising | Verify quality and buyer approval status. |
| R5 | No approved BOM, consumption or wastage data | Additional conditions | All | **High** | Merchandising / Costing | Obtain the approved BOM. |
| R6 | No permission for partial production or material release | Additional conditions | Cutting onwards | **High** | Management | Any such decision rests with authorised management. |

**Recommended verification by function (none is recorded as completed)**
- **Merchandising:** buyer quantity confirmation, sample approval, BOM, trim and label approvals.
- **Sourcing:** supplier-confirmed arrival dates for all five balances. Any purchase, substitution or quantity change needs authorised approval.
- **Warehouse:** physical stock, location, inspection status and allocation.
- **QA:** fabric test timeline and results, and inspection of reported available materials.
- **Production Planning:** review the 25 Nov cutting target against confirmed material and approval dates, then update the T&A.

## F. Data Limitations and Human Approval Requirements

**Not supplied or not verifiable**
- The approved BOM, consumption and wastage data.
- The confirmed garment quantity. Final material requirements cannot be set without it and the approved BOM.
- Arrival dates for all five outstanding balances.
- Receipt, inspection, allocation and buyer approval status for every item, except that fabric testing is confirmed as pending.
- Size-wise stock, supplier details and order status for outstanding items.
- Any permission for partial production or release.

**Deliberately not done:** no garment-equivalent stock calculations, no 9,000-based requirements, no revised purchase quantities, no supplier commitments and no delay durations.

**Human approvals required**
- Final quantity and BOM (Merchandising Manager).
- Material purchases and substitutions (authorised purchaser).
- Quality release of fabric and trims (QA).
- Stock release, cutting start and any partial production (authorised management and Production Planning).

## Evaluation and Improvements

Version 1 generated a useful preliminary production schedule but introduced unsupported assumptions about overlapping activities and export processing times. Version 2 improved accuracy by introducing explicit working-day calculations, clearer production dependencies and evidence-based scheduling constraints. It also distinguished calculated dates from unverified assumptions. Version 2 was selected because it provides more reliable critical path planning, reduces misleading delivery forecasts and supports informed management decisions while maintaining human oversight.

**Final Selected Version: Version 2**
