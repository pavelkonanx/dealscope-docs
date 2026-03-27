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

