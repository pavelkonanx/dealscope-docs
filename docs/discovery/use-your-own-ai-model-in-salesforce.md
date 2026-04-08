# Use Your Own AI Model in Salesforce

This page documents the current public DealScope guide for bring-your-own-model questions in Salesforce.

## What Teams Usually Mean by This Query

The guide does not treat this as a generic architecture question.

It frames the query more narrowly:

- the team wants to stay inside Salesforce
- the model call should go to an endpoint they already control or pay for
- the real implementation problem is request compatibility, not only credentials

## What the Current Public Guide Highlights

The guide says the first failure point is often the request shape.

The practical issues it calls out are:

- extra parameters
- provider-specific fields
- payload formats external model endpoints do not accept as-is

## Recommended Pattern

The current public guide recommends a narrower and more reliable pattern:

- Salesforce to proxy
- proxy to model endpoint

That keeps provider-specific request cleanup out of the Salesforce layer itself.

## Where DealScope Fits

The guide positions DealScope as the narrower option when the real goal is not custom model architecture, but record-level understanding and follow-up support inside Salesforce.

## Related Docs

- [Does Salesforce AI Send Data to OpenAI?](./does-salesforce-ai-send-data-to-openai.md)
- [Salesforce AI Tools Without Einstein](./salesforce-ai-tools-without-einstein.md)
- [AI Follow-Up Email for Salesforce](../features/ai-follow-up-email.md)
