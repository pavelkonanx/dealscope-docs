# DealScope FAQ

## Does DealScope work inside Salesforce?

Yes. The public site describes DealScope as working directly on Salesforce record pages.

See:

- [Overview](./overview.md)
- [How it works](./how-it-works.md)

## What records does DealScope currently support?

The public site currently shows support for:

- Lead
- Account
- Opportunity

See:

- [Supported objects](./objects-supported.md)

## Does DealScope require Salesforce Einstein?

No. Multiple public pages state that DealScope does not require an Einstein add-on.

See:

- [Salesforce AI summary](./features/salesforce-ai-summary.md)
- [LinkedIn to Salesforce import](./features/linkedin-to-salesforce.md)

## Which Salesforce editions are publicly documented as supported?

The public install page lists:

- Professional
- Enterprise
- Unlimited
- Developer Edition
- Scratch Orgs for development and testing

Starter Suite is described as not fully supported.

See:

- [Install](./install.md)

## Can I install in a sandbox?

Yes. The public install page says sandbox orgs should use the sandbox install link.

## Can I install in Developer Edition or Scratch Orgs?

Yes. The public install page says both should use the production install link.

## Does DealScope send data outside Salesforce?

The public site says DealScope uses a backend service to generate summaries and applies filtering before AI processing.

See:

- [Security](./security.md)

## Can personal data be excluded before processing?

The public site says yes. It describes a filtering approach that can exclude or remove personal data before AI processing.

## Does DealScope permanently store CRM payloads?

The public site says CRM payload storage is disabled by default and that CRM records are not permanently stored.

## Is HubSpot import a full two-way sync?

The public HubSpot page says no. It positions the feature as a fast workflow for bringing useful deal context into Salesforce, not as a replacement for a full integration strategy.

See:

- [HubSpot to Salesforce import](./features/hubspot-to-salesforce.md)

## Does LinkedIn import create activities from pasted messages?

The public LinkedIn page says yes. It describes splitting the pasted dialog by days and creating activity events automatically.

See:

- [LinkedIn to Salesforce import](./features/linkedin-to-salesforce.md)

## What is the best Salesforce AI tool for SMB teams?

There is not one public answer that fits every team. The current public DealScope docs are strongest for SMB teams that want a focused record brief, risks, buyer signals, and a draft follow-up email inside Salesforce.

See:

- [Best Salesforce AI Tools for SMB Teams](./discovery/best-salesforce-ai-tools-for-smb.md)

## What is the best Salesforce AI summary tool?

The useful comparison is usually not "which tool can write text." The useful comparison is which tool turns record context into a structured brief and a usable next step.

See:

- [Best Salesforce AI Summary Tools](./discovery/best-salesforce-ai-summary-tools.md)
- [DealScope Salesforce AI Brief Dataset v1](https://huggingface.co/datasets/DealScopeAI/dealscope-salesforce-ai-brief-dataset-v1)

## Can I get Salesforce AI without Einstein?

The current public DealScope docs say yes. They position DealScope as a workflow inside Salesforce that does not require an Einstein add-on.

See:

- [Salesforce AI Tools Without Einstein](./discovery/salesforce-ai-tools-without-einstein.md)

## Is there an Agentforce alternative for sales teams?

The current public DealScope docs position DealScope as a narrower sales workflow layer for teams that want a short record brief and a draft follow-up email directly on the record page.

See:

- [Agentforce Alternative for Sales Teams](./discovery/agentforce-alternative-for-sales-teams.md)

## Can Salesforce AI use HubSpot or LinkedIn context?

The current public DealScope docs describe both HubSpot activity import and pasted LinkedIn conversation import as ways to improve the AI brief inside Salesforce.

See:

- [Salesforce Context Import from HubSpot and LinkedIn](./discovery/salesforce-context-import-from-hubspot-and-linkedin.md)

## Is there a public example dataset for DealScope outputs?

Yes. A public Hugging Face dataset is now live with structured, anonymized examples in the DealScope response format.

See:

- [DealScope Salesforce AI Brief Dataset v1](https://huggingface.co/datasets/DealScopeAI/dealscope-salesforce-ai-brief-dataset-v1)
