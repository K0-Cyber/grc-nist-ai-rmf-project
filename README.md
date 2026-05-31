# NIST AI RMF 1.0 Portfolio Project

## Project Overview

This project applies the NIST AI Risk Management Framework 1.0 to a simulated AI system called EugAI, a customer service chatbot used by EugTech Solutions Ltd.

The project demonstrates how AI risks can be identified, assessed, measured, managed, and traced back to specific controls and evidence using the four NIST AI RMF functions:

- GOVERN
- MAP
- MEASURE
- MANAGE

## AI System

**System Name:** EugAI Customer Service Chatbot  
**Organisation:** EugTech Solutions Ltd  
**System Type:** Large Language Model chatbot  
**Use Case:** First-line customer service support  
**Risk Context:** Limited-risk AI system with security, privacy, reliability, fairness, transparency, and governance considerations

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
