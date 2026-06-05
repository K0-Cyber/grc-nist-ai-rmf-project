# AI Incident Response Procedure

## Purpose

This document defines the procedure for detecting, containing, analysing, remediating, and learning from AI incidents involving EugAI.

The purpose is to ensure that AI-specific incidents are handled consistently and that lessons learned are used to improve controls.

## Scope

This procedure applies to incidents involving:

- Hallucination
- Prompt injection
- Jailbreaking
- PII leakage
- Bias or unfair treatment
- Transparency failure
- Data poisoning
- Model misuse
- Third-party AI provider failure
- AI system availability issues

## AI Incident Classification

| Incident Type | Definition and Example |
|---|---|
| Hallucination Incident | AI confidently states something factually incorrect, such as describing a product feature that does not exist |
| Security Incident | Successful prompt injection, jailbreak, data extraction, or adversarial exploitation |
| Privacy Incident | Personal data is processed, repeated, retained, or exposed beyond intended scope |
| Bias Incident | Evidence that AI systematically provides lower quality service to a specific group |
| Availability Incident | AI system is unavailable or severely degraded, affecting client service levels |
| Transparency Incident | AI denies being AI or fails to disclose its AI nature |
| Data Poisoning Incident | Malicious or inaccurate content is introduced into the knowledge base |

## Severity Levels

| Severity | Description | Example |
|---|---|---|
| High | Incident causes or could cause significant harm, regulatory breach, or widespread customer impact | PII leakage, successful jailbreak, systematic bias |
| Medium | Incident affects service quality or trust but is contained | Hallucinated product information affecting a small number of users |
| Low | Minor issue with limited impact | Single incorrect response with no customer harm |

## Incident Response Process

### 1. Detect

Potential AI incidents may be detected through:

- User reports
- Human agent escalation
- Automated monitoring
- Red team testing
- Log review
- Customer complaints
- Third-party provider alerts

All suspected AI incidents must be reported to the Information Security Manager.

### 2. Contain

Containment actions may include:

- Disable EugAI for high-severity incidents
- Route all affected queries to human agents
- Restrict specific query types
- Preserve all logs
- Prevent deletion of conversation records
- Disable affected knowledge base content
- Rotate API credentials if compromise is suspected

### 3. Analyse

The incident owner must determine:

- What happened
- Which users were affected
- Which AI risk category applies
- Whether personal data was involved
- Whether regulatory notification may be required
- Whether the root cause was model behaviour, knowledge base error, adversarial input, supplier failure, or process failure

### 4. Remediate

Remediation actions may include:

- Update system prompts
- Improve guardrails
- Remove or correct knowledge base content
- Add PII masking
- Improve bias testing
- Strengthen monitoring
- Retest the fix before re-enabling production
- Update the AI Risk Register

### 5. Learn

After remediation, EugTech must:

- Conduct a post-incident review within 5 business days
- Update the AI Risk Register
- Update the Requirements Traceability Matrix if a control gap is identified
- Add new red team test cases where relevant
- Brief relevant staff on lessons learned
- Report significant findings to governance stakeholders

## Incident Reporting Timeline

| Step | Target Time |
|---|---|
| Staff report suspected incident | Immediately |
| ISM initial triage | Within 1 hour |
| High-severity containment | Immediately after confirmation |
| Initial analysis | Within 24 hours |
| Post-incident review | Within 5 business days |
| Risk register update | Within 5 business days |
| Control retest | Before production re-enable where applicable |

## Roles and Responsibilities

| Role | Responsibility |
|---|---|
| Information Security Manager | Owns incident coordination and risk register updates |
| AI Engineering Lead | Investigates technical cause and implements technical remediation |
| Head of Product | Assesses business and customer impact |
| Data Protection Officer | Assesses privacy and UK GDPR implications |
| Customer Experience Manager | Coordinates customer support and user communications |
| CEO | Receives escalation for high-severity incidents |

## Evidence Produced

Each AI incident should produce:

- Incident record
- Timeline of events
- Affected users or systems
- Root cause analysis
- Corrective actions
- Risk register update
- RTM update where required
- Post-incident review notes

## Summary

This procedure provides a structured process for responding to AI-specific incidents, including hallucination, misuse, privacy, bias, transparency, and security events.

It supports the NIST AI RMF MANAGE function by ensuring AI incidents are detected, contained, analysed, remediated, and used for continual improvement.

## Status

Status: Implemented  
Framework mapping: NIST AI RMF MANAGE 3.1 and MANAGE 3.2  
Project: NIST AI RMF 1.0 Portfolio Project
