# P04 – Material Readiness Checker

## Version 1 – Original Prompt

Act as an experienced garment merchandising and material planning assistant working for Meridian Apparels Ltd., a fictional apparel manufacturer in Bangladesh.

Your task is to review the following material-status report and assess whether the required materials are ready to support the planned production schedule.

Please:
1. Review the required and available quantities for each material.
2. Calculate material shortages and identify which items are fully available.
3. Assess overall material readiness for production.
4. Identify materials that could delay cutting, sewing, finishing or packing.
5. Prepare a material readiness table showing required quantity, available quantity, shortage, readiness status and responsible department.
6. Recommend practical follow-up actions for the merchandising, sourcing, warehouse and production teams.
7. Summarise the main issues for the merchandising manager.

Use a professional and concise format. Clearly identify missing information and assumptions. Do not claim that materials have been approved or delivered unless the data confirms this.

SYNTHETIC MATERIAL-STATUS REPORT

Manufacturer: Meridian Apparels Ltd., Bangladesh
Buyer: NorthStar Fashion Ltd.
PO Number: PO-2026-1045
Style: NSF-LG-225
Product: Ladies' Cotton Leggings
Report Date: 23 November 2026
Planned Cutting Start: 25 November 2026
Declared Garment Quantity: 10,000 pieces
Size Breakdown Total: 9,000 pieces
Buyer Sample Approval: Pending

Material 1: Main Fabric
Required: 1,800 kg
Available: 1,200 kg
Outstanding: 600 kg
Testing Status: Pending
Expected Arrival of Balance: Not confirmed

Material 2: Waistband Elastic
Required: 10,000 pieces
Available: 8,000 pieces
Outstanding: 2,000 pieces
Expected Arrival: Not confirmed

Material 3: Sewing Thread
Required: 120 cones
Available: 120 cones
Expected Arrival: Not applicable

Material 4: Care Labels
Required: 10,000 pieces
Available: 10,000 pieces
Expected Arrival: Not applicable

Material 5: Size Labels
Required: 10,000 pieces
Available: 7,000 pieces
Outstanding: 3,000 pieces
Expected Arrival: Not confirmed

Material 6: Polybags
Required: 10,000 pieces
Available: 6,000 pieces
Outstanding: 4,000 pieces
Expected Arrival: Not confirmed

Material 7: Cartons
Required: 200 pieces
Available: 150 pieces
Outstanding: 50 pieces
Expected Arrival: Not confirmed

Important:
All material requirements are provisional planning estimates based on 10,000 garments. They have not been approved as final purchasing quantities. The buyer's declared quantity conflicts with the size breakdown. Fabric testing and buyer sample approval remain pending. No confirmed arrival dates are supplied for outstanding materials.

Generate a preliminary material readiness assessment and management recommendations.

## Version 1 – Claude Response

# Material Readiness Assessment: PO-2026-1045 / NSF-LG-225

*Preliminary planning aid dated 23 Nov 2026. It does not approve materials, purchasing quantities or the cutting start.*

## 1. Summary

**Materials are not ready to support the full order.** Only 2 of 7 items (thread and care labels) have their full provisional requirement on hand. The other five are short, none has a confirmed arrival date, and main fabric testing and buyer sample approval are both pending. The report does not say whether "Available" stock is in-house, inspected or allocated to this PO.

## 2. Assumptions and Basis

| # | Item | Type |
|---|---|---|
| 1 | All requirements are provisional and based on 10,000 garments, not approved purchasing quantities. | Supplied |
| 2 | Shortage = Required − Available. All reported "Outstanding" figures match my recalculation. | Derived |
| 3 | "Available" is read as the quantity the report lists. In-house receipt, inspection status and allocation to this PO are not stated. | Assumption, requires confirmation |
| 4 | Ratios in Section 4 assume the requirement scales linearly with garment count. Wastage allowances and BOM consumption were not supplied. | Assumption |
| 5 | The stages at risk (cutting, sewing, finishing, packing) follow normal garment practice, not the report. | Potential risk, requires verification |

## 3. Material Readiness Table

| # | Material | Required | Available | Shortage | % available | Readiness status | Stage at risk | Responsible |
|---|---|---|---|---|---|---|---|---|
| 1 | Main fabric | 1,800 kg | 1,200 kg | **600 kg** | 66.7% | **Not ready**: shortage, testing pending, balance arrival unconfirmed | Cutting (first), then all later stages | Merchandising / Sourcing / Fabric Store / QA |
| 2 | Waistband elastic | 10,000 pcs | 8,000 pcs | **2,000 pcs** | 80.0% | **Not ready**: partial | Sewing | Sourcing / Merchandising |
| 3 | Sewing thread | 120 cones | 120 cones | 0 | 100% | Quantity available (quality approval not stated) | Sewing | Store |
| 4 | Care labels | 10,000 pcs | 10,000 pcs | 0 | 100% | Quantity available (artwork/approval not stated) | Sewing / finishing | Store |
| 5 | Size labels | 10,000 pcs | 7,000 pcs | **3,000 pcs** | 70.0% | **Not ready**: partial | Sewing / finishing | Sourcing / Merchandising |
| 6 | Polybags | 10,000 pcs | 6,000 pcs | **4,000 pcs** | 60.0% | **Not ready**: partial | Packing | Sourcing / Packing |
| 7 | Cartons | 200 pcs | 150 pcs | **50 pcs** | 75.0% | **Not ready**: partial | Packing / shipment | Sourcing / Packing |

Overall: 2 fully available, 5 short, 0 with a confirmed arrival date.

## 4. Coverage and Quantity Sensitivity

**Garments the current stock can support** (derived, assuming consumption matches the planning basis):

| Material | Implied rate (10,000 basis) | Stock covers about |
|---|---|---|
| Main fabric | 0.18 kg per garment | **6,667 garments** |
| Waistband elastic | 1 per garment | 8,000 garments |
| Size labels | 1 per garment | 7,000 garments |
| Polybags | 1 per garment | 6,000 garments |
| Cartons | 50 garments per carton | 7,500 garments |

On this basis, **fabric** limits cutting to roughly 6,667 garments before any wastage allowance, and **polybags** limit packing to about 6,000.

**Illustrative effect of the 9,000 size total** (linear scaling only; the final BOM must come from confirmed consumption):

| Material | Scaled requirement | Available | Shortage / surplus |
|---|---|---|---|
| Main fabric | 1,620 kg | 1,200 kg | Short 420 kg |
| Waistband elastic | 9,000 | 8,000 | Short 1,000 |
| Sewing thread | 108 cones | 120 | Surplus 12 (consumption may not scale linearly) |
| Care labels | 9,000 | 10,000 | Surplus 1,000 |
| Size labels | 9,000 | 7,000 | Short 2,000 |
| Polybags | 9,000 | 6,000 | Short 3,000 |
| Cartons | 180 | 150 | Short 30 |

Even at 9,000, every item that is short at 10,000 stays short. Resolving the quantity discrepancy reduces the gaps but does not close them.

## 5. Items That Could Delay Production

| Stage | Material | Concern |
|---|---|---|
| **Cutting (planned 25 Nov)** | Main fabric | The 600 kg shortfall (or 420 kg at 9,000) has no arrival date, and testing is pending. It is unconfirmed whether the 1,200 kg has been inspected or released. Cutting the full order cannot be supported. |
| **Cutting** | Sample approval | Pending, which is a separate dependency from material quantity. |
| **Sewing** | Waistband elastic | 2,000 pcs short, arrival not confirmed. |
| **Sewing / finishing** | Size labels | 3,000 pcs short. Size-wise availability is not given. Because labels are size-specific, a shortage in one size could stop that size even where the total looks adequate. |
| **Packing** | Polybags, cartons | 4,000 and 50 pcs short. These are needed later. On the earlier baseline (no holidays applied), finishing and packing begins 10 Dec, which gives some time, but only if arrival dates are confirmed. |
| Not at risk on quantity | Thread, care labels | Fully available, subject to quality and approval status not being shown. |

## 6. Missing Information

- Arrival dates for all five outstanding items.
- Whether "Available" stock is received, inspected and allocated to this PO.
- Main fabric test status detail and expected result date.
- Wastage allowances and the BOM consumption basis.
- Size-wise split for size labels (and elastic if size-specific).
- Whether trims and labels are buyer-approved.
- Confirmed garment quantity (10,000 vs 9,000).
- Supplier names and order status for outstanding items.

## 7. Recommended Follow-up Actions

**Merchandising**
1. Get written confirmation from the buyer of the final quantity, then reissue the material requirement from the confirmed BOM. Do not place top-up orders on the provisional figures.
2. Obtain the sample approval date and agree with management whether any at-risk cutting is permitted.

**Sourcing**
3. Obtain confirmed arrival dates for the fabric balance, elastic and size labels first, then polybags and cartons.
4. Ask suppliers about partial deliveries, so a first lot can support a partial cutting or sewing start. Any order or purchase needs authorised approval.
5. Identify fallback sources for the items with no arrival date.

**Warehouse / Fabric Store**
6. Confirm the physical on-hand quantity, inspection status and allocation of the 1,200 kg of fabric and the other available items.
7. Confirm size-wise label stock.

**QA**
8. Confirm the fabric test timeline and requirements so that results can be linked to the cutting decision.

**Production Planning**
9. Review the 25 Nov cutting start against the fabric position, and replan if necessary. Evaluate a partial cutting plan only with verified capacity, line allocation and overlap rules, and with management approval.
10. Update the T&A with confirmed material dates.

## 8. Manager Summary

1. **Five of seven materials are short** and none has a confirmed arrival date.
2. **Main fabric is the critical item.** It is 600 kg short, testing is pending, and it limits cutting to about 6,667 garments on current stock.
3. **Quantity and sample approval are unresolved.** Requirements may fall by about 10% if 9,000 is confirmed, but shortages remain either way.
4. **Sewing and packing items are also exposed.** Elastic, size labels and polybags are all short.
5. **Decisions needed from authorised management:** whether to start cutting before approvals and full material availability, and who authorises any material purchases.

*Quantities are taken directly from the supplied report. Coverage and scaled figures are my calculations under the stated assumptions. This is not an approval of materials, purchases or the production start.*

## Version 2 – Improved Prompt

ROLE
You are an AI Material Readiness and Production Coordination Analyst supporting Meridian Apparels Ltd., a fictional garment manufacturer in Bangladesh.

Your responsibility is to analyse provisional material records, calculate quantity gaps, identify readiness risks and prepare recommendations for authorised human managers. You cannot approve material purchases, release stock, authorise cutting or confirm a production schedule.

OBJECTIVE
Evaluate the material readiness of purchase order PO-2026-1045 for style NSF-LG-225. Determine which materials meet their provisional quantity requirements, which have shortages and which have unresolved quality, allocation or delivery conditions.

TASK 1 — VALIDATE THE DATA
1. Extract all seven materials, their units, provisional requirements and reported available quantities.
2. Independently calculate shortage = MAX(required minus available, 0).
3. Calculate quantity coverage percentage = available / required × 100, rounded to one decimal place.
4. Preserve each material's original unit. Do not add kilograms, pieces and cones together.
5. Check whether the reported outstanding quantities agree with your calculations.
6. Identify the unresolved garment quantity discrepancy: 10,000 declared versus 9,000 in the size breakdown.

TASK 2 — SEPARATE QUANTITY COVERAGE FROM ACTUAL READINESS
For every material, distinguish:
A. Quantity coverage: fully covered or short against the provisional requirement.
B. Physical stock status: whether receipt and physical location are confirmed.
C. Quality and buyer approval: confirmed, pending or not supplied.
D. Allocation status: whether the available stock is reserved for this order.
E. Outstanding balance arrival date: confirmed or not supplied.

Important rules:
- The term "Available" is only a reported quantity. It does not prove that stock has been physically received, inspected, approved or allocated.
- A material with 100% reported quantity coverage must not automatically be labelled production-ready.
- If information is missing, state "Not confirmed" rather than inventing a status.
- Fabric testing and buyer sample approval are pending.

TASK 3 — ASSESS PRODUCTION DEPENDENCIES
1. Evaluate the implications for cutting, sewing, finishing and packing.
2. Prioritise risks based on their potential effect on the planned cutting start of 25 November 2026 and later production stages.
3. Identify main fabric availability and testing as immediate cutting concerns.
4. Identify elastic and labels as potential sewing/finishing concerns, and polybags and cartons as packing concerns.
5. Do not claim a specific delay duration because outstanding arrival dates are unknown.
6. Do not recommend releasing material or starting partial production as an authorised action.

TASK 4 — PREVENT UNSUPPORTED CALCULATIONS
1. Do not calculate how many garments current fabric or trim stocks can produce.
2. Do not recalculate material requirements for 9,000 garments.
3. Do not assume linear scaling, approved consumption rates, wastage allowances, carton ratios or size-wise availability.
4. Do not create revised purchase quantities or supplier delivery commitments.
5. Explain that the approved BOM and confirmed garment quantity are needed before material requirements can be finalised.

TASK 5 — RISK REGISTER AND ACTIONS
Prepare a risk register with:
- Material or issue
- Evidence from the supplied data
- Confirmed quantity gap
- Potential affected production stage
- Missing verification
- Priority (Critical, High or Medium)
- Responsible human department
- Recommended next action

Distinguish confirmed quantity shortages from potential operational risks.

TASK 6 — MANAGEMENT OVERSIGHT
Recommend verification by Merchandising, Sourcing, Warehouse, QA and Production Planning.
All material purchases, substitutions, quality releases and production-start decisions require approval from authorised human personnel.
Do not present any recommended action as already completed.

REQUIRED OUTPUT
A. Executive Readiness Summary
B. Material Quantity Validation Table
C. Physical, Quality and Allocation Status Assessment
D. Production-Stage Dependency Analysis
E. Risk Register and Prioritised Actions
F. Data Limitations and Human Approval Requirements

Keep the report professional, concise and evidence-based. Do not introduce external supplier lead times, stock records or unverified operational assumptions.

SYNTHETIC TEST DATA

Manufacturer: Meridian Apparels Ltd., Bangladesh
Buyer: NorthStar Fashion Ltd.
PO Number: PO-2026-1045
Style: NSF-LG-225
Product: Ladies' Cotton Leggings
Report Date: 23 November 2026
Planned Cutting Start: 25 November 2026
Declared Garment Quantity: 10,000 pieces
Size Breakdown Total: 9,000 pieces
Buyer Sample Approval: Pending

MATERIAL 1 — MAIN FABRIC
Provisional Requirement: 1,800 kg
Reported Available: 1,200 kg
Reported Outstanding: 600 kg
Testing Status: Pending
Balance Arrival Date: Not confirmed

MATERIAL 2 — WAISTBAND ELASTIC
Provisional Requirement: 10,000 pieces
Reported Available: 8,000 pieces
Reported Outstanding: 2,000 pieces
Balance Arrival Date: Not confirmed

MATERIAL 3 — SEWING THREAD
Provisional Requirement: 120 cones
Reported Available: 120 cones
Reported Outstanding: 0

MATERIAL 4 — CARE LABELS
Provisional Requirement: 10,000 pieces
Reported Available: 10,000 pieces
Reported Outstanding: 0

MATERIAL 5 — SIZE LABELS
Provisional Requirement: 10,000 pieces
Reported Available: 7,000 pieces
Reported Outstanding: 3,000 pieces
Balance Arrival Date: Not confirmed

MATERIAL 6 — POLYBAGS
Provisional Requirement: 10,000 pieces
Reported Available: 6,000 pieces
Reported Outstanding: 4,000 pieces
Balance Arrival Date: Not confirmed

MATERIAL 7 — CARTONS
Provisional Requirement: 200 pieces
Reported Available: 150 pieces
Reported Outstanding: 50 pieces
Balance Arrival Date: Not confirmed

ADDITIONAL CONDITIONS
- All requirements are provisional estimates based on the declared 10,000-garment order.
- The buyer's quantity discrepancy remains unresolved.
- No approved final BOM or consumption/wastage data is supplied.
- Except for the pending fabric test, material inspection and buyer approval statuses are not supplied.
- Physical receipt and allocation of reported available stock are not confirmed.
- No confirmed arrival dates are available for outstanding balances.
- No permission for partial production or material release is supplied.

Generate the preliminary material readiness assessment now.

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

Version 1 correctly identified material shortages but introduced unsupported assumptions about production coverage and material requirements based on unconfirmed order quantities. Version 2 improved reliability by distinguishing reported stock, physical availability, quality acceptance and confirmed material allocation. It also restricted unsupported calculations and highlighted missing information. Version 2 was selected because it provides a more accurate material readiness assessment, reduces production planning risks and supports informed decision-making while maintaining human oversight.

**Final Selected Version: Version 2**
