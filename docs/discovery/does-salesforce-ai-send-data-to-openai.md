# Does Salesforce AI Send Data to OpenAI?

This page documents the current public DealScope guide for Salesforce AI privacy and external-model questions.

## The Current Public Answer

The public guide says the useful question is not only whether data is sent.

The more useful question is:

- what exact version of the data reaches the external model
- what Salesforce masking changes first
- what still needs to be verified in the org

## What the Guide Emphasizes

The current public guide highlights Salesforce Trust Layer style masking as the key practical boundary before the model call.

It says that:

- names, emails, and phone numbers can be transformed before they leave the Salesforce side
- the payload seen by the model may differ materially from the raw record

## What Teams Should Still Verify

The current public guidance says teams should still test their own workflow using known sample data.

The guide recommends verifying:

- what the model actually receives
- whether the workflow boundary matches the team's assumptions
- how masking behaves in the actual configuration

## Related Docs

- [Use Your Own AI Model in Salesforce](./use-your-own-ai-model-in-salesforce.md)
- [Security](../security.md)
- [Salesforce AI Tools Without Einstein](./salesforce-ai-tools-without-einstein.md)
