# EU AI Act Mapping to NIST AI RMF

## Purpose

This document maps the NIST AI RMF project to relevant EU AI Act obligations and risk concepts.

The purpose is to show how AI risk management activities can support regulatory readiness for AI systems deployed in or affecting EU users.

## AI System Classification

| Field | Details |
|---|---|
| System Name | EugAI Customer Service Chatbot |
| Organisation | EugTech Solutions Ltd |
| AI Act Classification | Limited Risk |
| Reason | EugAI is a chatbot that interacts with natural persons |
| Main Obligation | Transparency |
| High Risk Status | Not high risk in current deployment |

## EU AI Act to NIST AI RMF Mapping

| EU AI Act Area | NIST AI RMF Function | Project Evidence | Connection |
|---|---|---|---|
| Article 6: Risk classification | MAP | EU AI Act Classification | EugAI is assessed against prohibited, high-risk, limited-risk, and minimal-risk categories |
| Article 9: Risk management system | MAP and MANAGE | AI Risk Register, Risk Treatment Plan | NIST AI RMF supports identifying, assessing, treating, and monitoring AI risks |
| Article 10: Data governance | GOVERN and MAP | AI System Card, Model Card, AI Risk Identification | Data sources, training data, RAG content, and personal data risks are documented |
| Article 11: Technical documentation | GOVERN | AI System Card, Model Card, RTM | System purpose, model details, limitations, and evidence are documented |
| Article 12: Record keeping and logging | MEASURE | Hallucination Rate Tracking, AI Incident Response Procedure | AI outputs, incidents, and monitoring evidence support record keeping |
| Article 13: Transparency and information provision | GOVERN and MAP | AI System Card, EU AI Act Classification | Users and stakeholders are informed about AI use, purpose, and limitations |
| Article 14: Human oversight | GOVERN and MANAGE | AI Security Policy, AI Incident Response Procedure | Human escalation and oversight are required for sensitive or low-confidence responses |
| Article 15: Accuracy, robustness, and cybersecurity | MEASURE | Hallucination Tracking, Red Team Report, OWASP Mapping | Testing and monitoring support accuracy, reliability, and cybersecurity expectations |
| Article 50: Transparency for chatbots | GOVERN and MAP | EU AI Act Classification, AI Security Policy | Users must know they are interacting with AI |
| Article 73: Serious incident reporting | MANAGE | AI Incident Response Procedure | AI incidents are detected, contained, analysed, remediated, and reviewed |

## Limited Risk Compliance Relevance

EugAI is currently classified as Limited Risk.

The main compliance expectation is that users must be clearly informed they are interacting with an AI system.

The following controls support this obligation:

| Control | Description |
|---|---|
| AI disclosure | Users are informed that EugAI is an AI assistant |
| No AI denial | EugAI must not deny being an AI system |
| Human escalation | Users can escalate to a human support agent |
| Transparency documentation | AI System Card and EU AI Act classification explain system purpose and limits |
| Monitoring | Transparency failures are treated as AI incidents |

## High Risk Reclassification Warning

EugAI could become High Risk if deployed for:

- Employment screening
- Credit assessment
- Education access or assessment
- Access to essential services
- Biometric identification or categorisation
- Law enforcement support
- Migration or asylum decisions
- Decisions affecting legal rights or fundamental rights

Before any High Risk use case, EugTech would need additional controls including:

- Formal EU AI Act High Risk gap assessment
- Technical documentation under Annex IV
- Stronger data governance
- Human oversight documentation
- Conformity assessment
- EU database registration where applicable
- Fundamental Rights Impact Assessment where required

## NIST AI RMF Support for AI Act Readiness

| NIST AI RMF Function | AI Act Readiness Benefit |
|---|---|
| GOVERN | Establishes accountability, policies, model documentation, and transparency controls |
| MAP | Identifies AI system context, affected users, possible harms, and classification |
| MEASURE | Tests bias, accuracy, hallucination, security, and robustness |
| MANAGE | Treats risks, responds to incidents, maintains evidence, and supports continual improvement |

## Key Observations

- NIST AI RMF does not automatically prove EU AI Act compliance.
- It provides strong supporting evidence for governance, risk management, testing, monitoring, and incident response.
- For EugAI's current Limited Risk deployment, transparency is the main EU AI Act concern.
- If EugAI is used in a High Risk context, additional regulatory documentation would be required.

## Summary

This mapping shows how NIST AI RMF supports EU AI Act readiness for EugAI.

The project demonstrates that AI risks have been identified, measured, managed, and linked to transparency, oversight, documentation, and incident response controls.

## Status

Status: Implemented  
Framework mapping: NIST AI RMF to EU AI Act  
Project: NIST AI RMF 1.0 Portfolio Project
