# AI System Context

## Purpose

This document describes the context in which EugAI operates.

The NIST AI RMF MAP function requires the organisation to understand the AI system's purpose, users, deployment environment, affected populations, potential harms, benefits, and regulatory context before assessing risk.

## System Overview

| Context Factor | EugAI Assessment |
|---|---|
| System name | EugAI Customer Service Chatbot |
| Organisation | EugTech Solutions Ltd |
| System type | Large Language Model chatbot |
| Use case | First-line customer service |
| Deployment channel | Web chat widget on client portal |
| Availability | 24/7 automated support with human agents available during business hours |
| Human support hours | 09:00 to 17:00 UK time |
| Estimated usage | Approximately 500 queries per day |

## Intended Purpose

EugAI is intended to:

- Answer customer product queries
- Troubleshoot common support issues
- Route complex cases to human agents
- Provide general guidance from approved knowledge base content
- Reduce wait times for common customer service queries

## Intended Users

| User Group | Description |
|---|---|
| Client employees | SME employees using EugTech client portals |
| Support staff | Human agents reviewing escalated conversations |
| Product team | System owners monitoring performance and business value |
| Security and governance teams | Teams reviewing logs, risks, and incidents |

## Impact Domain

EugAI operates in the customer service domain.

The current deployment is low criticality because EugAI does not provide:

- Medical advice
- Legal advice
- Financial advice
- Employment decisions
- Credit decisions
- Safety-critical decisions
- Automated decisions affecting legal rights

## Affected Populations

EugAI may affect:

- SME employees in financial services
- SME employees in healthcare
- SME employees in retail
- Users with different levels of technical literacy
- Users with different writing styles or language formality
- Users who may accidentally include personal data in support queries

## Potential Benefits

| Benefit | Description |
|---|---|
| Faster support | Users can receive immediate responses to common questions |
| 24/7 availability | Support is available outside normal business hours |
| Reduced support workload | Human agents can focus on complex cases |
| Consistent answers | Approved knowledge base content can be reused consistently |
| Improved triage | Complex or sensitive queries can be routed to human agents |

## Potential Harms

| Harm Area | Description |
|---|---|
| Incorrect advice | EugAI may provide inaccurate or outdated product information |
| Privacy breach | Users may submit personal data that is processed or repeated |
| Bias or unfairness | Some users may receive lower quality responses based on writing style or implied demographics |
| Overreliance | Users may rely on AI responses when human confirmation is needed |
| Reputational harm | Poor AI output may reduce trust in EugTech |
| Security misuse | Attackers may attempt prompt injection, jailbreaks, or data extraction |

## Rights and Equity Concerns

EugAI must respond equally well regardless of:

- Writing style
- Language formality
- Implied gender
- Implied nationality
- Technical literacy
- Customer sector

Quarterly bias testing is used to monitor whether response quality differs across demographic variants.

## Regulatory Context

| Regulation or Framework | Relevance |
|---|---|
| NIST AI RMF 1.0 | Primary framework used to map, measure, and manage AI risk |
| UK GDPR | Applies where personal data is processed in user queries or logs |
| ICO AI guidance | Relevant to responsible AI use and data protection |
| EU AI Act | Applies because EugTech serves EU clients |
| Equality Act 2010 | Relevant to fairness and non-discrimination |
| OWASP LLM Top 10 | Used to identify technical AI security risks |

## AI Act Risk Classification

EugAI is classified as a Limited Risk AI system under the EU AI Act because it is a chatbot that interacts with natural persons.

The main obligation is transparency: users must know they are interacting with an AI system.

## Summary

EugAI is a customer service AI system with low criticality but meaningful risks relating to security, privacy, reliability, fairness, transparency, and accountability.

The system remains acceptable only where human oversight, monitoring, escalation, and transparency controls are maintained.

## Status

Status: Implemented  
Framework mapping: NIST AI RMF MAP 1.0  
Project: NIST AI RMF 1.0 Portfolio Project
