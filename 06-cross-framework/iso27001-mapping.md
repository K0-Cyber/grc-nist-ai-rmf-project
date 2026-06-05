# ISO 27001 Mapping to NIST AI RMF

## Purpose

This document maps the NIST AI RMF project to relevant ISO 27001 control areas.

The purpose is to show how AI governance and AI risk management connect to information security governance, risk assessment, access control, supplier management, incident response, and continual improvement.

## Framework Relationship

NIST AI RMF focuses on AI-specific risks such as hallucination, bias, prompt injection, transparency, and overreliance.

ISO 27001 focuses on information security risks relating to confidentiality, integrity, and availability.

Together, they provide a stronger governance foundation for AI systems.

## Cross-Framework Mapping

| NIST AI RMF Area | ISO 27001 Area | Connection |
|---|---|---|
| GOVERN | Clause 5 Leadership | AI governance requires leadership accountability, policies, roles, and risk appetite |
| GOVERN | Clause 6 Planning | AI risks must be considered within organisational risk planning |
| GOVERN | Annex A 5.1 Policies for information security | AI Security Policy supports broader information security policy requirements |
| GOVERN | Annex A 5.2 Information security roles and responsibilities | AI Governance RACI defines clear roles and responsibilities |
| MAP | Clause 6.1 Risk assessment | AI risk identification supports broader enterprise risk assessment |
| MAP | Annex A 5.9 Inventory of information and other associated assets | AI systems, models, prompts, logs, and knowledge bases should be treated as assets |
| MAP | Annex A 5.12 Classification of information | AI data and outputs should be classified based on sensitivity |
| MEASURE | Annex A 8.8 Management of technical vulnerabilities | Red team findings and prompt injection weaknesses support vulnerability management |
| MEASURE | Annex A 8.15 Logging | AI interaction logs support monitoring, investigation, and audit evidence |
| MEASURE | Annex A 8.16 Monitoring activities | Hallucination tracking, output monitoring, and anomaly detection support monitoring requirements |
| MANAGE | Annex A 5.24 Information security incident management planning and preparation | AI Incident Response Procedure aligns with incident management planning |
| MANAGE | Annex A 5.25 Assessment and decision on information security events | AI incident triage supports event assessment and classification |
| MANAGE | Annex A 5.26 Response to information security incidents | AI incident containment, analysis, remediation, and learning align with incident response |
| MANAGE | Annex A 5.27 Learning from information security incidents | Post-incident reviews update the risk register and RTM |
| MANAGE | Annex A 5.19 Information security in supplier relationships | Third-party LLM provider risks require supplier assessment and contractual controls |
| MANAGE | Annex A 8.10 Information deletion | AI decommissioning includes data retention, deletion, and evidence preservation |

## AI Evidence Supporting ISO 27001

| Evidence Document | ISO 27001 Relevance |
|---|---|
| AI Security Policy | Supports policy governance |
| AI Governance RACI | Supports roles and responsibilities |
| AI Risk Register | Supports risk assessment |
| Risk Treatment Plan | Supports risk treatment |
| Red Team Exercise Report | Supports vulnerability management and technical testing |
| Hallucination Rate Tracking | Supports monitoring and control effectiveness |
| AI Incident Response Procedure | Supports incident management |
| AI Decommission Procedure | Supports asset lifecycle, data retention, and secure disposal |
| OWASP LLM Top 10 Mapping | Supports technical security risk identification |

## Key Observations

- ISO 27001 provides the information security management system foundation.
- NIST AI RMF adds AI-specific governance, testing, trustworthiness, and lifecycle risk management.
- AI risks should be integrated into the wider organisational risk register.
- AI suppliers, logs, prompts, models, and knowledge bases should be treated as security-relevant assets.
- AI incident response should connect to the wider information security incident management process.

## Summary

This mapping shows how NIST AI RMF and ISO 27001 work together.

ISO 27001 provides the security governance structure, while NIST AI RMF provides AI-specific risk management for systems like EugAI.

## Status

Status: Implemented  
Framework mapping: NIST AI RMF to ISO 27001  
Project: NIST AI RMF 1.0 Portfolio Project
