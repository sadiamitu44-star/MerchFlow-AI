# P08 – Delivery Risk Escalation Assistant

## Version 1 – Original Prompt

Act as an experienced apparel merchandising and delivery risk coordinator working for Meridian Apparels Ltd., a fictional garment manufacturer in Bangladesh.

Your task is to review the delivery risk status of style NSF-LG-225 and prepare a shipment risk escalation report for senior management.

Please:
1. Review the purchase order, sample approval, material, production, quality and logistics information.
2. Identify confirmed problems, unresolved risks and missing information.
3. Classify the major delivery risks by priority.
4. Explain how each issue could affect the planned shipment.
5. Assess whether the available evidence supports meeting the shipment target of 15 December 2026.
6. Recommend practical actions for Merchandising, Planning, Production, QA, Sourcing and Logistics.
7. Prepare an internal escalation message to the Merchandising Manager.
8. Draft a professional buyer communication for management review if escalation to the buyer is appropriate.

Use clear tables, a concise management summary and an action tracker. Distinguish verified facts from potential consequences. Do not invent supplier delivery dates, approval dates, production capacity, shipment delays, buyer concessions or recovery commitments.

SYNTHETIC DELIVERY RISK DATA

Manufacturer: Meridian Apparels Ltd., Bangladesh
Buyer: NorthStar Fashion Ltd.
PO Number: PO-2026-1045
Style: NSF-LG-225
Product: Ladies' Cotton Leggings
Review Date: 7 December 2026
Target Shipment Date: 15 December 2026

PURCHASE ORDER
- Declared order quantity: 10,000 garments.
- Size breakdown total: 9,000 garments.
- Difference: 1,000 garments.
- Buyer quantity confirmation or amended PO: Not received.

SAMPLE APPROVAL
- Revised fit sample waist measurement was accepted on 20 November.
- Fit acceptance remained conditional.
- Elastic quality and care-label artwork confirmations were outstanding in the supplied approval record.
- Pre-production sample was submitted on 21 November.
- No written final sample approval or written bulk-cutting approval is evidenced in this snapshot.
- The current status of any subsequent buyer correspondence is unknown.

MATERIAL READINESS
- Provisional main fabric requirement: 1,800 kg.
- Reported main fabric quantity: 1,200 kg.
- Provisional quantity gap: 600 kg.
- Fabric testing status: Not confirmed as completed.
- Material receipt, inspection and allocation status: Not verified.
- Supplier delivery or replenishment date: Not supplied.
- Other material readiness and revised BOM status: Not supplied.

PRODUCTION PROGRESS
- At the 3 December reporting point, planned sewing output was 2,000 pieces and reported sewing output was 1,800 pieces.
- Cumulative reported-output shortfall: 200 pieces.
- These are historical reported output figures, not confirmed accepted good-piece quantities.
- Current sewing output as of 7 December: Not supplied.
- Remaining sewing workload, available capacity and validated revised schedule: Not supplied.

QUALITY
- An inspection snapshot dated 4 December recorded 45 defect occurrences across 200 inspected garments.
- Unique defective-garment count: Not supplied.
- Buyer AQL and inspection acceptance criteria: Not supplied.
- QA disposition, rework and accepted-piece results: Not supplied.
- No quality pass/fail or shipment release is established.

LOGISTICS AND SHIPMENT
- Shipment target: 15 December 2026.
- Whether this date means ex-factory, FOB handover, vessel departure or destination arrival: Not confirmed.
- Packing completion: Not confirmed.
- Final inspection booking and outcome: Not supplied.
- Freight booking, document readiness and cargo handover: Not supplied.
- No confirmed revised shipment forecast is available.

IMPORTANT CONDITIONS
- This is a self-contained hypothetical management snapshot using selected historical figures for analysis.
- It does not prove that previous buyer approvals, factory releases or other operational prerequisites were satisfied.
- The absence of a record in this snapshot is not automatically proof that an action never occurred.
- Do not assume the historical 3 December production shortfall remains unchanged on 7 December.
- Do not combine provisional quantities with unverified final order requirements to calculate a completion forecast.
- Escalation recommendations must remain subject to authorised human review.
- Do not send any email or make a buyer commitment.

Prepare the delivery risk escalation assessment and communication drafts now.

## Version 1 – Claude Response

# Shipment Risk Escalation Assessment: PO-2026-1045 / NSF-LG-225

*Review date: Mon 7 Dec 2026. Target shipment: Tue 15 Dec 2026 (8 calendar days away). This is decision-support analysis of the supplied snapshot only. It is not a shipment commitment, a buyer concession or a recovery plan. No email has been sent. Absence of a record in the snapshot does not prove that an action never occurred.*

## 1. Management Summary

- **The snapshot does not evidence that the 15 Dec target can be met.** It also does not demonstrate a delay, because current output, remaining workload, capacity, supplier dates and logistics status are all unknown.
- **Confirmed problems:**
  - The quantity conflict (10,000 declared vs 9,000 size breakdown) is unresolved, with no buyer confirmation or amended PO.
  - The reported main fabric quantity is 1,200 kg against a provisional requirement of 1,800 kg (66.7% coverage, 600 kg gap).
  - A 4 Dec inspection recorded 45 defect occurrences in a 200-garment sample, with no disposition.
  - A 200-piece reported-output shortfall existed at 3 Dec, a historical figure.
- **Unevidenced prerequisites:** written final sample approval, written bulk-cutting approval, fabric test completion, packing completion, final inspection, freight booking and shipping documents.
- **Definition gap:** it is not confirmed whether 15 Dec means ex-factory, FOB handover, vessel departure or destination arrival. This determines what must be complete by that date.
- **Recommendation:** escalate internally now. Whether to approach the buyer, and on what, is a management decision. A draft is in Section 8.

## 2. Verified Facts vs Unknowns

| Area | Verified in snapshot | Not supplied or unverified |
|---|---|---|
| **PO** | 10,000 declared; size total 9,000 (difference 1,000 pcs) | Buyer confirmation or amended PO |
| **Sample approval** | Waist accepted 20 Nov. Fit acceptance conditional. Elastic quality and care-label artwork were outstanding. Pre-production sample submitted 21 Nov. | Written final sample approval and bulk-cutting approval (not evidenced). Any later buyer correspondence (unknown). |
| **Materials** | Fabric: 1,200 of 1,800 kg reported, a 600 kg provisional gap | Fabric test completion, receipt, inspection and allocation, supplier date, other materials, revised BOM |
| **Production** | At 3 Dec: 2,000 planned, 1,800 reported (-200). Reported output only. | Output as of 7 Dec, accepted good pieces, remaining workload, capacity, validated schedule |
| **Quality** | 4 Dec: 45 occurrences in 200 garments | Unique defective garments, buyer AQL and criteria, QA disposition, rework and accepted-piece results |
| **Logistics** | Target 15 Dec | Date definition, packing completion, final inspection, freight booking, documents, handover, revised forecast |

The 3 Dec shortfall is not assumed to remain unchanged at 7 Dec. The 1,800 kg requirement is provisional and is not combined with unverified quantities to forecast completion.

## 3. Risk Register

| ID | Risk | Class. | Potential effect on shipment | Priority |
|---|---|---|---|---|
| R1 | Quantity conflict (10,000 vs 9,000), no buyer confirmation | **Confirmed** | Quantities for materials, production and packing cannot be final, and the shipment quantity is uncertain | **Critical** |
| R2 | Final sample approval and written bulk-cutting approval not evidenced; conditions open; later correspondence unknown | **Confirmed (not evidenced)** | Risk of rework, change or hold if approval conditions are unresolved or the buyer's requirements apply | **Critical** |
| R3 | Main fabric: 600 kg provisional gap, testing not confirmed, supplier date not supplied, receipt and inspection not verified | **Confirmed (gap); Unknown (dates)** | Any dependent production depends on fabric that is unconfirmed. No delay duration can be stated. | **Critical** |
| R4 | Shipment date definition not confirmed | **Unknown** | The required completion point is unclear, so readiness cannot be judged | **Critical** |
| R5 | Production: 200-pc reported shortfall at 3 Dec, current output and remaining workload unknown | **Confirmed (historical); Unknown (current)** | Completion status cannot be determined | **High** |
| R6 | Quality: 45 occurrences, no disposition, AQL unknown | **Confirmed (record); Unknown (outcome)** | Accepted output and rework volume unknown. Release not established. | **High** |
| R7 | Logistics readiness: packing, final inspection, freight, documents, handover not supplied | **Unknown** | Post-production steps cannot be assessed | **High** |
| R8 | Other materials and revised BOM not supplied | **Unknown** | Trim and packing readiness cannot be assessed | **High** |

## 4. How Each Issue Could Affect the Shipment

These are potential consequences, not forecasts. No delay, duration or probability is stated.

| Issue | Possible mechanism |
|---|---|
| Quantity conflict | Production, materials and packing may be planned against the wrong quantity. Shipment may be for 9,000 or 10,000 pieces. |
| Approval status | Without evidenced approval, bulk work already done may need rework or may not be accepted. Buyer requirements for release are not supplied. |
| Fabric | Work needing the missing fabric cannot be confirmed as completable. The gap is provisional and its effect depends on the final quantity and BOM. |
| Production | Any uncovered shortfall must be addressed by the plan. Capacity and approved resource options are unknown. |
| Quality | Rework, re-inspection or rejection may reduce accepted output. Quantities are unknown. |
| Date definition and logistics | Each possible meaning (ex-factory, FOB handover, vessel departure, destination arrival) requires different work before 15 Dec. Booking and documents are not evidenced. |

## 5. Can the Evidence Support the 15 Dec Target?

| Question | Finding |
|---|---|
| Does the snapshot show the target is achievable? | **No.** Key prerequisites are unevidenced (Section 2). |
| Does it show the target will be missed? | **No.** Current production, remaining workload, capacity and logistics data are not supplied. |
| Can a revised date be stated? | **No.** No validated schedule exists, and none is proposed here. |
| Overall | **Not determinable and unsupported.** The target should not be confirmed to the buyer, and no delay should be asserted, until the data below is obtained. |

## 6. Action Tracker

*Recommendations only. None is recorded as completed. Overtime, resource changes, revised schedules and buyer commitments need authorised approval.*

| # | Action | Department | Priority | Evidence needed | Decision owner |
|---|---|---|---|---|---|
| 1 | Escalate this report to the Merchandising Manager (Section 7) | Merchandising | Critical | n/a | Merchandising Manager |
| 2 | Obtain written buyer quantity confirmation or an amended PO | Merchandising | Critical | Buyer's written confirmation | Merchandising Manager / buyer |
| 3 | Check records for any buyer correspondence since 21 Nov, and confirm final sample approval, conditions closed and bulk-cutting approval status | Merchandising / Sampling | Critical | Written buyer decision | Buyer / Merchandising Manager |
| 4 | Confirm what 15 Dec means, with the buyer, in writing | Merchandising / Logistics | Critical | Buyer's written definition | Merchandising Manager |
| 5 | Verify fabric receipt, inspection and allocation. Obtain the test status and the supplier's confirmed delivery date. | Sourcing / Fabric Store / QA | Critical | Store records, test report, supplier-confirmed date | Sourcing Manager / QA |
| 6 | Report the current sewing output, accepted output and remaining workload, then reassess against a validated schedule | Production / Planning | High | Current output, accepted-piece data, workload, capacity | Production Planning Manager |
| 7 | Complete the QA assessment of the 4 Dec findings: unique defective garments, classification against the buyer's standard, rework and rejection status | QA | High | Garment-level data, buyer AQL and criteria | QA Manager / buyer for any concession |
| 8 | Confirm the status of other materials and the revised BOM | Merchandising / Sourcing | High | Approved BOM, material status report | Merchandising Manager |
| 9 | Confirm packing status, final inspection booking, freight booking, documents and handover plan | Logistics / QA / Shipping | High | Booking and readiness records | Logistics Manager |
| 10 | Decide whether any recovery option is to be evaluated, and approve any resource or overtime | Management | High | Items 5, 6 and 9 | Authorised management |
| 11 | Re-issue this assessment when the above data is available | Merchandising / Planning | High | Updated records | Merchandising Manager |

## 7. Draft Internal Escalation Message

*For the Merchandising Manager. Draft, not sent.*

**To:** [Merchandising Manager]
**Cc:** [Production Planning Manager]; [QA Manager]; [Sourcing Manager]; [Logistics Manager]
**Subject:** Escalation: Delivery Risk, PO-2026-1045 / NSF-LG-225 (Target 15 Dec)

Dear [Name],

Our 7 Dec review of NSF-LG-225 found that the records do not show that the 15 December 2026 target is achievable. They also do not show that it will be missed, because key data is missing.

**Confirmed:**
- The PO quantity conflicts (10,000 declared vs 9,000 size total), with no buyer confirmation.
- Reported main fabric is 1,200 kg against a provisional 1,800 kg requirement, and testing is not confirmed as complete.
- A 4 Dec inspection recorded 45 defect occurrences in 200 garments, with no disposition.
- At 3 Dec, reported sewing output was 200 pieces behind plan (historical).

**Not evidenced:** written final sample approval and bulk-cutting approval, supplier delivery dates, current output, remaining workload, packing, final inspection and freight status. The meaning of "15 December" is also unconfirmed.

**Decisions and support requested:**
1. Whether to contact the buyer now on the items they control (quantity, approval status, date definition). A draft is attached.
2. Direction to Sourcing, Production Planning, QA and Logistics to supply the missing data.
3. Whether any recovery options should be evaluated. They would need your approval.

I have not stated any delay or commitment to the buyer.

Regards,
[Name], Merchandising

## 8. Draft Buyer Communication

*For management review. Escalation to the buyer on the items below is appropriate in my assessment, because they need the buyer's input. Whether to share fabric, production or quality matters is a management decision, so they are not included. Not sent. No response deadline is inserted because none has been agreed.*

**To:** [Buyer contact name], NorthStar Fashion Ltd.
**Cc:** [Merchandising Manager]
**Subject:** Information Needed for Shipment Planning: Style NSF-LG-225 / PO-2026-1045

Dear [Buyer contact name],

We are reviewing our plan for the above order against your shipment target of 15 December 2026, and need your confirmation on a few points to plan accurately:

1. **Quantity:** the PO shows a total of 10,000 pieces, but the size breakdown adds up to 9,000. Please confirm the correct quantity and issue an amended PO if needed.
2. **Sample and bulk approval:** please confirm the status of your decision on the pre-production sample submitted on 21 November, the elastic quality and care-label artwork conditions from your 20 November comments, and your written bulk-production approval.
3. **Shipment date:** please confirm whether 15 December means ex-factory, FOB handover, vessel departure or arrival at destination.
4. **Inspection and requirements:** please share your acceptance criteria and any inspection requirements for this order.

Once we have your replies, we will review our plan against your target and come back to you. Please let us know if a call would help.

Kind regards,
[Name], Merchandising Executive
Meridian Apparels Ltd., Bangladesh
[Phone] | [Email]

## 9. Limitations and Required Human Decisions

- This snapshot is self-contained. It does not prove earlier approvals, releases or prerequisites, and its absences are not proof that actions did not happen.
- I have invented no supplier dates, approval dates, capacity, delays, concessions or recovery commitments.
- The 3 Dec production and 4 Dec quality figures are historical, and no completion forecast is calculated.
- **Authorised humans must decide:**
  - Whether to escalate to the buyer and what to disclose.
  - Any request to change the target date.
  - Any recovery option, overtime or resource change.
  - QA disposition, and any concession (which needs buyer approval).
  - Any shipment commitment.

I can also prepare a one-page status dashboard for the management meeting, or a call script for the buyer follow-up.

## Version 2 – Improved Prompt

ROLE
You are an AI Delivery Risk and Merchandising Escalation Analyst supporting Meridian Apparels Ltd., a fictional apparel manufacturer in Bangladesh.

Your role is to assess delivery risks, validate evidence, prioritise issues, recommend escalation and draft communications for authorised human review.

You cannot confirm shipment feasibility, approve production, amend purchase orders, authorise recovery measures, grant buyer concessions, send emails or commit to shipment dates.

OBJECTIVE
Assess the delivery-risk snapshot dated 7 December 2026 for PO-2026-1045 / style NSF-LG-225, with a target shipment date of 15 December 2026.

TASK 1 — EVIDENCE VALIDATION
Separate information into four categories:
1. Confirmed fact: explicitly recorded or arithmetically validated.
2. Confirmed unresolved issue: an identified discrepancy or condition explicitly recorded as unresolved.
3. Not evidenced or unverified: information absent from the snapshot, without proof that the action never occurred.
4. Potential consequence: a possible future operational impact, not an established outcome.

Do not classify missing written approval records as proof that approval was refused or never granted.

TASK 2 — VALIDATE QUANTITIES AND HISTORICAL FIGURES
Check:
- Declared PO quantity 10,000 versus size breakdown 9,000: discrepancy 1,000 garments.
- Provisional fabric requirement 1,800 kg versus reported 1,200 kg: provisional gap 600 kg, numerical coverage 66.7%.
- At 3 December, reported sewing output 1,800 versus 2,000 planned: historical shortfall 200 pieces.
- At 4 December, 45 defect occurrences were recorded in 200 inspected garments.

Do not:
- Treat reported fabric as approved, inspected or allocated.
- Treat the 3 December shortfall as the current 7 December shortfall.
- Treat 45 defect occurrences as 45 unique defective garments.
- Treat provisional requirements as an approved final BOM.
- Combine these figures to generate a production or delivery forecast.

TASK 3 — RISK REGISTER WITH TRANSPARENT PRIORITY
For each risk provide:
- Unique risk ID R01 onward.
- Issue or risk.
- Evidence status: Confirmed / Confirmed unresolved / Not evidenced / Potential.
- Evidence supporting the classification.
- Potential impact on shipment.
- Priority: Critical / High / Medium.
- Reason for priority.
- Responsible department.
- Missing evidence.
- Next action.
- Required closure evidence.

Priority guidance:
Critical = an unresolved fundamental decision or prerequisite that requires urgent management attention to assess the shipment target.
High = a material operational risk or information gap requiring prompt verification.
Medium = a supporting issue that should be tracked but is not currently shown to be a fundamental blocker.

These are internal triage priorities, not statistically calculated risk scores. Do not invent probability or monetary impact.

TASK 4 — DELIVERY FEASIBILITY
Evaluate whether the snapshot supports:
A. A confirmed on-time shipment.
B. A confirmed shipment delay.
C. A revised shipment date.

If evidence is insufficient, explicitly state that feasibility and delay are not determinable.

The shipment milestone itself is unconfirmed: 15 December might mean ex-factory, FOB handover, vessel departure or destination arrival.

Do not infer any of these meanings or assume a freight lead time.

TASK 5 — ESCALATION DECISION FRAMEWORK
Classify recommended actions into:
A. Immediate internal verification: check existing records and obtain current operational status.
B. Buyer confirmation required: matters requiring the buyer's written decision or clarification.
C. Management decision required: disclosure, recovery measures, revised schedules or commitments.
D. Monitor and update: issues requiring new evidence before further escalation.

For each action specify the owner, evidence required and decision authority.

Do not invent a buyer response deadline or claim that escalation has occurred.

TASK 6 — EVIDENCE-BASED ACTION TRACKER
Create a prioritised action tracker with:
- Action ID.
- Related risk ID.
- Department owner.
- Requested action.
- Required evidence.
- Closure criterion.
- Human decision owner.
- Current status: Open / Awaiting evidence / Decision required.

Sending an email, requesting information or assigning an action does not by itself close a risk.

TASK 7 — INTERNAL MANAGEMENT ESCALATION
Draft a concise professional internal email to the Merchandising Manager.

Include:
- The shipment target and its unconfirmed milestone definition.
- The confirmed numerical discrepancies.
- Historical production and quality findings.
- The distinction between missing records and proven non-compliance.
- The immediate decisions and information required.
- No unsupported delay estimate, delivery commitment or recovery promise.

This must be a draft only.

TASK 8 — BUYER COMMUNICATION AND DISCLOSURE CONTROL
Draft a buyer email for management approval, limited to buyer-controlled questions:
1. Correct PO quantity and size breakdown.
2. Current sample, artwork and bulk-production approval status.
3. Meaning of the 15 December shipment milestone.
4. Applicable final inspection or acceptance requirements.

Do not disclose internal fabric shortages, production shortfalls, quality occurrences, operational capacity or recovery assumptions without management authorisation.

Do not:
- State that shipment will be delayed.
- Guarantee the target will be met.
- Invent an agreed response deadline.
- Claim that the buyer previously approved or rejected anything not supported by the records.
- Send the email.

TASK 9 — HUMAN OVERSIGHT
Explain that:
- Buyer approvals and commercial changes require buyer decisions.
- QA disposition requires authorised QA or management decisions.
- Production recovery, overtime and staffing changes require authorised management approval.
- Any shipment commitment or revised delivery date requires appropriate human authorisation.
- AI recommendations are not operational instructions.

TASK 10 — SCENARIO INTEGRITY
This is a self-contained hypothetical management snapshot using selected historical observations.

It does not prove earlier sample approval, fabric release, cutting authorisation or quality acceptance.

The absence of a record in this snapshot is not proof that the action never occurred.

REQUIRED OUTPUT
A. Executive Delivery Risk Summary
B. Evidence Classification and Calculation Checks
C. Prioritised Risk Register
D. Shipment Feasibility Assessment
E. Escalation Decision Framework
F. Action and Closure Tracker
G. Draft Internal Management Escalation Email
H. Draft Buyer Communication
I. Limitations and Required Human Decisions

Use concise, professional management language. Clearly distinguish verified evidence, unresolved issues, unknowns, hypotheses and recommendations.

SYNTHETIC DELIVERY RISK DATA

Manufacturer: Meridian Apparels Ltd., Bangladesh
Buyer: NorthStar Fashion Ltd.
PO Number: PO-2026-1045
Style: NSF-LG-225
Product: Ladies' Cotton Leggings
Review Date: 7 December 2026
Target Shipment Date: 15 December 2026

PURCHASE ORDER
Declared Quantity: 10,000 garments
Size Breakdown Total: 9,000 garments
Quantity Discrepancy: 1,000 garments
Buyer Confirmation or Amended PO: Not received in supplied records

SAMPLE APPROVAL
Revised Waist Measurement: Accepted on 20 November
Overall Fit Acceptance: Conditional
Elastic Quality Confirmation: Outstanding in the supplied approval record
Care-Label Artwork Confirmation: Outstanding in the supplied approval record
Pre-Production Sample: Submitted 21 November
Written Final Sample Approval: Not evidenced
Written Bulk-Cutting Approval: Not evidenced
Subsequent Buyer Correspondence: Unknown

MATERIALS
Provisional Main Fabric Requirement: 1,800 kg
Reported Main Fabric Quantity: 1,200 kg
Provisional Gap: 600 kg
Fabric Testing Completion: Not confirmed
Physical Receipt, Inspection and Allocation: Unverified
Supplier Replenishment Date: Not supplied
Approved Revised BOM: Not supplied
Other Material Readiness: Not supplied

PRODUCTION
Historical Reporting Date: 3 December
Planned Sewing Output: 2,000 pieces
Reported Sewing Output: 1,800 pieces
Historical Reported Shortfall: 200 pieces
Current Sewing Output on 7 December: Unknown
Accepted Good-Piece Quantity: Unknown
Remaining Sewing Workload: Unknown
Available Capacity: Unknown
Validated Revised Production Schedule: Not supplied

QUALITY
Inspection Date: 4 December
Inspection Sample: 200 garments
Recorded Defect Occurrences: 45
Unique Defective Garments: Unknown
Buyer AQL and Acceptance Criteria: Not supplied
QA Disposition: Unknown
Rework, Rejection and Accepted Output: Unknown

LOGISTICS
Shipment Target: 15 December
Shipment Milestone Definition: Not confirmed
Packing Completion: Unknown
Final Inspection Booking and Result: Unknown
Freight Booking: Unknown
Shipping Document Readiness: Unknown
Cargo Handover Status: Unknown
Validated Revised Shipment Forecast: Not supplied

IMPORTANT RESTRICTIONS
- No supplier delivery dates, approval dates, recovery durations or delivery-delay estimates may be invented.
- No buyer response deadline is agreed.
- No email has been sent.
- No production recovery action has been authorised.
- The snapshot does not establish whether the target will be met or missed.
- All outputs are for authorised human review.

Generate the evidence-controlled delivery risk escalation assessment now.

## Version 2 – Claude Response

# Delivery Risk Escalation Assessment: PO-2026-1045 / NSF-LG-225

*Review date: Mon 7 Dec 2026. Target shipment: 15 Dec 2026 (milestone definition not confirmed). This is a draft for authorised human review. I cannot confirm feasibility, approve production, amend POs, authorise recovery, grant concessions, send emails or commit to dates. No email has been sent. This is a self-contained snapshot and does not prove earlier approvals, releases or quality acceptance.*

**Correction to my earlier draft.** It fell short of your controls in these ways:
- It blended evidence categories (for example, "Confirmed (not evidenced)").
- It wrote that "bulk work already done" might need rework, which assumes bulk work occurred.
- It had no R01-style IDs, reasons for priority, closure criteria, status column or A to D escalation framework.
- It advised that the target "should not be confirmed to the buyer", which is a management decision, not mine.

This version corrects these points.

## A. Executive Delivery Risk Summary

- **The snapshot does not support a confirmed on-time shipment, and it does not support a confirmed delay.** Both are not determinable, because key evidence is absent.
- **Confirmed unresolved issues:**
  - The PO quantity discrepancy is 1,000 garments, with no buyer confirmation in the supplied records.
  - The sample fit acceptance is conditional, with elastic quality and care-label artwork outstanding in the approval record.
  - There is a 600 kg provisional fabric gap.
- **Not evidenced (not proof that actions never occurred):**
  - Written final sample approval and written bulk-cutting approval.
  - Fabric test completion, receipt, inspection and allocation.
  - Current sewing output.
  - Packing, final inspection, freight and documents.
- **Milestone gap:** 15 Dec could mean ex-factory, FOB handover, vessel departure or destination arrival. No meaning is inferred and no freight lead time is assumed.
- **Recommendation:** escalate internally now for verification and decisions. Whether to contact the buyer, and what to disclose, is a management decision.

## B. Evidence Classification and Calculation Checks

### B1. Evidence classification

| Category | Items |
|---|---|
| **1. Confirmed fact** | Declared quantity 10,000; size total 9,000 (as supplied); revised waist measurement accepted 20 Nov; pre-production sample submitted 21 Nov; fabric reported 1,200 kg vs provisional 1,800 kg; at 3 Dec, 2,000 planned vs 1,800 reported sewing pieces; 4 Dec inspection recorded 45 occurrences in 200 inspected garments |
| **2. Confirmed unresolved issue** | Quantity discrepancy (no buyer confirmation or amended PO in supplied records); conditional fit acceptance, with elastic quality and care-label artwork outstanding in the record; provisional fabric gap |
| **3. Not evidenced / unverified** | Written final sample approval; written bulk-cutting approval; later buyer correspondence; fabric test completion, receipt, inspection, allocation; supplier date; approved BOM; other materials; current output; accepted pieces; remaining workload; capacity; validated schedule; QA disposition; packing; final inspection; freight; documents; handover; milestone definition |
| **4. Potential consequence** | See Section C. These are possible impacts, not outcomes. |

Missing written approvals are **not** treated as proof that approval was refused or never granted.

### B2. Calculation checks

| Check | Calculation | Result | Note |
|---|---|---|---|
| Quantity discrepancy | 10,000 − 9,000 | **1,000 garments** (10.0% of declared) | The size total is taken as supplied. The size-wise figures are not in this snapshot, so they are not re-added. |
| Fabric gap | 1,800 − 1,200 | **600 kg** | Provisional gap |
| Fabric coverage | 1,200 ÷ 1,800 × 100 | **66.7%** | Numerical coverage only. It is not approved, inspected or allocated stock, and the 1,800 kg is not an approved BOM figure. |
| Sewing shortfall at 3 Dec | 2,000 − 1,800 | **200 pieces** | **Historical.** It is not the 7 Dec position, and reported output is not accepted good output. |
| Defect occurrences | 45 in 200 inspected garments | 45 occurrences | **Not** 45 defective garments, and no rate is derived. |

No production or delivery forecast is built from these figures.

## C. Prioritised Risk Register

Priorities are internal triage judgements. They are not statistical scores, and no probability or monetary impact is stated.

### C1. Classification and priority

| ID | Issue / risk | Evidence status | Evidence | Potential impact on shipment | Priority | Reason for priority |
|---|---|---|---|---|---|---|
| R01 | PO quantity discrepancy | **Confirmed unresolved** | 10,000 vs 9,000; no buyer confirmation in records | Quantities for materials, production, packing and the shipment may be planned against the wrong figure | **Critical** | Fundamental unresolved commercial decision |
| R02 | Shipment milestone undefined | **Not evidenced** | "Not confirmed" | The work needed by 15 Dec cannot be defined, so the target cannot be assessed | **Critical** | Fundamental prerequisite to assessing the target |
| R03 | Sample conditions open: elastic quality, care-label artwork | **Confirmed unresolved** | Outstanding in the supplied approval record; fit acceptance conditional | Open conditions may require further buyer interaction or changes. Their effect is unknown. | **Critical** | Unresolved buyer decision that bears on proceeding |
| R04 | Written final sample approval and bulk-cutting approval not evidenced; later correspondence unknown | **Not evidenced** | None in snapshot | Buyer requirements for proceeding are unknown. Absence does not prove non-compliance. | **Critical** | Fundamental prerequisite, status unknown |
| R05 | Main fabric: 600 kg provisional gap; testing, receipt, inspection, allocation, supplier date unverified | **Confirmed unresolved** (gap) / **Not evidenced** (rest) | Section B2; fields "Not confirmed" or "Unverified" | Fabric-dependent work cannot be confirmed as supportable. No delay duration can be stated. | **High** | Material operational risk. The gap is against a provisional requirement, so it is not shown to be a fundamental blocker until the BOM is approved. |
| R06 | Approved revised BOM and other material readiness not supplied | **Not evidenced** | "Not supplied" | Trim and packing readiness cannot be assessed | **High** | Information gap needing prompt verification |
| R07 | Production: 3 Dec shortfall of 200 pcs (historical); current output, accepted pieces, workload, capacity, schedule unknown | **Confirmed** (historical) / **Not evidenced** (current) | Section B2 | Completion status cannot be determined | **High** | Material operational information gap |
| R08 | Quality: 45 occurrences recorded; unique defective garments, AQL, disposition, rework unknown | **Confirmed** (record) / **Not evidenced** (outcome) | 4 Dec inspection | Accepted output and rework volume unknown. Release is not established. | **High** | Material risk requiring prompt verification |
| R09 | Logistics readiness: packing, final inspection, freight, documents, handover unknown | **Not evidenced** | "Unknown" | Post-production steps cannot be assessed | **High** | Information gap affecting any milestone definition |

### C2. Ownership and closure

| ID | Responsible department | Missing evidence | Next action | Required closure evidence |
|---|---|---|---|---|
| R01 | Merchandising | Buyer's written quantity | Seek buyer confirmation or an amended PO | Written confirmation or amended PO on file |
| R02 | Merchandising / Logistics | Buyer's written definition | Ask the buyer to define the milestone | Written definition on file |
| R03 | Merchandising / Sampling / QA | Buyer's requirements and acceptance of elastic evidence and artwork | Check records for later correspondence, then ask the buyer | Written buyer decision on each condition |
| R04 | Merchandising | Written final sample approval; written bulk-cutting approval | Search existing records, then ask the buyer for the status and process | Written approvals located or issued, or the buyer's stated process documented |
| R05 | Sourcing / Fabric Store / QA | Test status, receipt and inspection records, allocation, supplier date | Verify store and QA records; request the supplier's date | Records plus supplier-confirmed date, or documented absence |
| R06 | Merchandising / Sourcing | Approved BOM; material status | Obtain the approved BOM and the status of all materials | Approved BOM; material status report |
| R07 | Production / Planning | Current output, accepted pieces, workload, capacity | Report the 7 Dec position and the remaining workload | Current data and a validated schedule from authorised planners |
| R08 | QA | Unique defective garments, AQL, disposition, rework data | Complete the QA assessment against the buyer's criteria | Documented QA disposition |
| R09 | Logistics / QA / Shipping | Booking and readiness records | Obtain status of each logistics step | Records for packing, inspection, freight, documents, handover |

## D. Shipment Feasibility Assessment

| Question | Finding |
|---|---|
| **A. Confirmed on-time shipment?** | **Not supported.** Key prerequisites are unevidenced and the milestone is undefined. |
| **B. Confirmed shipment delay?** | **Not supported.** Current output, workload, capacity and logistics status are unknown, and the snapshot establishes neither success nor failure. |
| **C. Revised shipment date?** | **Not determinable.** No validated schedule exists, and none is proposed. |

**Conclusion:** feasibility and delay are **not determinable** from this snapshot. Four possible milestone meanings exist. None is inferred, and no freight lead time is assumed.

## E. Escalation Decision Framework

| Class | Action | Owner | Evidence required | Decision authority |
|---|---|---|---|---|
| **A. Immediate internal verification** | Check existing records for buyer correspondence, approvals and test reports | Merchandising / Sampling | Records or documented absence | Merchandising Manager |
| A | Confirm fabric receipt, inspection, allocation and supplier date | Sourcing / Fabric Store / QA | Store and QA records | Sourcing Manager / QA |
| A | Report 7 Dec sewing output, accepted pieces and remaining workload | Production / Planning | Current production and QA records | Production Planning Manager |
| A | Confirm packing, final inspection, freight and document status | Logistics / QA | Booking and readiness records | Logistics Manager |
| **B. Buyer confirmation required** | Quantity and amended PO | Merchandising | Written buyer decision | Buyer |
| B | Sample, artwork and bulk-production approval status | Merchandising | Written buyer decision | Buyer |
| B | Meaning of the 15 Dec milestone | Merchandising | Written definition | Buyer |
| B | Final inspection or acceptance requirements | Merchandising / QA | Buyer's written criteria | Buyer |
| **C. Management decision required** | Whether, when and what to disclose to the buyer | Merchandising Manager | This assessment and verified records | Authorised management |
| C | Any recovery measure, overtime or staffing change; any revised schedule or date; any commitment | Production / Planning | Validated data | Authorised management |
| C | QA disposition, and any concession request | QA | Garment-level data and the buyer's criteria | QA / management; buyer for any concession |
| **D. Monitor and update** | Re-issue this assessment when verified data arrives | Merchandising / Planning | Updated records | Merchandising Manager |
| D | Track later buyer correspondence | Merchandising | Correspondence log | Merchandising Manager |

No buyer response deadline is invented. No escalation is claimed to have occurred.

## F. Action and Closure Tracker

Requesting information or assigning an action does not close a risk. Closure requires the stated criterion.

| Action | Risk | Owner | Requested action | Required evidence | Closure criterion | Decision owner | Status |
|---|---|---|---|---|---|---|---|
| A01 | All | Merchandising | Escalate this assessment to the Merchandising Manager | n/a | Manager has reviewed and directed next steps | Merchandising Manager | Decision required |
| A02 | R01 | Merchandising | Request buyer quantity confirmation or amended PO | Written buyer response | Amended PO or written confirmation received | Buyer / Merchandising Manager | Decision required |
| A03 | R03, R04 | Merchandising / Sampling | Search for later correspondence; confirm status of the pre-production sample, conditions and bulk approval | Correspondence, written decisions | Written status documented | Buyer / Merchandising Manager | Open |
| A04 | R02 | Merchandising / Logistics | Request the buyer's definition of 15 Dec | Written definition | Definition on file | Buyer | Decision required |
| A05 | R05 | Sourcing / Fabric Store / QA | Verify fabric receipt, inspection, allocation, test status; request the supplier's date | Store, QA and supplier records | Verified records and a supplier-confirmed date | Sourcing Manager / QA | Awaiting evidence |
| A06 | R06 | Merchandising / Sourcing | Obtain the approved BOM and other material status | BOM; material report | Approved BOM and material status on file | Merchandising Manager | Awaiting evidence |
| A07 | R07 | Production / Planning | Provide current output, accepted pieces, remaining workload and capacity | Production and QA records | Data supplied and a schedule validated by authorised planners | Production Planning Manager | Awaiting evidence |
| A08 | R08 | QA | Complete the assessment: unique defective garments, classification, disposition | Garment-level data; buyer criteria | QA disposition documented | QA Manager; buyer for any concession | Awaiting evidence |
| A09 | R08 | Merchandising | Request the buyer's AQL and acceptance criteria | Written criteria | Criteria on file | Buyer | Decision required |
| A10 | R09 | Logistics / QA / Shipping | Report packing, final inspection, freight, documents and handover status | Booking and readiness records | Status documented | Logistics Manager | Awaiting evidence |
| A11 | R05 to R09 | Management | Decide whether any recovery option is to be evaluated | A05, A07, A10 outputs | Documented decision | Authorised management | Decision required |
| A12 | All | Merchandising / Planning | Re-issue this assessment with verified data | Updated records | Revised assessment issued | Merchandising Manager | Open |

## G. Draft Internal Management Escalation Email

*Draft only. Not sent.*

**To:** [Merchandising Manager]
**Cc:** [Production Planning Manager]; [QA Manager]; [Sourcing Manager]; [Logistics Manager]
**Subject:** Escalation: Delivery Risk Review, PO-2026-1045 / NSF-LG-225

Dear [Name],

Our 7 December review of NSF-LG-225 is attached. The target shipment date is 15 December 2026, but the milestone it refers to (ex-factory, FOB handover, vessel departure or destination arrival) is not confirmed.

**Confirmed discrepancies:**
- The PO declares 10,000 garments against a 9,000 size breakdown (difference 1,000), with no buyer confirmation in the records.
- Reported main fabric is 1,200 kg against a provisional 1,800 kg requirement (66.7% numerical coverage, 600 kg gap). The 1,800 kg is not an approved BOM figure.

**Historical findings:** at 3 December, reported sewing output was 1,800 against 2,000 planned (a 200-piece historical shortfall, not confirmed for 7 December). A 4 December inspection recorded 45 defect occurrences in 200 garments. This is not a count of defective garments, and no disposition is recorded.

**Missing records are not proven non-compliance.** Written final sample approval, written bulk-cutting approval, fabric receipt and testing, current output, packing, final inspection and freight status are not evidenced in the snapshot. They may exist elsewhere.

**Decisions and information requested:**
1. Direct teams to verify existing records and supply current status (actions A03 and A05 to A10).
2. Decide whether, when and what to raise with the buyer. A draft covering buyer-controlled questions only is attached.
3. Decide whether any recovery option should be evaluated.

I have not estimated any delay, and I have made no delivery or recovery commitment.

Regards,
[Name], Merchandising

## H. Draft Buyer Communication

*Draft for management approval. Not sent. It is limited to buyer-controlled questions. It does not disclose fabric, production, quality or capacity information, and it states no delay or guarantee. No response deadline is included because none has been agreed.*

**To:** [Buyer contact name], NorthStar Fashion Ltd.
**Cc:** [Merchandising Manager]
**Subject:** Confirmations Requested for Planning: Style NSF-LG-225 / PO-2026-1045

Dear [Buyer contact name],

We are reviewing our planning for the above order and would be grateful for your help with the following:

1. **Quantity:** the PO states 10,000 pieces, but the size breakdown totals 9,000. Please confirm the correct quantity and size breakdown, and issue an amended PO if needed.
2. **Approvals:** please confirm the current status of your sample, care-label artwork and written bulk-production approvals, including the pre-production sample we submitted on 21 November and the items from your 20 November comments.
3. **Shipment date:** please confirm what the 15 December 2026 date refers to (ex-factory, FOB handover, vessel departure or arrival at destination).
4. **Inspection:** please advise your final inspection and acceptance requirements for this order.

Your replies will help us plan accurately. Please let us know if a call would be easier.

Kind regards,
[Name], Merchandising Executive
Meridian Apparels Ltd., Bangladesh
[Phone] | [Email]

## I. Limitations and Required Human Decisions

**Limitations**
- This is a self-contained snapshot. It does not prove earlier sample approval, fabric release, cutting authorisation or quality acceptance.
- The absence of a record is not proof that an action never occurred.
- The 3 Dec and 4 Dec figures are historical. No current shortfall, completion forecast, delay, probability or monetary impact is stated.
- No supplier dates, approval dates, recovery durations, concessions or delivery commitments are invented.

**Human oversight**
- **Buyer decisions:** approvals, quantity, commercial changes, the milestone definition and any concession.
- **QA / management:** QA disposition and release.
- **Authorised management:** production recovery, overtime and staffing changes, disclosure to the buyer, any revised delivery date and any shipment commitment.
- **AI recommendations in this report are not operational instructions.** No email has been sent, and no buyer commitment has been made.

I can also prepare a one-page status dashboard for the management meeting, or a call script for the buyer follow-up.

## Evaluation and Improvements

Version 1 identified key delivery risks but contained ambiguous evidence classifications, unsupported operational assumptions and insufficient risk traceability. Version 2 introduced unique risk identifiers, prioritised risk assessments, structured escalation procedures, departmental responsibilities and evidence-based closure criteria. It also strengthened confidentiality and management approval controls. Version 2 was selected because it improves delivery risk visibility, reduces unsupported shipment forecasts and supports accountable management decisions without making unauthorised commercial commitments.

**Final Selected Version: Version 2**
