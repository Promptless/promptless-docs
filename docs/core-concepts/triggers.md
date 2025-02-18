---
sidebar_position: 0
---

# Triggers

Triggers are events that tell Promptless that there might be a documentation update that is warranted. Promptless supports multiple trigger types to fit seamlessly into your team's workflow -- it is designed to minimize the friction of creating and updating documentation.

## Supported Triggers

### GitHub Pull Requests

When configured, Promptless automatically runs whenever a new pull request is opened in your specified source repositories. If there are any changes in the PR that might impact the documentation, Promptless will suggest documentation updates in a separate PR, and link to it with a comment on the original PR. If there are no changes to the documentation, Promptless leave a comment that it didn't find any changes to the documentation.

### Slack Integration

When configured, Promptless can be triggered from Slack channels to find documentation updates that may be warranted from a thread. Primarily, this is used in Slack Connect support channels with customers -- where in a thread, a customer asks a question about your product, your team has answered it, and when Promptless is triggered, it suggests documentation updates based on the content of the thread. This is particularly useful if you notice a common question that you think should be answered in the docs. 

Promptless can be triggered directly from Slack in two ways:

1. **Message Action**: Use the Promptless message shortcut on any Slack message to trigger documentation analysis
2. **Mentions**: Tag Promptless in a channel to request documentation updates

### Demo Documentation Scraping

Promptless can analyze and process documentation from external websites through its demo scraping feature. This allows you to:

1. Input any website URL containing documentation
2. Automatically scrape and clean the documentation content
3. Process the content for analysis and integration

This feature is particularly useful when:
- Evaluating Promptless with your existing documentation
- Analyzing documentation structure and content
- Testing documentation improvements

The demo scraping feature requires authentication and can be accessed through the Promptless dashboard.

Promptless regularly adds new trigger types. If you need a specific trigger that isn't currently supported, please contact us at [help@gopromptless.ai](mailto:help@gopromptless.ai).