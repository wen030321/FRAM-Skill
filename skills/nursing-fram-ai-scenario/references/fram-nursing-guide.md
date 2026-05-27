# FRAM Nursing Guide

## Boundary Definition Checklist

- Setting: ward, emergency department, ICU, operating room, outpatient clinic, home care, long-term care, or community care.
- Workflow episode: one bounded episode that can be observed from start to end.
- Actors: primary nurse, charge nurse, physician, pharmacist, nursing assistant, patient, family, AI system, EHR, or monitoring system.
- Endpoint: a concrete workflow result, not a broad quality goal.
- Exclusions: activities that influence the workflow but will not be modeled in detail.

## Common Nursing Functions

Use these as candidates, then adapt to the case:

- Receive patient information
- Assess patient condition
- Prioritize nursing concerns
- Verify orders or care plan
- Communicate with interprofessional team
- Administer medication or intervention
- Document care
- Monitor response
- Escalate deterioration
- Educate patient or family
- Prepare handoff or discharge

## FRAM Aspect Prompts

- Input: What starts this function or what information/material is transformed?
- Output: What result is produced for another function?
- Preconditions: What must be true before this function can be performed?
- Resources: What people, tools, data, spaces, or devices are needed?
- Control: What rules, protocols, clinical judgment, policies, or alerts shape the function?
- Time: What deadlines, rhythms, delays, or time pressure matter?

## Variability Prompts

- Timing: early, late, rushed, delayed, interrupted.
- Precision: incomplete, ambiguous, duplicated, overly general, overly specific.
- Sequence: skipped, repeated, reordered, parallelized.
- Capacity: staffing, experience, fatigue, workload, patient acuity.
- Technology: EHR usability, alert burden, missing data, device integration.
- Communication: handoff quality, shared mental model, closed-loop confirmation.

## AI Scenario Design Prompts

- What nursing decision or coordination point is being supported?
- What data does the AI need, and how reliable is that data at the moment of use?
- Does the AI summarize, predict, detect, prioritize, recommend, or document?
- What does the nurse see first?
- What explanation is provided?
- How can the nurse accept, reject, correct, or escalate the AI output?
- What harms could appear through automation bias, missed context, inequity, privacy leakage, or alert fatigue?
