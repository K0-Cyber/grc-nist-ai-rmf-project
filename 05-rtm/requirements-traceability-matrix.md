# Requirements Traceability Matrix

## Purpose

This Requirements Traceability Matrix maps NIST AI RMF requirements to the controls, implementation evidence, and status for EugAI.

The RTM is the centrepiece of this project because it shows how AI governance requirements are converted into practical and auditable controls.

## AI System

| Field | Details |
|---|---|
| System Name | EugAI Customer Service Chatbot |
| Organisation | EugTech Solutions Ltd |
| Framework | NIST AI RMF 1.0 |
| Functions Covered | GOVERN, MAP, MEASURE, MANAGE |
| Project Type | Simulated AI governance and risk management portfolio project |

## Status Key

| Status | Meaning |
|---|---|
| Implemented | Control is documented and operating |
| Partially Implemented | Control exists but requires improvement |
| Planned | Control has been identified but not yet implemented |

---

# GOVERN Function

| Req. ID | Category | Control / Sub-Category | Implementation | Evidence | Status |
|---|---|---|---|---|---|
| GOV-1.1 | Governance | AI policies established | AI Security Policy approved. AI System Card completed. RACI matrix documented. | AI Security Policy, AI System Card, AI Governance RACI | Implemented |
| GOV-1.2 | Governance | Roles and responsibilities | ISM assigned as AI Risk Owner. Head of Product assigned as System Owner. DPO assigned for privacy compliance. | AI Governance RACI | Implemented |
| GOV-1.3 | Governance | Organisational culture | AI ethics principles communicated. AI literacy training required for staff using AI tools. | Training records, policy communications | Partially Implemented |
| GOV-1.4 | Governance | Organisational teams | AI governance responsibilities assigned across security, product, engineering, privacy, and customer experience. | RACI matrix, governance documentation | Partially Implemented |
| GOV-1.5 | Governance | Organisational risk tolerance | AI risk appetite defined. No AI decisions on financial, health, legal, or safety matters without human review. | AI Risk Appetite Statement | Implemented |
| GOV-1.6 | Governance | Policies updated through lifecycle | AI policies reviewed after incidents, major system changes, or regulatory changes. | Policy review schedule | Implemented |
| GOV-1.7 | Governance | Model documentation | Model Card completed for EugAI. Includes model type, intended use, training sources, evaluation, limitations, and ethical considerations. | Model Card | Implemented |
| GOV-2.1 | Governance | Risk tolerance communicated | AI risk appetite communicated to product, engineering, and support teams. | Risk appetite statement, governance communications | Partially Implemented |
| GOV-4.1 | Governance | Teams understand AI risks | Relevant staff are trained on AI risks including hallucination, bias, privacy, and prompt injection. | Training records | Partially Implemented |
| GOV-6.1 | Governance | Supply chain policies | LLM API provider assessed as a third-party supplier. AI-specific supplier controls identified. | Supplier assessment, cross-framework mapping | Implemented |

---

# MAP Function

| Req. ID | Category | Control / Sub-Category | Implementation | Evidence | Status |
|---|---|---|---|---|---|
| MAP-1.1 | Risk Identification | AI system context documented | EugAI purpose, users, deployment context, data handled, benefits, and harms documented. | AI System Context, AI System Card | Implemented |
| MAP-1.5 | Risk Identification | Organisational risk tolerance mapped | EugAI classified as a low-criticality customer service chatbot with limited-risk obligations. | AI Risk Appetite Statement, EU AI Act Classification | Implemented |
| MAP-1.6 | Risk Identification | Scientific and technical sources reviewed | AI risks identified using NIST AI RMF, OWASP LLM Top 10, EU AI Act, and privacy/security considerations. | AI Risk Identification, OWASP Mapping | Implemented |
| MAP-2.1 | Risk Identification | Scientific basis for risk impacts | AI risk categories based on trustworthiness characteristics and LLM security risks. | AI Risk Identification | Implemented |
| MAP-2.2 | Risk Identification | Risk metrics defined | 12 AI risks identified with likelihood, impact, rating, residual risk, and status. | AI Risk Register | Implemented |
| MAP-2.3 | Risk Identification | AI system classification | EugAI classified as Limited Risk under the EU AI Act because it is a chatbot interacting with humans. | EU AI Act Classification | Implemented |
| MAP-3.5 | Risk Identification | Third-party risks identified | Third-party LLM API provider risk identified, including API failure, breach, and supplier dependency. | AI Risk Register, Risk Treatment Plan | Partially Implemented |
| MAP-5.1 | Risk Identification | Likelihood of impact assessed | All 12 AI risks scored using likelihood and impact methodology. | AI Risk Register | Implemented |
| MAP-5.2 | Risk Identification | Practices for impact assessment | Bias testing, hallucination monitoring, red team testing, and incident response used to assess impact. | Bias Assessment, Hallucination Tracking, Red Team Report | Implemented |

---

# MEASURE Function

| Req. ID | Category | Control / Sub-Category | Implementation | Evidence | Status |
|---|---|---|---|---|---|
| MEA-1.1 | Measurement | AI risk metrics established | Metrics defined for factual accuracy, hallucination rate, bias, refusal rate, escalation appropriateness, and incident tracking. | Hallucination Rate Tracking, Bias Assessment Results | Implemented |
| MEA-2.2 | Measurement | AI risk monitoring | Monthly performance monitoring and AI interaction review defined. | Hallucination Rate Tracking | Partially Implemented |
| MEA-2.3 | Measurement | AI system testing | Testing includes hallucination assessment, bias assessment, red team testing, and output review. | Bias Assessment Methodology, Red Team Report | Implemented |
| MEA-2.5 | Measurement | Bias and fairness evaluation | Quarterly bias assessment performed using 200 query pairs and demographic variants. | Bias Assessment Methodology, Bias Assessment Results | Implemented |
| MEA-2.6 | Measurement | Explainability and reliability evaluation | Accuracy and hallucination rate tracked monthly. RAG grounding and uncertainty messaging defined. | Hallucination Rate Tracking, Model Card | Partially Implemented |
| MEA-2.7 | Measurement | Red team exercises | Red team exercise conducted with 5 findings across prompt injection, jailbreak, PII handling, scope bypass, and hallucination. | Red Team Exercise Report | Implemented |
| MEA-2.8 | Measurement | Feedback mechanisms | User feedback, escalation review, and customer support input included in monitoring process. | AI Incident Response Procedure, Risk Treatment Plan | Partially Implemented |
| MEA-4.1 | Measurement | Measurement results communicated | Results reported to AI governance stakeholders and used to update risks and controls. | Risk Treatment Plan, AI Risk Register | Partially Implemented |

---

# MANAGE Function

| Req. ID | Category | Control / Sub-Category | Implementation | Evidence | Status |
|---|---|---|---|---|---|
| MAN-1.1 | Management | Risk prioritisation | AI risks prioritised by rating. High risks treated within 30 days and medium risks within 90 days. | AI Risk Register, Risk Treatment Plan | Implemented |
| MAN-1.3 | Management | Risk treatment plans | Treatment actions documented for all 12 AI risks. | Risk Treatment Plan | Implemented |
| MAN-2.2 | Management | Mechanisms to sustain risk treatment | Quarterly risk review, monthly KPI review, annual red team testing, and incident reviews defined. | Risk Treatment Plan | Implemented |
| MAN-2.4 | Management | Residual risk documented | Residual risk scores recorded for all 12 AI risks. | AI Risk Register | Implemented |
| MAN-3.1 | Management | AI incident response | AI-specific incident response procedure covers hallucination, security, privacy, bias, availability, transparency, and data poisoning incidents. | AI Incident Response Procedure | Implemented |
| MAN-3.2 | Management | Incidents documented | Incident evidence requirements defined, including timeline, root cause, corrective actions, and post-incident review. | AI Incident Response Procedure | Partially Implemented |
| MAN-4.1 | Management | Continual improvement | Lessons learned from incidents and testing update the risk register and RTM. | AI Incident Response Procedure, Risk Treatment Plan | Partially Implemented |
| MAN-4.2 | Management | Decommission process | AI decommission procedure documents how to safely disable EugAI, revoke access, preserve evidence, and manage data retention. | AI Decommission Procedure | Implemented |

---

# Evidence Mapping Summary

| Evidence Document | Related Function |
|---|---|
| AI System Card | GOVERN, MAP |
| AI Security Policy | GOVERN |
| AI Governance RACI | GOVERN |
| Model Card | GOVERN, MEASURE |
| AI Risk Appetite Statement | GOVERN, MAP |
| AI Risk Identification | MAP |
| AI System Context | MAP |
| EU AI Act Classification | MAP |
| Bias Assessment Methodology | MEASURE |
| Bias Assessment Results | MEASURE |
| Hallucination Rate Tracking | MEASURE |
| Red Team Exercise Report | MEASURE |
| AI Risk Register | MAP, MANAGE |
| Risk Treatment Plan | MANAGE |
| AI Incident Response Procedure | MANAGE |
| AI Decommission Procedure | MANAGE |
| OWASP LLM Top 10 Mapping | MAP, MEASURE |
| ISO 27001 Mapping | GOVERN, MANAGE |
| EU AI Act Mapping | MAP, GOVERN |

## Key Observations

- The RTM covers all four NIST AI RMF functions: GOVERN, MAP, MEASURE, and MANAGE.
- The strongest evidence documents are the AI Risk Register, RTM, Red Team Exercise Report, Bias Assessment Results, and AI Incident Response Procedure.
- Partial implementation items show realistic governance maturity rather than claiming everything is perfect.
- The RTM provides audit-style traceability between framework requirements, controls, evidence, and status.

## Conclusion

This Requirements Traceability Matrix demonstrates how the NIST AI RMF can be applied to a real-world AI system use case.

It provides clear evidence that EugAI's AI risks have been identified, measured, managed, and mapped to governance controls.

## Status

Status: Implemented  
Framework mapping: NIST AI RMF GOVERN, MAP, MEASURE, MANAGE  
Project: NIST AI RMF 1.0 Portfolio Project
