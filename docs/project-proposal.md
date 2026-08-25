# Project proposal: offering patient-controlled sedation for subcutaneous venous port implantation

**Type:** small quality improvement project (implementation, not a new trial)  
**Intended setting:** a Swedish university-hospital anaesthesia service that implants subcutaneous venous ports (SVPs), specifically Perioperative Medicine and Intensive Care (PMV), Karolinska University Hospital, unless a different site is agreed.  
**Clinical specification:** propofol–alfentanil PCS as an adjunct to local anaesthesia, copied from PACSPI 2.[1]  
**Reporting standard if we later write this up:** SQUIRE 2.0.[2]  
**Improvement method:** Model for Improvement and sequential PDSA cycles.[3]

This document is a sketch. Local numbers, list structure, and current sedation practice must be filled in during the baseline audit ([issue #1](https://github.com/martingerdin/patient-controlled-sedation/issues/1)).

## 1. Problem

SVP implantation is common, short, and usually done under LA with or without clinician-controlled analgosedation. Two problems sit side by side:

1. **Under-treatment of a minority.** About one in four patients report clinically important pain under LA alone in Swedish observational data, and PACSPI 2 still found NRS ≥ 4 in 22% even in a high-volume anaesthetic service.[1,4]
2. **Over-treatment of a majority.** PACSPI 2 showed that adding PCS does *not* reduce pain or raise already-high satisfaction. Routine sedation therefore gives drug exposure, monitoring load, and a small respiratory risk to patients who would have done well with LA.[1]

Meanwhile, patients differ sharply in whether they want sedation at all. In PACSPI 1, many declined because they judged the procedure minor; in PACSPI 2, many declined because they wanted the department’s usual sedation.[1,5] Current local pathways rarely make that choice explicit, documented, and technically supported.

**Local problem (to confirm):** we do not yet have a reliable, protocolised way to offer PCS to those who want it, with PACSPI-level monitoring, while leaving LA alone as a first-class alternative.

## 2. Rationale

The literature review in `docs/literature-review.md` supports three claims:

- PCS with propofol is a known, generally safe technique for short procedures, with fewer rescue interventions than clinician-controlled propofol in pooled data.[6]
- For *this* operation, PACSPI 2 is definitive on pain: do not implement PCS to lower NRS scores.[1]
- PACSPI 2 still supports PCS as an *option*: better operating conditions (96% vs 82% “perfect”), far less unplanned rescue sedation (0.6% vs 8.9%), similar list times, and a safety profile that is acceptable only in an anaesthetic environment.[1]

The change theory is simple. If eligible patients are offered an honest choice, those who want control and anxiolysis will use the pump, operators will have calmer fields, and we will avoid both forced sedation and last-minute rescue. Safety is protected by copying PACSPI staffing and monitoring rather than inventing a lighter model.

This is QI, not another RCT. We are implementing a published, licensed-drug technique inside its evidence envelope and studying whether *our* process can deliver it reliably.

## 3. Aims

### 3.1 Primary aim

Within six months of the first clinical PDSA cycle, **≥ 80% of eligible adult patients** scheduled for SVP implantation on participating lists will have a **documented shared decision** between LA alone and LA + PCS.

### 3.2 Secondary aims

- Among patients who choose PCS, keep **hypoxia (SpO₂ < 90%) or airway obstruction requiring intervention ≤ 3%**, with no mask ventilation or conversion to general anaesthesia that the team judges attributable to PCS.
- Reduce **unplanned rescue sedation** compared with the baseline rate on the same lists.
- Maintain **median procedure time and recovery observation time** within 5 minutes of baseline.
- Achieve **protocol fidelity ≥ 90%** (correct pump programme, dedicated monitor, oxygen with capnography, only the patient presses the button).

Pain NRS will be recorded for learning, not as a success criterion.

## 4. Scope

**In scope**

- Adult patients (≥ 18 years) booked for primary or replacement SVP implantation on designated anaesthesia lists.
- Choice of LA alone vs LA + propofol–alfentanil PCS.
- Staff training, SOP, patient information, and a small prospective QI dataset.

**Out of scope**

- Children.
- Planned general anaesthesia.
- Changing the implantation technique (vein, ultrasound, catheter type).
- A new randomised trial, off-label research, or Läkemedelsverket CTA.
- PCS delivered without anaesthesia-competent monitoring.

**Exclusion from the PCS option** (aligned with PACSPI): inability to operate the handset; inability to communicate sufficiently for consent and button use; non-fasting; no peripheral venous access; pregnancy; anaesthesiologist judgement that sedation is contraindicated.

## 5. Intervention

### 5.1 Clinical technique (PACSPI 2)

Copy the published recipe unless local pharmacy or devices force a documented equivalent.[1]

| Element | Specification |
| --- | --- |
| Pump | Patient-controlled syringe pump with a handset (PACSPI used Syramed μSP6000, Arcomed) |
| Syringe | Propofol 36 mL (10 mg/mL) + alfentanil 4 mL (0.5 mg/mL) |
| Bolus | 0.5 mL = propofol 4.5 mg + alfentanil 25 µg over 10 s |
| Lockout | None; maximum six boluses/min (27 mg propofol + 0.15 mg alfentanil/min) |
| Who presses | The patient only |
| When | From connection of the pump, before skin antisepsis |
| LA | Operator’s usual infiltration (PACSPI: mepivacaine ± adrenaline ± bicarbonate) |
| Monitoring | Dedicated nurse anaesthetist; ECG, NIBP, SpO₂, respiratory rate, capnography |
| Oxygen | 2 L/min via nasal cannula with capnography from the start |
| Sedation score | OAA/S at predefined steps (antisepsis, LA injection, tunnelling, drape off) |
| Setting | Operating room or equivalent anaesthetic environment |

### 5.2 The actual QI change

The drug regimen is not the innovation. The innovation is the **care process**:

1. Pre-procedure information that PCS is optional, does not shorten pain scores on average, and exists for comfort and control.
2. A documented choice (LA vs LA + PCS).
3. Standardised pump set-up and monitoring if PCS is chosen.
4. Standardised rescue and discharge rules.
5. Feedback of process and safety data to the team.

## 6. Method

### 6.1 Model for Improvement

Three questions, then PDSA:[3]

1. **What are we trying to accomplish?** Reliable, documented choice, with PACSPI-level safety.
2. **How will we know that a change is an improvement?** See measures below.
3. **What change can we make?** Decision aid + SOP + training + PCS kit on selected lists.

### 6.2 PDSA sequence

| Cycle | Scale | Question |
| --- | --- | --- |
| 0 | Desk | Baseline audit of current sedation, rescue, times, and documentation |
| 1 | Simulation | Can the team set up the pump, teach the handset, and run the safety checklist without a patient? |
| 2 | 5–10 patients, volunteer operators | Does the SOP survive a real list? What breaks? |
| 3 | One to two lists per week | Can we hit the 80% documented-choice target without slowing the list? |
| 4 | All eligible lists in the participating unit | Is the process stable enough to write into the standing SOP? |

Each cycle has a prediction, a small data collection plan, and an explicit decide-to-adopt / adapt / abandon step.

### 6.3 Measures

| Type | Measure | Source |
| --- | --- | --- |
| Outcome | Documented shared decision (%) | Booking / anaesthetic record |
| Outcome | Patient-reported importance of control, anxiety, max pain, satisfaction (0–10) | Short postoperative form |
| Outcome | Operator conditions (PACSPI 4-point scale) | Operator |
| Process | Eligible patients offered PCS (%) | Checklist |
| Process | Pump programme verified (%) | Checklist |
| Process | Training / competency signed off (%) | Training log |
| Balancing | Procedure time, recovery time | Existing timestamps |
| Balancing | Rescue sedation | Record |
| Balancing | Bradypnoea, hypoxia, chin lift, mask ventilation | Record |
| Balancing | Drug cost per case (propofol + alfentanil + disposables) | Pharmacy |

Use a simple run chart of weekly documented-choice rate and a safety tally after every PCS case. No sample-size calculation: this is sequential learning, not a test of superiority.

A one-page case report form is enough. If the department already uses a structured anaesthetic record, add a PCS tick-box set rather than a parallel database.

## 7. Team and stakeholders

Minimum team:

- Anaesthesiologist lead (clinical and QI)
- Nurse anaesthetist lead (pump, monitoring, patient teaching)
- Operating-list coordinator
- Pharmacy (admixture, labelling, double-check)
- Medical technician / device lead (pump library)
- Quality / patient-safety representative
- Optional: oncology / access-nurse representative for the patient information

Patients are stakeholders, not only subjects. The decision aid should be piloted with a handful of patients and revised before PDSA 3.

## 8. Ethics, governance, and data

This is intended as **verksamhetsutveckling / quality improvement** using licensed medicines within their indications, not a clinical trial.

Still required, locally:

- Departmental and, if applicable, hospital QI registration.
- Advice on whether the Swedish Ethical Review Authority must be asked *if* a generalisable report is planned. PACSPI 2’s editorial asked for more experience and safety data; a SQUIRE report may cross the line into research. Decide this *before* PDSA 2, not after.
- GDPR / Patientdatalagen: minimum data, access list, retention, no extra identifiers.
- Device conformity and a local pump-programme lock so settings cannot drift.
- Incident reporting through the existing avvikelse system for any airway or haemodynamic event.

Informed choice for the clinical option is part of ordinary care. Separate research consent is used only if the ethics review says we are doing research.

## 9. Risks and mitigations

| Risk | Mitigation |
| --- | --- |
| Overselling PCS as analgesia | Script and decision aid quote PACSPI 2 on pain |
| Respiratory depression from propofol + alfentanil | PACSPI monitoring; small bolus; verbal prompt / chin lift / oxygen as expected responses; stop criteria |
| Pump programming error | Locked drug library; two-person check |
| List delay | Simulation first; kit pre-prepared; abandon if recovery time creeps |
| Inequity (language, cognitive impairment, inability to use the handset) | LA remains a full option; interpreter; no pressure to choose PCS |
| Selection of only “easy” patients | Track offer rate, not only uptake |
| Scope creep into a new RCT | Keep aims process-oriented; no new experimental regimen |

## 10. Work packages

Tracked as GitHub issues. Order is mostly sequential; protocol drafting can start in parallel with the baseline audit.

| WP | Issue | Content | Depends on |
| --- | --- | --- | --- |
| 1 | [#1](https://github.com/martingerdin/patient-controlled-sedation/issues/1) | Baseline audit of current SVP sedation practice | — |
| 2 | [#14](https://github.com/martingerdin/patient-controlled-sedation/issues/14) | QI team and stakeholder map | — |
| 3 | [#3](https://github.com/martingerdin/patient-controlled-sedation/issues/3) | Governance, ethics, data protection | 2 |
| 4 | [#4](https://github.com/martingerdin/patient-controlled-sedation/issues/4) | Clinical SOP (technique, staffing, discharge) | 1, 3 |
| 5 | [#5](https://github.com/martingerdin/patient-controlled-sedation/issues/5) | Patient information and shared decision aid | 4 |
| 6 | [#6](https://github.com/martingerdin/patient-controlled-sedation/issues/6) | Staff training and competency sign-off | 4 |
| 7 | [#7](https://github.com/martingerdin/patient-controlled-sedation/issues/7) | Safety net: monitoring, rescue, stop criteria | 4 |
| 8 | [#8](https://github.com/martingerdin/patient-controlled-sedation/issues/8) | Measurement plan and case report form | 1, 4 |
| 9 | [#9](https://github.com/martingerdin/patient-controlled-sedation/issues/9) | PDSA 1 — simulation / dry run | 4–8 |
| 10 | [#10](https://github.com/martingerdin/patient-controlled-sedation/issues/10) | PDSA 2 — limited clinical pilot | 9 |
| 11 | [#11](https://github.com/martingerdin/patient-controlled-sedation/issues/11) | PDSA 3 — scale-up on selected lists | 10 |
| 12 | [#12](https://github.com/martingerdin/patient-controlled-sedation/issues/12) | Analysis and SQUIRE 2.0 report | 11 |
| 13 | [#13](https://github.com/martingerdin/patient-controlled-sedation/issues/13) | Sustainment, standing SOP, and spread decision | 12 |

The literature review and this proposal are the starting documents; they are not open work packages. [Issue #2](https://github.com/martingerdin/patient-controlled-sedation/issues/2) is an accidental duplicate of #1 and can be closed.

## 11. Timeline (indicative, not a deadline)

QI time is measured in cycles, not calendar promises. A realistic shape for a small project on an already busy port list:

- **Prepare:** baseline audit, team, governance, SOP, decision aid, training materials.
- **Test:** simulation, then a handful of cases with the core team.
- **Implement:** extend to nominated lists once fidelity and safety look stable.
- **Sustain:** write the chosen process into the standing PM, train the wider group, and stop collecting extra data except for a light safety dashboard.

If simulation or the first five cases show unsafe airway events or material list delay, stop and reassess rather than “power through.”

## 12. Deliverables in this repository

| Deliverable | Location |
| --- | --- |
| Literature review | `docs/literature-review.md` |
| This proposal | `docs/project-proposal.md` |
| Later: SOP, decision aid, CRF, PDSA logs, SQUIRE draft | to be added under `docs/` as issues close |

## 13. Success, for us

The project has succeeded if a patient who wants to be in control of their own sedation can get PACSPI-style PCS on an ordinary port list, a patient who does not want sedation is not given it, both choices are documented, and the airway story remains boring.

## References

1. Seifert S, Taxbro K, Nilsson A, Azman J, Chew MS, Hammarskjöld F. Patient-controlled sedation in port implantation (PACSPI 2) — a randomised clinical trial. *Acta Anaesthesiol Scand*. 2026;70(1):e70148. doi:10.1111/aas.70148  
2. Ogrinc G, Davies L, Goodman D, Batalden P, Davidoff F, Stevens D. SQUIRE 2.0. *BMJ Qual Saf*. 2016;25:986-992.  
3. Langley GJ, et al. *The Improvement Guide*. 2nd ed. Jossey-Bass; 2009.  
4. Taxbro K, Berg S, Hammarskjöld F, Hanberger H, Malmvall BE. A prospective observational study on 249 subcutaneous central vein access ports in a Swedish county hospital. *Acta Oncol*. 2013;52:893-901.  
5. Seifert S, Taxbro K, Hammarskjöld F. PACSPI 1 — a feasibility trial. *BJA Open*. 2022;3:100026.  
6. Kreienbühl L, Elia N, Pfeil-Beun E, Walder B, Tramèr MR. Patient-controlled versus clinician-controlled sedation with propofol. *Anesth Analg*. 2018;127:873-880.
