# AI Governance RACI

## Purpose

This document defines the governance roles and responsibilities for EugAI, a simulated customer service chatbot used by EugTech Solutions Ltd.

The purpose of this RACI is to show clear accountability for AI risk management, system ownership, privacy, technical controls, monitoring, and incident response.

## AI Governance Roles

| Role | AI RMF Responsibility |
|---|---|
| Chief Executive Officer | Ultimate accountability for AI risk appetite and business impact decisions |
| Information Security Manager | AI risk owner. Maintains AI risk register, coordinates assessments, and reports to leadership |
| Head of Product | System owner. Accountable for EugAI's business purpose and performance |
| AI Engineering Lead | Technical implementation of AI controls, prompt guardrails, logging, and model versioning |
| Data Protection Officer | UK GDPR compliance for personal data processed by or passed to EugAI |
| Customer Experience Manager | Monitors AI output quality and user satisfaction |
| All Client-Facing Staff | Report suspected AI failures or inappropriate outputs immediately |

## RACI Matrix

| Activity | CEO | ISM | Head of Product | AI Engineering Lead | DPO | Customer Experience Manager | Client-Facing Staff |
|---|---|---|---|---|---|---|---|
| Approve AI risk appetite | A | C | C | I | C | I | I |
| Maintain AI risk register | I | A/R | C | C | C | I | I |
| Own EugAI business purpose | I | C | A/R | C | I | C | I |
| Implement prompt guardrails | I | C | C | A/R | C | I | I |
| Monitor AI output quality | I | C | C | C | I | A/R | R |
| Manage privacy compliance | I | C | I | C | A/R | I | I |
| Report AI incidents | I | A | C | R | C | R | R |
| Review model performance | I | C | A | R | C | R | I |
| Escalate high-risk responses | I | C | A | C | C | R | R |

## RACI Key

| Letter | Meaning |
|---|---|
| R | Responsible: Performs the activity |
| A | Accountable: Owns the final decision or outcome |
| C | Consulted: Provides input before action is taken |
| I | Informed: Kept updated on progress or outcome |

## Governance Notes

- The Information Security Manager owns the AI risk management process.
- The Head of Product owns the business use and customer impact of EugAI.
- The AI Engineering Lead owns technical safeguards.
- The Data Protection Officer must be consulted for any AI use involving personal data.
- All staff are responsible for reporting suspected AI failures or misuse.

## Status

Status: Implemented  
Framework mapping: NIST AI RMF GOVERN 1.2  
Project: NIST AI RMF 1.0 Portfolio Project