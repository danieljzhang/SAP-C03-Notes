# AWS Certified Solutions Architect - Professional (SAP-C03) Notes

Original study notes for the AWS Certified Solutions Architect - Professional exam, mapped to the SAP-C03 exam guide. Written from a blank page against AWS official documentation, with original practice scenarios. No exam questions or dumps.

## Exam version notice

This repository is mapped to **SAP-C03**. The SAP-C02 repo (SAP-C02-Notes) stays SAP-C02-only and is not changed by this project.

Key dates (per AWS announcement): SAP-C03 registration opened October 27, 2026; SAP-C02 last exam day November 16, 2026; SAP-C03 live November 17, 2026.

## Exam facts

| Item | Detail |
|---|---|
| Exam code | SAP-C03 |
| Questions | 75 (65 scored + 10 unscored) |
| Duration | 180 minutes |
| Passing score | 720 / 1000 (scaled score) |
| Cost | $300 USD |
| Validity | 3 years |

Official exam guide: https://docs.aws.amazon.com/aws-certification/latest/solutions-architect-professional-03/solutions-architect-professional-03.html

## Domains

| Folder | Domain | Weight |
|---|---|---|
| `Domain-1-Cloud-Native/` | Architecture Design and Implementation Built for the Cloud | 25% |
| `Domain-2-Security-Compliance-Governance/` | Security, Compliance, and Governance | 25% |
| `Domain-3-Cost-Optimized/` | Cost-Optimized Architecture Design | 15% |
| `Domain-4-Resilience-Migration-Continuity/` | Resilience, Migration, and Business Continuity | 15% |
| `Domain-5-Operational-Excellence-Automation/` | Operational Excellence and Automation | 20% |

`Cheatsheets/` holds domain cheatsheets and practice scenarios, added later.

## How this repo is built

- `prompts.md` holds the 16 reusable prompt templates (service notes, gap analysis, domain review, cheatsheets, original practice scenarios, repository review, study plan). Each template opens by verifying the current exam code and official exam guide first.
- Round 1 drafting: Amazon Q Developer, from a blank page against AWS official documentation.
- Review before merge: every draft is checked against official AWS documentation before it lands on main.
- New C03 topics are written first (Bedrock AgentCore and agent architectures, Bedrock Guardrails and AgentCore Identity, RAG architectures, VPC Lattice and ECS Service Connect, Step Functions durable workflows, Resilience Hub and Fault Injection Service, Lake Formation + Apache Iceberg lakehouse, Clean Rooms cross-account sharing, KMS post-quantum cryptography (ML-DSA, ML-KEM), IPv6 dual-stack migration), then the carried-over core, domain by domain, each file checked against the C03 guide rather than copied from C02 notes.

## Acknowledgments

Amazon Q Developer for round-1 drafting, and the prompt templates in `prompts.md`.
