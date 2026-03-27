# How DealScope Works in Salesforce

The public site describes DealScope as a simple record workflow.

## Core Flow

1. Open a supported Salesforce record.
2. Use the DealScope panel on the record page.
3. Click `Generate`.
4. DealScope analyzes the record context that is available to it, including activity, emails, and notes.
5. DealScope returns a structured brief and a draft follow-up email.

## What the User Sees

After generation, the user sees:

- a short summary
- risk flags
- buyer signals
- stakeholders
- a draft follow-up email

The public site positions this as a workflow for quick understanding, handoff, and follow-up rather than open-ended chat.

## Optional Context Import Workflows

Some public pages also describe add-on workflows for missing context:

- [LinkedIn to Salesforce import](./features/linkedin-to-salesforce.md)
- [HubSpot to Salesforce activity import](./features/hubspot-to-salesforce.md)

These pages describe ways to bring external communication into the record so the AI brief has better source context.

## Notes

- The public site explicitly describes the base `Generate` workflow for Leads and Opportunities.
- Account support is shown on the main site and account-specific page.
- `TODO`: add more object-specific workflow detail if the public site later publishes separate step-by-step pages for each object.
