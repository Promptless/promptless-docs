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

## Documentation Update Tracking

When a trigger is activated, Promptless creates and maintains a detailed record of the documentation update process. Each documentation update run tracks:

- The type and source of the trigger (GitHub PR, Slack message, etc.)
- The current status of the update process
- Whether any documentation updates were identified
- A summary of the trigger context
- The final response and any actions taken

This tracking system ensures transparency in the documentation update process and helps maintain a history of how your documentation evolves over time.

Promptless regularly adds new trigger types. If you need a specific trigger that isn't currently supported, please contact us at [help@gopromptless.ai](mailto:help@gopromptless.ai).