# AI Decommission Procedure

## Purpose

This document defines the process for safely retiring or disabling EugAI.

The purpose is to ensure that AI systems are decommissioned in a controlled way that protects users, data, security, compliance, and business continuity.

## Scope

This procedure applies when EugAI is:

- Permanently retired
- Replaced with another AI system
- Temporarily disabled after a serious incident
- Removed from a client environment
- No longer approved for use
- Reclassified into a higher-risk use case requiring redesign

## Decommission Triggers

| Trigger | Description |
|---|---|
| Business decision | EugTech decides to stop using EugAI |
| Replacement | EugAI is replaced by another AI system |
| Serious incident | EugAI causes unacceptable security, privacy, fairness, or reliability risk |
| Supplier issue | Third-party LLM provider becomes unavailable or non-compliant |
| Regulatory change | New obligations make current deployment non-compliant |
| Performance failure | EugAI repeatedly fails accuracy, bias, or hallucination thresholds |
| Scope change | EugAI is proposed for a use case outside current risk appetite |

## Decommission Process

### 1. Approve Decommission

The Information Security Manager and Head of Product must document:

- Reason for decommission
- Scope of affected users and systems
- Target date
- Business impact
- Risk impact
- Communication requirements

### 2. Notify Stakeholders

Stakeholders to notify include:

- CEO
- Information Security Manager
- Head of Product
- AI Engineering Lead
- Data Protection Officer
- Customer Experience Manager
- Support staff
- Affected clients or users where applicable

### 3. Disable AI Functionality

Technical steps include:

- Disable chatbot front-end access
- Stop API calls to third-party LLM provider
- Disable scheduled AI jobs
- Remove or archive system prompts
- Disable RAG retrieval connections
- Route customer service requests to human support
- Confirm no new user queries are processed by EugAI

### 4. Secure Logs and Evidence

Before deletion or archiving, preserve:

- Conversation logs
- Incident records
- Risk register entries
- Model card
- System card
- RTM evidence
- Red team reports
- Bias assessment records
- Supplier records

Logs must be retained according to legal, contractual, and privacy requirements.

### 5. Revoke Access and Credentials

Security actions include:

- Revoke API keys
- Remove service accounts
- Disable admin access
- Remove unused secrets from vaults
- Confirm no credentials remain in code or configuration
- Review audit logs for unusual access before shutdown

### 6. Data Retention and Deletion

The Data Protection Officer must confirm:

- What data must be retained
- What data must be deleted
- Whether personal data exists in logs
- Whether deletion is required under UK GDPR
- Whether clients need confirmation of deletion
- Whether anonymised evidence can be retained for audit purposes

### 7. Update Governance Documents

The following documents must be updated:

- AI Risk Register
- Requirements Traceability Matrix
- AI System Card
- Model Card
- Supplier register
- Incident log
- Asset inventory
- Business continuity documentation

### 8. Post-Decommission Review

A review must confirm:

- EugAI is no longer accessible to users
- API access has been revoked
- Data handling is complete
- Clients have been informed where required
- Replacement process is working
- Residual risks have been recorded
- Lessons learned have been documented

## Decommission Checklist

| Task | Owner | Status |
|---|---|---|
| Decommission approved | Head of Product | Pending |
| Stakeholders notified | Information Security Manager | Pending |
| Chatbot disabled | AI Engineering Lead | Pending |
| API keys revoked | AI Engineering Lead | Pending |
| Logs preserved | Information Security Manager | Pending |
| Data retention reviewed | Data Protection Officer | Pending |
| User communications issued | Customer Experience Manager | Pending |
| Risk register updated | Information Security Manager | Pending |
| RTM updated | Information Security Manager | Pending |
| Post-decommission review completed | Information Security Manager | Pending |

## Business Continuity

If EugAI is disabled, customer support will continue through:

- Human support agents
- Helpdesk ticketing system
- Knowledge base articles
- Email support
- Client service managers

## Summary

This procedure ensures EugAI can be safely retired or disabled without creating unmanaged security, privacy, operational, or compliance risks.

It supports responsible AI lifecycle management by ensuring controlled decommissioning.

## Status

Status: Implemented  
Framework mapping: NIST AI RMF MANAGE 4.2  
Project: NIST AI RMF 1.0 Portfolio Project
