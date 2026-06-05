# Hallucination Rate Tracking

## Purpose

This document tracks EugAI's factual accuracy and hallucination rate over time.

The purpose is to support the NIST AI RMF MEASURE function by monitoring whether EugAI produces accurate, grounded, and reliable customer service responses.

## AI System

| Field | Details |
|---|---|
| System Name | EugAI Customer Service Chatbot |
| Organisation | EugTech Solutions Ltd |
| Assessment Area | Reliability and hallucination monitoring |
| Framework Mapping | NIST AI RMF MEASURE 2.6 |
| Review Frequency | Monthly |

## Measurement Definitions

| Metric | Definition |
|---|---|
| Factual accuracy rate | Percentage of responses judged factually correct against approved knowledge base sources |
| Hallucination rate | Percentage of responses containing invented, unsupported, or false information |
| Confidence calibration | Whether EugAI expresses uncertainty when information is missing or unclear |
| Refusal rate | Percentage of legitimate queries incorrectly refused |
| Escalation appropriateness | Percentage of escalations that are justified based on sensitivity or uncertainty |

## Performance Targets

| Metric | Target |
|---|---|
| Factual accuracy rate | At least 95% |
| Hallucination rate | Less than 5% |
| Confidence calibration | AI expresses uncertainty when uncertain |
| Refusal rate | Less than 2% of legitimate queries |
| Escalation appropriateness | More than 90% of escalations justified |

## Monthly Tracking Results

| Month | Tested Responses | Factual Accuracy | Hallucination Rate | Refusal Rate | Escalation Appropriateness | Status |
|---|---:|---:|---:|---:|---:|---|
| January 2026 | 500 | 96.2% | 3.8% | 1.4% | 92.0% | Pass |
| February 2026 | 500 | 95.8% | 4.2% | 1.6% | 91.5% | Pass |
| March 2026 | 500 | 96.5% | 3.5% | 1.2% | 93.1% | Pass |
| April 2026 | 500 | 95.4% | 4.6% | 1.8% | 90.7% | Pass |
| May 2026 | 500 | 96.0% | 4.0% | 1.5% | 92.4% | Pass |
| June 2026 | 500 | 96.8% | 3.2% | 1.1% | 94.0% | Pass |

## Trend Summary

| Area | Observation |
|---|---|
| Factual accuracy | Remained above the 95% target across all six months |
| Hallucination rate | Remained below the 5% maximum threshold |
| Refusal rate | Remained below the 2% maximum threshold |
| Escalation appropriateness | Remained above the 90% target |
| Overall trend | Stable and acceptable |

## Example Hallucination Scenarios Monitored

| Scenario | Risk |
|---|---|
| AI describes a product feature that does not exist | Customer receives incorrect information |
| AI provides outdated pricing or service information | Customer confusion or complaint |
| AI invents support policy details | Inconsistent customer experience |
| AI fails to state uncertainty when knowledge base content is missing | Overreliance on unsupported response |

## Controls Used to Reduce Hallucination

| Control | Description |
|---|---|
| RAG grounding | EugAI retrieves content from approved knowledge base sources |
| Human escalation | Low-confidence or sensitive responses are escalated |
| Knowledge base review | Product content is reviewed and updated monthly |
| Output monitoring | Responses are sampled and reviewed for accuracy |
| Uncertainty prompting | EugAI is instructed to say when it does not know |
| Red team testing | Adversarial prompts are used to test hallucination behaviour |

## Findings

| Finding ID | Finding | Severity | Action |
|---|---|---|---|
| HR-001 | Accuracy remained above target in all months | Informational | Continue monitoring |
| HR-002 | Hallucination rate peaked at 4.6% in April but stayed below threshold | Low | Review April knowledge base updates |
| HR-003 | Escalation appropriateness remained above 90% | Informational | No action required |
| HR-004 | No high-risk hallucination events detected | Informational | Continue monthly review |

## Conclusion

EugAI met the factual accuracy and hallucination rate targets across the six-month monitoring period.

The system remains within risk appetite, provided monthly testing, knowledge base review, and human escalation controls continue.

## Status

Status: Implemented  
Framework mapping: NIST AI RMF MEASURE 2.6  
Project: NIST AI RMF 1.0 Portfolio Project
