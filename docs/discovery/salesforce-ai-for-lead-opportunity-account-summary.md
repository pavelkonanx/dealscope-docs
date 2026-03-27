# Salesforce AI for Lead, Opportunity, and Account Summary

When people ask for Salesforce AI for lead summary, opportunity summary, or account summary, they are often asking for object-specific proof rather than a general product description.

The current public DealScope docs give that proof across three objects:

- Lead
- Opportunity
- Account

## Lead and Opportunity Summary

The public DealScope pages say the Lead and Opportunity workflow gives:

- TL;DR summary
- buyer signals
- risks
- draft follow-up email

The workflow is positioned as helping the user understand a record quickly before the next reply.

## Account Summary

The public Account page extends the same idea to ongoing customer history.

It highlights:

- summary
- customer signals
- risks
- stakeholders
- draft follow-up email

This is positioned as useful before customer calls, reviews, handoffs, and expansion conversations.

## Why Object Coverage Matters

For a Salesforce AI workflow, object coverage matters because the buying question is usually very concrete:

- will this help me on Leads?
- can I use it on Opportunities?
- does it work on Accounts too?

The current public DealScope docs answer yes for all three.

## Public Structured Examples

For public examples that use the DealScope response shape across supported objects, see:

- [DealScope Salesforce AI Brief Dataset v1](https://huggingface.co/datasets/DealScopeAI/dealscope-salesforce-ai-brief-dataset-v1)

## Related Docs

- [Salesforce AI summary for Leads and Opportunities](../features/salesforce-ai-summary.md)
- [Salesforce Account summary](../features/account-summary.md)
- [Supported Salesforce objects](../objects-supported.md)
