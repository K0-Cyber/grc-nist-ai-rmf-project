# Model Card

## Model Overview

| Field | Details |
|---|---|
| Model Name | EugAI v1.0 |
| Model Type | Large Language Model with Retrieval Augmented Generation |
| Deployment Context | Customer service chatbot |
| Organisation | EugTech Solutions Ltd |
| Version | 1.0 |
| Status | Simulated portfolio project |

## Intended Use

EugAI is intended to support first-line customer service queries for EugTech Solutions Ltd clients.

The system is designed to:

- Answer product and service questions
- Troubleshoot common issues
- Route complex queries to human agents
- Provide general support information from an approved knowledge base

## Out-of-Scope Use

EugAI must not be used for:

- Medical advice
- Legal advice
- Financial advice
- Employment decisions
- Credit decisions
- High-impact automated decision-making
- Processing sensitive personal data without approval

## Model Technology

EugAI uses a GPT-4 class large language model accessed through a third-party API.

A Retrieval Augmented Generation layer is used to retrieve information from EugTech's approved internal knowledge base before generating responses.

## Training and Knowledge Sources

| Data Source | Use |
|---|---|
| Third-party base model training data | General language understanding |
| EugTech product documentation | Customer support knowledge |
| Anonymised historical support tickets | Common troubleshooting patterns |
| Public technical documentation | General product support context |

No client personal data is intentionally used in training data, system prompts, or RAG knowledge sources.

## Evaluation Results

| Evaluation Area | Result |
|---|---|
| Factual accuracy | 96.2% on internal test set |
| Bias assessment | Pass. All demographic variants within 8% of baseline |
| Red team testing | 5 findings identified |
| High severity findings | 2 |
| Medium/low findings | 3 |
| Human escalation | Required for sensitive or low-confidence responses |

## Known Limitations

EugAI has the following limitations:

- It may hallucinate features that do not exist
- It may provide outdated information if the knowledge base is not current
- It may struggle with highly technical multi-step queries
- It cannot understand images, audio, or uploaded documents
- It may be vulnerable to prompt injection if guardrails fail
- It requires human oversight for sensitive or high-impact topics

## Ethical Considerations

EugAI must operate according to the following ethical requirements:

- Users must be told they are interacting with AI
- EugAI must not deny that it is an AI system
- Human support must remain available
- AI outputs must be monitored for bias, hallucination, and unsafe responses
- The system must not make final decisions affecting customer rights or access to services

## Monitoring Requirements

| Monitoring Area | Frequency |
|---|---|
| Performance review | Monthly |
| Bias assessment | Quarterly |
| Knowledge base review | Monthly |
| Red team testing | Annually |
| Full system review | Annually |

## Status

Status: Implemented  
Framework mapping: NIST AI RMF GOVERN 1.7  
Project: NIST AI RMF 1.0 Portfolio Project