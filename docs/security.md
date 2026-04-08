# DealScope Security Notes

This page documents public-facing security statements from `dscopeai.com`. It is not a substitute for a security review, DPA, or vendor questionnaire.

## Public Security Positioning

The current public site says DealScope is built to minimize data sent to the backend and avoid transmitting personal data where possible.

## Data Handling Statements on the Public Site

The public pages state that:

- last names are not transmitted
- emails and phone numbers are not transmitted
- stakeholder processing can use role-based identifiers instead of names
- personal data can be excluded before processing
- a filtering layer removes personal data such as email addresses, phone numbers, names when possible, and other sensitive fields before AI processing
- filtered values are restored locally inside Salesforce after the AI response is merged back

## Processing and Storage Statements

The public pages also state that:

- DealScope uses a backend service to generate summaries
- encrypted transport uses TLS
- org-level tenant separation is used
- access is controlled through secure credentials
- minimal operational logs are stored for reliability
- CRM payload storage is disabled by default
- the backend does not permanently store CRM records
- future versions may support configurable field allowlists and redaction rules

## What Is Not Publicly Documented

The current public site does not clearly document:

- retention windows
- encryption at rest details
- certification status
- subprocessor list
- customer-managed key options

`TODO`: add these only when they are published publicly.

## Related Docs

- [Install](./install.md)
- [FAQ](./faq.md)
