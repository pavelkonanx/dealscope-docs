# Install DealScope in Salesforce

This page rewrites the current public installation guidance from the DealScope trial page into a cleaner setup flow.

## Before You Start

The public trial page says DealScope currently works with:

- Professional Edition
- Enterprise Edition
- Unlimited Edition
- Developer Edition
- Scratch Orgs for development and testing

The same page says Starter Suite is not fully supported because of Salesforce limitations around API access, customization, and Lightning component support.

## Choose the Right Install Path

Use the public install page:

- [DealScope trial and install page](https://dscopeai.com/start-trial)

Public guidance on the site:

- use the `Sandbox` install link for sandbox orgs
- use the `Production` install link for Developer Edition orgs
- use the `Production` install link for Scratch Orgs

## Recommended Rollout Pattern

The public site recommends a simple first rollout:

1. Start in a sandbox.
2. Try one object first.
3. Add the panel to a single record page.
4. Review the output with a small pilot group.
5. Expand after the workflow is validated.

## Setup Steps

The public trial page currently shows this sequence:

1. Install the package in Salesforce.
2. Install for admins only.
3. Find the `DealScope_User` permission set.
4. Open `Manage Assignments`.
5. Assign the permission set to the users who need access.
6. Use `No expiration date` if that matches your policy.
7. Open an Opportunity page in Salesforce.
8. Click the gear icon and choose `Edit Page`.
9. Add the `aiSummaryPanel` component to the Lightning Record Page.
10. Save the page.

The same page says:

- the page must be a Lightning Record Page
- adding DealScope to a Lead page works the same way

## Account Page Note

The public site clearly shows Account support, but the current install walkthrough explicitly demonstrates Opportunity and says Lead is the same.

`TODO`: add explicit Account page placement steps when the public site publishes them.

## Trial Note

At the time of writing, the public trial page says the trial includes:

- 1,000 AI summaries
- no time limit

Verify this on the public site before relying on it operationally.

## Related Docs

- [Overview](./overview.md)
- [Supported objects](./objects-supported.md)
- [FAQ](./faq.md)
