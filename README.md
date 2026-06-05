# NIST AI RMF 1.0 Portfolio Project

## Project Overview

This project applies the NIST AI Risk Management Framework 1.0 to a simulated AI system called EugAI, a customer service chatbot used by EugTech Solutions Ltd.

The project demonstrates how AI risks can be identified, assessed, measured, managed, and traced back to specific controls and evidence using the four NIST AI RMF functions:

- GOVERN
- MAP
- MEASURE
- MANAGE

## AI System

| Field | Details |
|---|---|
| System Name | EugAI Customer Service Chatbot |
| Organisation | EugTech Solutions Ltd |
| System Type | Large Language Model chatbot |
| Use Case | First-line customer service support |
| Risk Context | Limited-risk AI system with security, privacy, reliability, fairness, transparency, and governance considerations |

## Project Objectives

The objectives of this project are to:

- Document the AI system context, purpose, users, limitations, and accountability
- Identify and assess AI-specific risks such as hallucination, prompt injection, bias, privacy leakage, overreliance, and model drift
- Create a Requirements Traceability Matrix linking NIST AI RMF requirements to controls and evidence
- Demonstrate AI governance through policies, roles, responsibilities, and risk appetite
- Assess bias, fairness, hallucination rate, and AI red team findings
- Map AI risks to OWASP LLM Top 10, ISO 27001, and EU AI Act requirements

## Repository Structure

```text
grc-nist-ai-rmf-project/
├── README.md
├── 01-govern/
│   ├── ai-system-card.md
│   ├── ai-security-policy.md
│   ├── ai-governance-raci.md
│   ├── model-card.md
│   └── ai-risk-appetite-statement.md
├── 02-map/
│   ├── ai-risk-identification.md
│   ├── ai-system-context.md
│   └── eu-ai-act-classification.md
├── 03-measure/
│   ├── bias-assessment-methodology.md
│   ├── bias-assessment-results.md
│   ├── hallucination-rate-tracking.md
│   └── red-team-exercise-report.md
├── 04-manage/
│   ├── ai-risk-register.md
│   ├── risk-treatment-plan.md
│   ├── ai-incident-response-procedure.md
│   └── ai-decommission-procedure.md
├── 05-rtm/
│   └── requirements-traceability-matrix.md
├── 06-cross-framework/
│   ├── owasp-llm-top10-mapping.md
│   ├── iso27001-mapping.md
│   └── eu-ai-act-mapping.md
└── screenshots/
    └── .gitkeep
```

## Key Deliverables

| Deliverable | Purpose |
|---|---|
| AI System Card | Documents the AI system purpose, users, data, oversight, and limitations |
| Model Card | Documents model characteristics, training data, evaluation results, and known limitations |
| AI Security Policy | Defines the organisation’s approach to trustworthy and secure AI |
| AI Governance RACI | Assigns AI risk and governance responsibilities |
| AI Risk Register | Records 12 AI-specific risks with likelihood, impact, residual risk, and status |
| Requirements Traceability Matrix | Maps NIST AI RMF requirements to controls, implementation evidence, and status |
| Red Team Exercise Report | Documents AI security testing findings and remediation actions |
| Bias Assessment | Assesses potential demographic bias in AI responses |
| OWASP LLM Top 10 Mapping | Maps LLM security risks to NIST AI RMF and the AI Risk Register |
| AI Incident Response Procedure | Defines how hallucination, privacy, bias, security, and transparency incidents are handled |
| Cross-Framework Mapping | Links NIST AI RMF to OWASP LLM Top 10, ISO 27001, and the EU AI Act |

## Framework Coverage

### GOVERN

The GOVERN function establishes AI governance, accountability, policies, roles, and risk appetite.

Deliverables include:

- AI System Card
- AI Security Policy
- AI Governance RACI
- Model Card
- AI Risk Appetite Statement

### MAP

The MAP function identifies the AI system context, affected users, possible harms, regulatory considerations, and AI-specific risk categories.

Deliverables include:

- AI Risk Identification
- AI System Context
- EU AI Act Classification

### MEASURE

The MEASURE function evaluates and tests AI risks, including bias, hallucination, reliability, robustness, and red team findings.

Deliverables include:

- Bias Assessment Methodology
- Bias Assessment Results
- Hallucination Rate Tracking
- Red Team Exercise Report

### MANAGE

The MANAGE function prioritises, treats, monitors, and improves AI risk management activities.

Deliverables include:

- AI Risk Register
- Risk Treatment Plan
- AI Incident Response Procedure
- AI Decommission Procedure

## Requirements Traceability Matrix

The Requirements Traceability Matrix is the centrepiece of this project. It links NIST AI RMF sub-categories to:

- Control implementation
- Evidence
- Status
- Responsible governance area

This demonstrates how AI governance requirements can be converted into practical, auditable controls.

## Skills Demonstrated

- AI risk management
- GRC documentation
- Requirements traceability
- AI governance and accountability
- Bias and fairness assessment
- AI red teaming
- AI incident response
- OWASP LLM Top 10 mapping
- ISO 27001 cross-framework mapping
- EU AI Act awareness

## Screenshots

The screenshots folder will contain visual evidence of the main project deliverables.

| Screenshot | File Name |
|---|---|
| AI System Card | 01-ai-system-card.png |
| AI Governance RACI | 02-ai-governance-raci.png |
| Bias Assessment Results | 03-bias-assessment-results.png |
| Hallucination Rate Tracking | 04-hallucination-rate-tracking.png |
| Red Team Findings | 05-red-team-findings.png |
| Requirements Traceability Matrix | 06-rtm-complete.png |
| Model Card | 07-model-card.png |
| OWASP LLM Top 10 Mapping | 08-owasp-llm-mapping.png |

## Disclaimer

This is a simulated portfolio project created for educational and professional development purposes. EugTech Solutions Ltd and EugAI are fictional examples used to demonstrate AI governance, risk management, and compliance documentation.
