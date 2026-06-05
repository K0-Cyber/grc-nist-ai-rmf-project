# OWASP LLM Top 10 Mapping to NIST AI RMF

## Purpose

This document maps the OWASP LLM Top 10 risks to the NIST AI RMF categories, EugAI AI Risk Register references, and implemented controls.

The purpose is to show how technical AI security risks are connected to AI governance and risk management controls.

## AI System

| Field | Details |
|---|---|
| System Name | EugAI Customer Service Chatbot |
| Organisation | EugTech Solutions Ltd |
| Frameworks Mapped | OWASP LLM Top 10 and NIST AI RMF |
| Use Case | Customer service chatbot |
| Project Type | Simulated AI governance and security portfolio project |

## Mapping Table

| OWASP LLM Risk | Vulnerability | NIST AI RMF Category | Risk Register Reference | Control Implemented |
|---|---|---|---|---|
| LLM01 | Prompt Injection | Security | AIR-002 | Input validation, system prompt hardening, output monitoring, escalation after repeated suspicious attempts |
| LLM02 | Insecure Output Handling | Security | AIR-001 | Output sanitisation, no code execution from AI output, human review for sensitive topics |
| LLM03 | Training Data Poisoning | Security | AIR-006 | Knowledge base access control, content approval process, integrity monitoring, provenance tracking |
| LLM04 | Model Denial of Service | Reliability | AIR-011 | Rate limiting, API timeout configuration, fallback to human agents, supplier SLA monitoring |
| LLM05 | Supply Chain Vulnerabilities | Security | AIR-011 | API provider security assessment, contractual clauses, contingency planning |
| LLM06 | Sensitive Information Disclosure | Privacy | AIR-003 | PII detection, masking, data minimisation, retention limits, no PII in system prompts |
| LLM07 | Insecure Plugin Design | Security | Not applicable | No plugins currently deployed. Assessment required before future plugin integration |
| LLM08 | Excessive Agency | Accountability | AIR-008 | EugAI is advisory only and cannot take action on customer accounts without human confirmation |
| LLM09 | Overreliance | Reliability | AIR-008 | AI disclosure, confidence messaging, human escalation, human override available |
| LLM10 | Model Theft | Security | AIR-007 | API key rotation, rate limiting, output length limits, monitoring for systematic extraction attempts |

## Key Observations

- Prompt injection is one of the highest-priority risks for EugAI because users can directly interact with the chatbot.
- Sensitive information disclosure is a major privacy concern because users may accidentally enter personal data.
- Overreliance is controlled through transparency notices, confidence messaging, and human escalation.
- Supply chain risk exists because EugAI depends on a third-party LLM API provider.
- Insecure plugin design is not currently applicable because EugAI does not use plugins.

## Relationship to NIST AI RMF

| NIST AI RMF Function | OWASP Mapping Relevance |
|---|---|
| GOVERN | Defines roles, policies, and accountability for managing LLM risks |
| MAP | Identifies LLM-specific risks in EugAI's deployment context |
| MEASURE | Tests risks through hallucination tracking, bias assessment, and red team exercises |
| MANAGE | Treats risks through controls, incident response, and monitoring |

## Summary

This mapping shows that OWASP LLM Top 10 risks can be managed through the NIST AI RMF structure.

OWASP provides the technical AI security risk categories, while NIST AI RMF provides the governance, risk management, testing, and treatment structure.

## Status

Status: Implemented  
Framework mapping: NIST AI RMF MAP, MEASURE, MANAGE  
Project: NIST AI RMF 1.0 Portfolio Project
