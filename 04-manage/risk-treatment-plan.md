# Risk Treatment Plan

## Purpose

This document defines how EugTech Solutions Ltd will treat the AI risks identified for EugAI.

The purpose of this plan is to ensure that AI risks are prioritised, assigned to owners, treated within agreed timeframes, and monitored until closure.

## Treatment Approach

| Risk Level | Required Treatment |
|---|---|
| High | Treat within 30 days and report to leadership |
| Medium | Treat within 90 days and monitor regularly |
| Low | Accept with documented controls and periodic review |

## Treatment Options

| Option | Description |
|---|---|
| Treat | Implement additional controls to reduce likelihood or impact |
| Accept | Accept risk where it is within risk appetite |
| Transfer | Transfer part of the risk through supplier contracts or insurance |
| Avoid | Stop or restrict the AI activity creating the risk |

## Risk Treatment Plan

| Risk ID | Risk | Current Rating | Treatment Action | Owner | Target Date | Status |
|---|---|---|---|---|---|---|
| AIR-001 | LLM hallucination | High | Strengthen RAG grounding, improve uncertainty responses, review knowledge base monthly | Head of Product | 30 days | In progress |
| AIR-002 | Prompt injection | High | Harden system prompt, add input pattern detection, monitor abnormal outputs | AI Engineering Lead | 30 days | In progress |
| AIR-003 | PII leakage | High | Add PII detection and masking before prompts are processed | Data Protection Officer | 30 days | In progress |
| AIR-004 | Demographic bias | Medium | Continue quarterly bias testing and expand demographic test cases | Information Security Manager | 90 days | Implemented |
| AIR-005 | Jailbreaking | Medium | Add jailbreak detection rules and escalation after repeated suspicious prompts | AI Engineering Lead | 90 days | Implemented |
| AIR-006 | Training data poisoning | Medium | Restrict knowledge base editing and require content approval | Head of Product | 90 days | Implemented |
| AIR-007 | Model inversion | Low | Monitor systematic extraction attempts and limit output length | AI Engineering Lead | Review quarterly | Implemented |
| AIR-008 | Overreliance | Medium | Improve AI disclosure, add confidence messaging, require human review for sensitive topics | Head of Product | 90 days | In progress |
| AIR-009 | Transparency failure | Medium | Display AI disclosure at start of every interaction | Head of Product | 30 days | Implemented |
| AIR-010 | Model drift | Medium | Track monthly performance metrics and review model outputs | Information Security Manager | 90 days | In progress |
| AIR-011 | Third-party LLM API failure or breach | Medium | Review supplier security, monitor SLA, document contingency plan | Information Security Manager | 90 days | Implemented |
| AIR-012 | Misuse | Medium | Add scope restrictions and monitor out-of-scope queries | AI Engineering Lead | 90 days | Implemented |

## Monitoring Requirements

| Activity | Frequency | Owner |
|---|---|---|
| AI risk register review | Quarterly | Information Security Manager |
| High-risk treatment review | Monthly until closed | Information Security Manager |
| Bias assessment | Quarterly | Customer Experience Manager |
| Hallucination monitoring | Monthly | Head of Product |
| Red team testing | Annually | AI Engineering Lead |
| Supplier review | Annually | Information Security Manager |
| Incident review | After every AI incident | Information Security Manager |

## Residual Risk Acceptance

Residual risks may only be accepted when:

- Controls have been implemented
- The residual score is within risk appetite
- The risk owner approves acceptance
- Monitoring remains in place
- The decision is recorded in the AI Risk Register

## Escalation Criteria

A risk must be escalated to leadership if:

- It remains High after treatment
- It affects personal data
- It affects fairness or non-discrimination
- It creates customer harm
- It may breach the EU AI Act, UK GDPR, or contractual obligations
- Treatment is overdue

## Summary

This treatment plan ensures that all 12 AI risks have assigned owners, treatment actions, target dates, and monitoring requirements.

The plan supports ongoing AI governance and provides evidence that AI risks are being actively managed.

## Status

Status: Implemented  
Framework mapping: NIST AI RMF MANAGE 1.1, MANAGE 1.3, MANAGE 2.2  
Project: NIST AI RMF 1.0 Portfolio Project
