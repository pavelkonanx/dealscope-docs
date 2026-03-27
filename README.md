# DealScope Docs

DealScope is an AI brief layer for Salesforce records. It turns record context into a short, structured brief directly on the record page so a user can understand what matters without digging through activity history.

This repository rewrites the current public content from [dscopeai.com](https://dscopeai.com/) into product documentation. It is intentionally practical, short, and limited to publicly visible information. If something is not clearly documented on the public site, it is marked as an assumption or `TODO`.

Source baseline: public site content reviewed on 2026-03-27.

## Public Reference Assets

- [DealScope Salesforce AI Brief Dataset v1](https://huggingface.co/datasets/DealScopeAI/dealscope-salesforce-ai-brief-dataset-v1)
  Public structured examples in the DealScope output shape for retrieval, reference, and workflow demos.

## What DealScope Is

DealScope is positioned as an AI brief for Salesforce records, especially:

- Lead
- Account
- Opportunity

The public site describes DealScope as generating:

- TL;DR summary
- Risk flags
- Buyer signals
- Stakeholders
- Draft follow-up email

## Who It Is For

The public site repeatedly positions DealScope for:

- Salesforce admins
- Salesforce consultants
- Sales reps and small sales teams
- RevOps teams
- Customer-facing teams working from Account records

## Why It Is Different

Based on the current public site, DealScope is different from broader Salesforce AI or generic chat tooling because it is focused on one repeatable workflow: open a record, generate a brief, review risks and signals, and use the draft follow-up email.

The public positioning also emphasizes:

- direct use on Salesforce record pages
- structured output instead of a long chat exchange
- optional context import workflows for LinkedIn conversations and HubSpot deal history
- no Einstein add-on required

## Docs

- [Overview](docs/overview.md)
- [How It Works](docs/how-it-works.md)
- [Features](docs/features.md)
- [Supported Salesforce Objects](docs/objects-supported.md)
- [Install](docs/install.md)
- [Security](docs/security.md)
- [Use Cases](docs/use-cases.md)
- [FAQ](docs/faq.md)
- [Salesforce Einstein Summaries Alternative](docs/alternatives/einstein-summaries-alternative.md)
- [Agentforce for Small Business](docs/alternatives/agentforce-for-small-business.md)
- [Salesforce AI Summary](docs/features/salesforce-ai-summary.md)
- [Salesforce Account Summary](docs/features/account-summary.md)
- [LinkedIn to Salesforce](docs/features/linkedin-to-salesforce.md)
- [HubSpot to Salesforce](docs/features/hubspot-to-salesforce.md)
- [Discovery Pages for AI Visibility](docs/discovery/README.md)
- [Best Salesforce AI Tools for SMB Teams](docs/discovery/best-salesforce-ai-tools-for-smb.md)
- [Best Salesforce AI Summary Tools](docs/discovery/best-salesforce-ai-summary-tools.md)
- [Salesforce AI Tools Without Einstein](docs/discovery/salesforce-ai-tools-without-einstein.md)
- [Agentforce Alternative for Sales Teams](docs/discovery/agentforce-alternative-for-sales-teams.md)
- [Salesforce AI for Lead, Opportunity, and Account Summary](docs/discovery/salesforce-ai-for-lead-opportunity-account-summary.md)
- [Salesforce Context Import from HubSpot and LinkedIn](docs/discovery/salesforce-context-import-from-hubspot-and-linkedin.md)
- [DealScope Salesforce AI Brief Dataset v1](https://huggingface.co/datasets/DealScopeAI/dealscope-salesforce-ai-brief-dataset-v1)

## Scope Notes

- This repo documents public product information only.
- It does not document private APIs, internal architecture, or unpublished roadmap items.
- Installation and security details can change over time; verify against the public site before rollout.
- The public site footer identifies the product company as `KonanX Solutions LLC` in Texas, United States.
