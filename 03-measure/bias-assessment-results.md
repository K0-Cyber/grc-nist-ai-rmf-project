# Bias Assessment Results

## Purpose

This document records the simulated bias and fairness assessment results for EugAI.

The assessment evaluates whether EugAI provides consistent response quality across demographic variants while answering customer service queries.

## Assessment Summary

| Field | Details |
|---|---|
| System Name | EugAI Customer Service Chatbot |
| Assessment Type | Bias and fairness assessment |
| Framework Mapping | NIST AI RMF MEASURE 2.5 |
| Test Set Size | 200 query pairs |
| Assessment Date | January 2026 |
| Result | Pass |
| Pass Threshold | No group more than 10% below baseline |

## Test Metrics

| Metric | Target |
|---|---|
| Response quality | No demographic group more than 10% below baseline |
| Factual accuracy | Responses remain factually correct across variants |
| Helpfulness | Average score remains within acceptable range |
| Escalation rate | Similar queries receive similar escalation decisions |
| Tone | Responses remain respectful and professional |

## Bias Test Results

| Test Group | Baseline Score | Variant Score | Difference | Result |
|---|---:|---:|---:|---|
| Formal English baseline | 4.6 | 4.6 | 0% | Pass |
| Informal English variant | 4.6 | 4.4 | -4.3% | Pass |
| Non-standard English variant | 4.6 | 4.3 | -6.5% | Pass |
| Implied female name variant | 4.5 | 4.4 | -2.2% | Pass |
| Implied male name variant | 4.5 | 4.5 | 0% | Pass |
| Implied non-native English variant | 4.6 | 4.2 | -8.7% | Pass |
| Beginner technical literacy variant | 4.5 | 4.3 | -4.4% | Pass |
| Expert technical literacy variant | 4.5 | 4.6 | +2.2% | Pass |

## Factual Accuracy Results

| Test Group | Accuracy Rate | Target | Result |
|---|---:|---:|---|
| Baseline | 96.2% | 95% | Pass |
| Informal English | 95.7% | 95% | Pass |
| Non-standard English | 95.1% | 95% | Pass |
| Implied gender variants | 96.0% | 95% | Pass |
| Implied nationality variants | 95.3% | 95% | Pass |
| Technical literacy variants | 95.8% | 95% | Pass |

## Escalation Rate Results

| Test Group | Escalation Rate | Expected Result |
|---|---:|---|
| Baseline | 8.4% | Acceptable |
| Informal English | 8.7% | Acceptable |
| Non-standard English | 9.1% | Acceptable |
| Implied gender variants | 8.2% | Acceptable |
| Implied nationality variants | 9.0% | Acceptable |
| Technical literacy variants | 8.8% | Acceptable |

## Key Findings

| Finding | Description | Severity | Action |
|---|---|---|---|
| BF-001 | Non-standard English responses scored 6.5% below baseline | Low | Continue monitoring |
| BF-002 | Implied non-native English variant scored 8.7% below baseline | Low | Add more test cases in next quarterly review |
| BF-003 | No demographic group exceeded the 10% fail threshold | Informational | Assessment passed |
| BF-004 | Escalation rates were broadly consistent across groups | Informational | No immediate action required |

## Conclusion

The bias assessment passed.

No demographic group scored more than 10% below the neutral baseline. Some minor variation was observed for non-standard English and implied non-native English prompts, but the difference remained within the acceptable threshold.

These areas will continue to be monitored in the next quarterly assessment.

## Follow-Up Actions

| Action | Owner | Due Date | Status |
|---|---|---|---|
| Expand non-standard English test cases | Customer Experience Manager | Next quarterly review | Planned |
| Add more implied nationality variants | Information Security Manager | Next quarterly review | Planned |
| Review results with Head of Product | Information Security Manager | February 2026 | Complete |
| Update AI Risk Register if future disparity exceeds threshold | Information Security Manager | Ongoing | Open |

## Status

Status: Implemented  
Framework mapping: NIST AI RMF MEASURE 2.5  
Project: NIST AI RMF 1.0 Portfolio Project
