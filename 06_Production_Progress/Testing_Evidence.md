# P06 – Production Progress Analyst

## Version 1 – Original Prompt

Act as an experienced garment production analyst working for Meridian Apparels Ltd., a fictional apparel manufacturer in Bangladesh.

Your task is to analyse daily sewing production performance for style NSF-LG-225 and prepare a management report.

Please:
1. Compare daily production targets against actual output.
2. Calculate daily production variances in pieces and percentages.
3. Calculate cumulative planned output, cumulative actual output and overall achievement percentage.
4. Identify days with below-target and above-target performance.
5. Analyse the possible operational reasons for performance differences.
6. Assess whether the production trend creates a risk for completing the planned sewing work.
7. Recommend practical corrective actions for the production, maintenance and planning teams.
8. Prepare a concise management summary with key performance indicators.

Clearly distinguish observed performance from possible explanations. Do not invent machine downtime hours, worker numbers, defect rates, capacity or revised delivery dates.

SYNTHETIC PRODUCTION DATA

Manufacturer: Meridian Apparels Ltd., Bangladesh
Buyer: NorthStar Fashion Ltd.
Style: NSF-LG-225
Product: Ladies' Cotton Leggings
Report Date: 3 December 2026
Production Stage: Sewing
Daily Target: 500 pieces

30 November 2026
Planned Output: 500 pieces
Actual Output: 420 pieces
Supervisor Observation: Operator absenteeism reported. Number of absent operators not provided.

1 December 2026
Planned Output: 500 pieces
Actual Output: 480 pieces
Supervisor Observation: No operational issue recorded.

2 December 2026
Planned Output: 500 pieces
Actual Output: 390 pieces
Supervisor Observation: Machine downtime reported. Duration and affected machines not documented.

3 December 2026
Planned Output: 500 pieces
Actual Output: 510 pieces
Supervisor Observation: An additional operator was assigned. Actual output exceeded target.

IMPORTANT CONTEXT
This is a separate hypothetical production-progress scenario for testing the AI prompt. It does not establish that buyer sample approval, material release or cutting authorisation from earlier scenarios was received.

No validated final order quantity, remaining sewing workload, revised production schedule, line capacity, efficiency rate, defect count, rework quantity or confirmed shipment forecast is supplied.

Prepare the daily sewing production analysis and management recommendations.

## Version 1 – Claude Response

# Sewing Production Performance Report: NSF-LG-225

*Report date: Thu 3 Dec 2026. Analysis of the supplied daily records only. This is a separate hypothetical scenario and does not establish buyer sample approval, material release or cutting authorisation from earlier scenarios.*

## 1. Management Summary

| KPI | Value |
|---|---|
| Days reported | 4 (30 Nov to 3 Dec) |
| Cumulative planned output | 2,000 pcs |
| Cumulative actual output | 1,800 pcs |
| Cumulative variance | **-200 pcs** |
| Overall achievement | **90.0%** |
| Days below target | 3 (30 Nov, 1 Dec, 2 Dec) |
| Days above target | 1 (3 Dec) |
| Best day | 3 Dec: 510 pcs (102.0%) |
| Weakest day | 2 Dec: 390 pcs (78.0%) |

- Output is 200 pcs behind plan, equal to 0.4 of a target day (200 ÷ 500).
- The only day above target is the latest one, after an additional operator was assigned. One day of data is not enough to call it a trend.
- Whether the sewing work will finish on time **cannot be determined**, because the total sewing quantity, remaining workload and schedule are not supplied.

## 2. Daily Variance Analysis

Variance = Actual − Planned. Variance % = Variance ÷ Planned × 100. Achievement % = Actual ÷ Planned × 100.

| Date | Planned | Actual | Variance (pcs) | Variance % | Achievement % | Result |
|---|---|---|---|---|---|---|
| Mon 30 Nov | 500 | 420 | -80 | -16.0% | 84.0% | Below target |
| Tue 1 Dec | 500 | 480 | -20 | -4.0% | 96.0% | Below target |
| Wed 2 Dec | 500 | 390 | -110 | -22.0% | 78.0% | Below target |
| Thu 3 Dec | 500 | 510 | +10 | +2.0% | 102.0% | Above target |
| **Total** | **2,000** | **1,800** | **-200** | **-10.0%** | **90.0%** | Below target |

## 3. Cumulative Performance

| Date | Cumulative planned | Cumulative actual | Cumulative variance | Cumulative achievement |
|---|---|---|---|---|
| 30 Nov | 500 | 420 | -80 | 84.0% |
| 1 Dec | 1,000 | 900 | -100 | 90.0% |
| 2 Dec | 1,500 | 1,290 | -210 | 86.0% |
| 3 Dec | 2,000 | 1,800 | -200 | 90.0% |

The cumulative gap peaked at -210 pcs on 2 Dec. The 3 Dec result recovered only 10 pcs of it.

## 4. Observed Performance vs Possible Explanations

**Observed (from supervisor records)**

| Date | Supervisor observation | Documentation gap |
|---|---|---|
| 30 Nov | Operator absenteeism reported | Number of absent operators not provided |
| 1 Dec | No operational issue recorded | None recorded, yet output was 4.0% under target |
| 2 Dec | Machine downtime reported | Duration and affected machines not documented |
| 3 Dec | Additional operator assigned; output exceeded target | Operator's skill, operation and line position not provided |

**Possible explanations (hypotheses, require verification)**

| Date | Possible explanation | Verification needed |
|---|---|---|
| 30 Nov | Absenteeism may have reduced available labour on the line. The size of the effect cannot be quantified. | Attendance records, operation-wise manning |
| 1 Dec | The shortfall is unexplained. It may reflect normal variation, an unrecorded cause or a target that is slightly above routine capability. | Supervisor review, line data |
| 2 Dec | Machine stoppage may have reduced output. This was the largest shortfall (-110 pcs). The lost time is unknown. | Maintenance logs: duration, machines, cause |
| 3 Dec | The extra operator may have contributed to the above-target result. Cause and effect is not proven, since other factors were not recorded. | Operation-wise output, manning comparison |

No downtime hours, operator numbers, defect rates, rework or capacity are stated or inferred here.

## 5. Risk Assessment

| Risk | Basis | Status |
|---|---|---|
| Cumulative shortfall of 200 pcs | Calculated | **Confirmed** |
| Recurrence of absenteeism or machine downtime | Both recorded on separate days within 4 days | Potential risk, requires verification |
| Shortfall may not be recovered | Only 1 of 4 days exceeded target, by 10 pcs | Potential risk, requires verification |
| Effect on the sewing completion date | Total sewing quantity, remaining workload and schedule not supplied | **Cannot be assessed** |
| Quality, defects, rework | Not supplied | Unknown |
| Whether the 3 Dec level is sustainable | One day only; extra operator's availability not stated | Unknown |

If the 500 pcs/day target stays unchanged, the 200 pcs gap has to be made up from future output or by changing the plan. Whether this is feasible depends on capacity and remaining workload, which are not supplied. No revised completion date or delivery forecast is stated.

## 6. Recommended Corrective Actions

*These are recommendations for authorised personnel. None is recorded as completed.*

| Team | Action | Priority |
|---|---|---|
| **Production** | Record the number of absent operators and affected operations daily. Review how absences are covered. | High |
| **Production** | Review whether the extra operator assigned on 3 Dec can continue, and in which operation, with the supervisor and Production Manager. | High |
| **Production** | Investigate the unexplained 1 Dec shortfall (-20 pcs) with the line supervisor. | Medium |
| **Maintenance** | Document the 2 Dec downtime: machines, duration and cause. Review whether preventive checks are needed on the affected machines. | High |
| **Production Planning** | Obtain the total sewing quantity and remaining workload, then reassess the 200 pcs gap against the plan. Do not issue a revised schedule or delivery date until these are validated. | High |
| **Production Planning** | Decide whether the 200 pcs gap is to be recovered, and by what means. Any overtime or extra resources need authorised approval. | High |
| **Quality / Production** | Provide defect and rework data to confirm that output figures reflect usable pieces. | Medium |
| **Management** | Continue daily target-vs-actual tracking and review again once more days are recorded. | Medium |

## 7. Data Limitations

- Final order quantity, remaining sewing workload and the revised schedule are not supplied.
- Line capacity, efficiency, worker numbers, machine counts and downtime hours are not supplied.
- Defect and rework counts are not supplied, so it is unknown whether actual output means good pieces.
- The causes in Section 4 are hypotheses. They are not established.
- Four days of data are too few to establish a trend.

I can also prepare a daily tracking template with automatic cumulative variance, or a short note for the production meeting.

## Version 2 – Improved Prompt

ROLE
You are an AI Production Performance and Operations Analyst supporting the Production Planning and Merchandising departments of Meridian Apparels Ltd., a fictional apparel manufacturer in Bangladesh.

Your role is to validate sewing production data, analyse performance variance, identify operational risks and recommend evidence-based follow-up actions. You cannot approve overtime, change production targets, authorise resources, release production or commit to delivery dates.

OBJECTIVE
Assess four days of reported sewing output for style NSF-LG-225, distinguish confirmed performance results from possible causes, and identify the information management needs before deciding on recovery actions.

TASK 1 — DATA VALIDATION AND DAILY PERFORMANCE
For each of the four reporting dates:
1. Extract planned and actual output.
2. Calculate variance (pieces) = Actual − Planned.
3. Calculate variance percentage = (Actual − Planned) / Planned × 100.
4. Calculate achievement percentage = Actual / Planned × 100.
5. Classify performance as Below Target, On Target or Above Target.
6. Verify that all figures reconcile with the cumulative totals.

Use one decimal place for percentages. Do not invent missing production records.

TASK 2 — CUMULATIVE ANALYSIS
Calculate and present:
- Cumulative planned output for each day.
- Cumulative actual output for each day.
- Cumulative variance for each day.
- Cumulative achievement percentage for each day.
- Total reported output and cumulative shortfall.
- Number of days below, on and above target.
- Highest and lowest daily achievement.

Distinguish daily improvement from a sustained performance trend. Four observations are insufficient to establish a reliable trend.

TASK 3 — REPORTED OUTPUT VERSUS ACCEPTED OUTPUT
Important:
- The supplied actual output is reported sewing production, not verified accepted good-piece output.
- Defect counts, rework, rejection and quality acceptance data are unavailable.
- Do not claim that all 1,800 reported pieces are good pieces.
- Do not calculate yield, first-pass quality, defect rate or accepted output without supporting records.
- Explain what additional quality data is required.

TASK 4 — OBSERVATIONS AND CAUSAL UNCERTAINTY
Create two separate sections:
A. Confirmed observations from the supervisor records.
B. Possible explanations requiring verification.

Specific controls:
- Operator absenteeism was reported on 30 November, but its numerical effect is unknown.
- No operational issue was recorded on 1 December; this does not prove that no issue occurred.
- Machine downtime was reported on 2 December, but duration, affected machines and lost production are unknown.
- An additional operator was assigned on 3 December, but the relationship between staffing and output is not proven.
- Do not invent operator counts, downtime hours, line efficiency, productivity rates or machine capacity.
- Do not present correlation as proven causation.

TASK 5 — RECOVERY AND SCHEDULE RISK
Assess the cumulative 200-piece shortfall.

Do not:
- Convert the 200-piece shortfall into an assumed recovery time.
- Treat the 500-piece daily target as verified spare capacity.
- Predict when the shortfall will be recovered.
- Forecast sewing completion or shipment dates.
- Assume overtime, additional operators or production-line changes are available or approved.
- Assume the final garment quantity or remaining workload.

Explain the information required for a defensible recovery plan, including:
- Confirmed remaining sewing workload.
- Validated production schedule.
- Available capacity and staffing.
- Quality-accepted output.
- Approved resource or overtime options.

TASK 6 — OPERATIONAL RISK REGISTER
Prepare a risk register containing:
- Risk or performance issue.
- Supporting evidence.
- Classification: Confirmed / Potential / Unknown.
- Operational consequence.
- Missing verification.
- Priority: Critical / High / Medium.
- Responsible department.
- Recommended action.

Distinguish the confirmed 200-piece performance shortfall from unverified risks to the final completion date.

TASK 7 — HUMAN APPROVAL AND BUSINESS CONTROLS
- Production, Maintenance, QA and Planning may investigate and recommend actions.
- Any overtime, staffing change, revised target or revised production schedule requires approval from authorised human management.
- Do not present proposed actions as already implemented.
- The output is a decision-support report, not an operational authorisation.

TASK 8 — SCENARIO INTEGRITY
This is a separate hypothetical production-progress test. It does not demonstrate that buyer sample approval, fabric testing, material release or cutting authorisation from previous scenarios was completed.

Do not merge this dataset with earlier scenario records to claim production-release compliance.

REQUIRED OUTPUT
A. Executive Performance Summary
B. Daily Production Variance Table
C. Cumulative Performance Table
D. Reported Output and Quality Limitations
E. Supervisor Observations vs Possible Causes
F. Recovery Feasibility and Schedule Assessment
G. Operational Risk Register
H. Prioritised Departmental Action Plan
I. Human Approval Requirements and Data Limitations

Use concise, professional management language. Show calculations clearly and distinguish facts, calculations, hypotheses and missing evidence.

SYNTHETIC TEST DATA

Manufacturer: Meridian Apparels Ltd., Bangladesh
Buyer: NorthStar Fashion Ltd.
Style: NSF-LG-225
Product: Ladies' Cotton Leggings
Report Date: 3 December 2026
Production Stage: Sewing
Daily Target: 500 pieces

DAY 1 — 30 NOVEMBER 2026
Planned Output: 500 pieces
Reported Actual Output: 420 pieces
Supervisor Observation: Operator absenteeism reported.
Number of absent operators: Not supplied.

DAY 2 — 1 DECEMBER 2026
Planned Output: 500 pieces
Reported Actual Output: 480 pieces
Supervisor Observation: No operational issue recorded.

DAY 3 — 2 DECEMBER 2026
Planned Output: 500 pieces
Reported Actual Output: 390 pieces
Supervisor Observation: Machine downtime reported.
Downtime duration: Not supplied.
Affected machines: Not supplied.

DAY 4 — 3 DECEMBER 2026
Planned Output: 500 pieces
Reported Actual Output: 510 pieces
Supervisor Observation: One additional operator was assigned.
Operator's role and continued availability: Not supplied.

ADDITIONAL CONDITIONS
- Reported output may include pieces requiring rework or rejection.
- Accepted good-piece quantities are not supplied.
- Final approved order quantity is not supplied.
- Remaining sewing workload is not supplied.
- Validated revised production schedule is not supplied.
- Available line capacity, machine count and line efficiency are not supplied.
- Overtime approval and extra staffing availability are not supplied.
- No confirmed completion or shipment forecast is available.
- This is an independent hypothetical test scenario and not evidence of earlier buyer or factory approvals.

Generate the evidence-based sewing production performance and recovery assessment now.

## Version 2 – Claude Response

# Sewing Production Performance and Recovery Assessment: NSF-LG-225

*Report date: Thu 3 Dec 2026. This is a decision-support report, not an operational authorisation. This is an independent hypothetical scenario and does not show that buyer sample approval, fabric testing, material release or cutting authorisation from earlier scenarios was completed.*

**Correction to my earlier draft.** It broke several of your controls:
- It converted the shortfall into "0.4 of a target day", which is a recovery-time equivalent.
- It treated reported output as if it were usable output, without stating clearly that accepted good pieces are unknown.
- It did not explicitly reconcile daily figures to cumulative totals.
- It did not state the "On Target" classification.

This version corrects these points.

## A. Executive Performance Summary

| KPI | Value | Type |
|---|---|---|
| Days reported | 4 (30 Nov to 3 Dec) | Supplied |
| Total planned | 2,000 pcs | Calculated |
| Total **reported** output | 1,800 pcs | Calculated from supplied figures |
| Cumulative shortfall | **200 pcs** | Calculated |
| Overall achievement | **90.0%** | Calculated |
| Days Below / On / Above target | 3 / 0 / 1 | Calculated |
| Highest daily achievement | 102.0% (3 Dec) | Calculated |
| Lowest daily achievement | 78.0% (2 Dec) | Calculated |

- The confirmed finding is a 200-piece shortfall in *reported* output. Accepted good-piece output is unknown.
- 3 Dec is the only day above target. One day of improvement is not a sustained trend.
- Recovery and completion cannot be assessed, because the workload, schedule and capacity are not supplied.

## B. Daily Production Variance Table

Variance = Actual − Planned. Variance % = Variance ÷ Planned × 100. Achievement % = Actual ÷ Planned × 100.

| Date | Planned | Reported actual | Variance (pcs) | Variance % | Achievement % | Classification |
|---|---|---|---|---|---|---|
| Mon 30 Nov | 500 | 420 | -80 | -16.0% | 84.0% | Below Target |
| Tue 1 Dec | 500 | 480 | -20 | -4.0% | 96.0% | Below Target |
| Wed 2 Dec | 500 | 390 | -110 | -22.0% | 78.0% | Below Target |
| Thu 3 Dec | 500 | 510 | +10 | +2.0% | 102.0% | Above Target |
| **Total** | **2,000** | **1,800** | **-200** | **-10.0%** | **90.0%** | Below Target |

No day met the target exactly, so there are no "On Target" days.

## C. Cumulative Performance Table

| Date | Cum. planned | Cum. actual | Cum. variance | Cum. achievement |
|---|---|---|---|---|
| 30 Nov | 500 | 420 | -80 | 84.0% |
| 1 Dec | 1,000 | 900 | -100 | 90.0% |
| 2 Dec | 1,500 | 1,290 | -210 | 86.0% |
| 3 Dec | 2,000 | 1,800 | -200 | 90.0% |

**Reconciliation checks**
- Planned: 4 × 500 = 2,000. ✔
- Actual: 420 + 480 + 390 + 510 = 1,800. ✔
- Variance: (-80) + (-20) + (-110) + (+10) = -200 = 1,800 − 2,000. ✔
- Cumulative actual on 3 Dec (1,800) equals the sum of the daily figures. ✔

**Daily improvement vs sustained trend.** Output rose from 390 on 2 Dec to 510 on 3 Dec (+120 pcs day on day). The cumulative gap narrowed from -210 to -200. Four observations, with one above-target day, are not enough to establish a reliable trend.

## D. Reported Output and Quality Limitations

- The figures are **reported sewing output**, not verified accepted good-piece output.
- Reported output may include pieces needing rework or rejection (stated in the additional conditions).
- I have not calculated yield, first-pass quality, defect rate or accepted output, and I do not claim that all 1,800 pieces are good pieces.

**Data needed:**
- Daily defect, rework and rejection counts, by operation if available.
- A definition of what counts as "output" (sewn, inline-passed or end-of-line passed).
- QA-accepted quantity per day.
- Any pieces re-presented after rework, so they are not double-counted.

## E. Supervisor Observations vs Possible Causes

### A. Confirmed observations (supervisor records)

| Date | Record | Not supplied |
|---|---|---|
| 30 Nov | Operator absenteeism reported | Number of absent operators |
| 1 Dec | No operational issue recorded | n/a |
| 2 Dec | Machine downtime reported | Duration, affected machines, lost production |
| 3 Dec | One additional operator assigned | Operator's role and continued availability |

### B. Possible explanations (require verification)

| Date | Possibility | Limits |
|---|---|---|
| 30 Nov | Absence may have reduced labour on the line. | The numerical effect is unknown. |
| 1 Dec | The 20-piece shortfall has no recorded cause. | "No issue recorded" does not prove none occurred. |
| 2 Dec | Downtime may have contributed to the largest shortfall (-110 pcs). | Lost time and machines are unknown. |
| 3 Dec | The extra operator may have contributed to the above-target output. | A relationship between staffing and output is **not proven**. Other factors were not recorded. |

These are hypotheses. Correlation in timing is not causation, and no operator counts, downtime hours, efficiency or capacity are stated or inferred.

## F. Recovery Feasibility and Schedule Assessment

**Confirmed:** reported output is 200 pcs below plan over the four days.

**Not assessed.** I have not converted the 200 pcs into a recovery time, treated the 500 pcs/day target as spare capacity, predicted when the shortfall might be recovered, or forecast sewing completion or shipment. I have assumed no overtime, extra operators or line changes, and no final quantity or remaining workload.

**Information needed for a defensible recovery plan**

| Requirement | Status |
|---|---|
| Confirmed remaining sewing workload | Not supplied |
| Validated production schedule | Not supplied |
| Available capacity and staffing (line, machines, efficiency) | Not supplied |
| Quality-accepted output (to correct the shortfall for rework and rejects) | Not supplied |
| Approved resource or overtime options | Not supplied |

Until these exist, the effect of the shortfall on the final completion date is **unknown**.

## G. Operational Risk Register

| # | Risk / issue | Evidence | Class. | Consequence | Missing verification | Priority | Owner | Recommended action |
|---|---|---|---|---|---|---|---|---|
| 1 | 200-pcs cumulative shortfall in reported output | Section C | **Confirmed** | Output is behind plan | Accepted-quantity impact | **High** | Production Planning | Track daily; reassess once workload and schedule are validated |
| 2 | Effect on sewing completion / shipment | No workload or schedule | **Unknown** | Cannot be stated | Workload, schedule, capacity | **Critical** | Production Planning / Merchandising | Obtain the data in Section F before any recovery decision |
| 3 | Reported output may include rework or rejects | Additional conditions | **Potential** | The true shortfall may be larger or smaller | Defect and rework counts | **High** | QA | Provide daily accepted-quantity data |
| 4 | Absenteeism recurrence | Reported 30 Nov | **Potential** | Reduced labour availability | Absent numbers, operations affected | **High** | Production / HR | Record attendance and cover by operation |
| 5 | Machine downtime recurrence | Reported 2 Dec | **Potential** | Lost output | Duration, machines, cause | **High** | Maintenance | Document the event and review the machines |
| 6 | Unexplained 1 Dec shortfall | -20 pcs, no issue recorded | **Unknown** | Unknown | Cause | Medium | Production | Supervisor review |
| 7 | 3 Dec level not shown to be sustainable | One day; operator's availability not stated | **Unknown** | The shortfall may persist | Staffing continuity, operation | **High** | Production | Confirm the operator's role and availability |
| 8 | Overtime or extra staffing not confirmed | Not supplied | **Unknown** | Options may not exist | Approvals and availability | Medium | Management | Authorised decision only |

## H. Prioritised Departmental Action Plan

*Recommendations only. None is recorded as completed.*

| Priority | Department | Action |
|---|---|---|
| Critical | Production Planning / Merchandising | Confirm the final approved quantity, remaining sewing workload and validated schedule |
| High | QA | Supply daily defect, rework, rejection and accepted-piece data |
| High | Maintenance | Record 2 Dec downtime: duration, machines, cause and lost production if measurable |
| High | Production | Record absent operators by operation, and the role and continued availability of the additional operator |
| High | Production Planning | Supply line capacity, machine count and efficiency data for any recovery analysis |
| Medium | Production | Investigate the 1 Dec shortfall with the line supervisor |
| Medium | Management | Continue daily target-vs-actual tracking, and review when more data is available |

## I. Human Approval Requirements and Data Limitations

**Approval required from authorised management before any of the following:**
- Overtime.
- Staffing changes.
- Revised targets.
- A revised production schedule.
- Any completion or shipment commitment.

**Data limitations**
- Reported output only, with no accepted-quantity data.
- No final quantity, remaining workload, validated schedule, capacity, machine count or efficiency.
- No overtime or extra-staffing approvals.
- Four days of data, so no reliable trend.
- Causes are hypotheses.
- No earlier scenario approvals are carried into this report.

I can also prepare a daily tracking template that shows reported and accepted output side by side.

## Evaluation and Improvements

Version 1 correctly calculated production performance and identified output shortfalls but introduced potentially misleading recovery estimates and insufficient operational approval controls. Version 2 improved calculation transparency, distinguished reported production from quality-accepted output and restricted unsupported recovery and completion forecasts. Version 2 was selected because it provides more reliable production performance analysis, reduces misleading planning assumptions and supports evidence-based management decisions while maintaining human oversight.

**Final Selected Version: Version 2**
