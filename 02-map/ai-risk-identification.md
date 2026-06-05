# AI Risk Identification

## Purpose

This document identifies the main AI-specific risks associated with EugAI, a simulated customer service chatbot used by EugTech Solutions Ltd.

The purpose of this document is to support the NIST AI RMF MAP function by identifying what could go wrong, who could be affected, and which AI risk categories apply.

## AI System

| Field | Details |
|---|---|
| System Name | EugAI Customer Service Chatbot |
| Organisation | EugTech Solutions Ltd |
| System Type | Large Language Model chatbot |
| Use Case | First-line customer service |
| Deployment Context | Web chat widget on client portal |
| Users | SME employees across financial services, healthcare, and retail |

## AI Risk Categories

| AI Risk Category | Description | EugAI Relevance |
|---|---|---|
| Bias and Fairness | AI may produce systematically different quality responses for different users | Users with non-standard writing styles or implied demographic cues may receive lower quality responses |
| Data Privacy | AI may process personal data included in user queries | Users may accidentally submit personal data during support conversations |
| Security and Adversarial Misuse | AI may be attacked through prompt injection, jailbreaks, or data extraction attempts | Malicious users may try to override system instructions or extract sensitive information |
| Reliability and Robustness | AI may hallucinate, drift, or fail on edge cases | EugAI may confidently provide incorrect product information |
| Transparency and Explainability | Users may not understand they are interacting with AI or may not understand limitations | EU AI Act transparency obligations apply because EugAI interacts with humans |
| Accountability and Governance | Ownership of AI decisions and failures may be unclear | Clear roles are needed for system ownership, risk ownership, and incident response |

## Identified AI Risks

| Risk ID | Risk | Category | Description |
|---|---|---|---|
| AIR-001 | LLM hallucination | Reliability | EugAI may confidently provide false product information |
| AIR-002 | Prompt injection | Security | A user may attempt to override EugAI's system instructions |
| AIR-003 | PII leakage | Privacy | A user may submit personal data in a query and the AI may process or repeat it |
| AIR-004 | Demographic bias | Fairness | EugAI may provide lower quality responses to some demographic variants |
| AIR-005 | Jailbreaking | Security | A user may attempt to bypass content guardrails |
| AIR-006 | Training data poisoning | Security | Corrupted or malicious knowledge base content may affect AI outputs |
| AIR-007 | Model inversion | Security | Attackers may attempt to extract training data or sensitive information |
| AIR-008 | Overreliance | Reliability | Users may trust AI outputs over human judgement |
| AIR-009 | Transparency failure | Transparency | Users may not be clearly informed they are interacting with AI |
| AIR-010 | Model drift | Reliability | Performance may degrade over time |
| AIR-011 | Third-party LLM API failure or breach | Security | The external AI provider may suffer service failure or security compromise |
| AIR-012 | Misuse | Security | Users may attempt to extract sensitive competitor or internal information |

## Potentially Affected Groups

| Group | Potential Impact |
|---|---|
| Client users | May receive incorrect or misleading support responses |
| EugTech support staff | May need to manage escalations caused by AI errors |
| EugTech clients | May experience reputational or operational issues if AI responses are poor |
| Data subjects | May be affected if personal data is mishandled |
| EugTech leadership | Accountable for governance, compliance, and risk acceptance |

## Risk Identification Sources

AI risks were identified using:

- NIST AI RMF trustworthiness characteristics
- OWASP LLM Top 10 risk categories
- EU AI Act limited-risk transparency requirements
- Simulated red team findings
- Customer service chatbot deployment context
- Privacy and security considerations

## Summary

EugAI presents manageable but important AI risks across reliability, security, privacy, fairness, transparency, and accountability.

These risks are assessed and treated in the AI Risk Register and Requirements Traceability Matrix.

## Status

Status: Implemented  
Framework mapping: NIST AI RMF MAP 2.0  
Project: NIST AI RMF 1.0 Portfolio Project
