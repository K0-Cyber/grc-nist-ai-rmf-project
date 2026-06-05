# AI Risk Register

## Purpose

This document records the AI-specific risks identified for EugAI, a simulated customer service chatbot used by EugTech Solutions Ltd.

The purpose of this register is to support the NIST AI RMF MANAGE function by documenting AI risks, likelihood, impact, risk rating, residual risk, owner, and treatment status.

## Risk Scoring Method

| Score | Likelihood | Impact |
|---|---|---|
| 1 | Rare | Negligible |
| 2 | Unlikely | Minor |
| 3 | Possible | Moderate |
| 4 | Likely | Major |
| 5 | Almost certain | Critical |

## Risk Rating

| Score | Rating |
|---|---|
| 1-4 | Low |
| 5-9 | Medium |
| 10-25 | High |

## AI Risk Register

| Risk ID | AI Risk | Category | Likelihood | Impact | Rating | Control | Residual Risk | Status |
|---|---|---|---:|---:|---|---|---|---|
| AIR-001 | LLM hallucination: confident false product information | Reliability | 3 | 4 | High: 12 | RAG grounding, knowledge base review, human escalation | Medium: 6 | In progress |
| AIR-002 | Prompt injection: user manipulates AI behaviour | Security | 3 | 4 | High: 12 | Prompt hardening, input validation, output monitoring | Low: 4 | In progress |
| AIR-003 | PII leakage: user submits personal data in queries | Privacy | 4 | 3 | High: 12 | PII detection, masking, retention limits, privacy notice | Medium: 6 | In progress |
| AIR-004 | Demographic bias: lower quality responses for some groups | Fairness | 2 | 4 | Medium: 8 | Quarterly bias testing and remediation process | Low: 4 | Implemented |
| AIR-005 | Jailbreaking: bypassing content guardrails | Security | 2 | 4 | Medium: 8 | Jailbreak pattern detection and escalation | Low: 3 | Implemented |
| AIR-006 | Training data poisoning: corrupted knowledge base | Security | 1 | 5 | Medium: 5 | Knowledge base access control and content approval | Low: 2 | Implemented |
| AIR-007 | Model inversion: extracting training data from outputs | Security | 1 | 4 | Low: 4 | Output controls, rate limiting, monitoring | Low: 2 | Implemented |
| AIR-008 | Overreliance: users trust AI over human judgement | Reliability | 3 | 3 | Medium: 9 | AI disclosure, confidence indicators, human escalation | Medium: 6 | In progress |
| AIR-009 | Transparency failure: users unaware they are talking to AI | Transparency | 2 | 4 | Medium: 8 | AI disclosure notice and system prompt controls | Low: 2 | Implemented |
| AIR-010 | Model drift: performance degradation over time | Reliability | 3 | 3 | Medium: 9 | Monthly performance monitoring and periodic testing | Medium: 5 | In progress |
| AIR-011 | Third-party LLM API failure or breach | Security | 2 | 4 | Medium: 8 | Supplier assessment, SLA review, contingency planning | Low: 4 | Implemented |
| AIR-012 | Misuse: users extract sensitive competitor or internal information | Security | 2 | 3 | Medium: 6 | Scope restriction, output monitoring, escalation | Low: 3 | Implemented |

## Risk Owners

| Risk Area | Owner |
|---|---|
| AI governance and risk register | Information Security Manager |
| Product performance and customer impact | Head of Product |
| Technical AI controls | AI Engineering Lead |
| Privacy and personal data | Data Protection Officer |
| Customer feedback and quality | Customer Experience Manager |

## Summary

The AI Risk Register identifies 12 risks across reliability, security, privacy, fairness, transparency, and governance.

No high residual risks remain after controls are applied. High inherent risks are being actively treated through technical, governance, and monitoring controls.

## Status

Status: Implemented  
Framework mapping: NIST AI RMF MANAGE 1.1, MANAGE 1.3, MANAGE 2.4  
Project: NIST AI RMF 1.0 Portfolio Project
