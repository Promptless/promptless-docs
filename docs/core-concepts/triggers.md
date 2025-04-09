---
sidebar_position: 0
---

# Triggers

Triggers are events that tell Promptless that there might be a documentation update that is warranted. Promptless supports multiple trigger types to fit seamlessly into your team's workflow -- it is designed to minimize the friction of creating and updating documentation.

## Supported Triggers

### GitHub Pull Requests

When configured, Promptless automatically runs whenever a new pull request is opened in your specified source repositories. If there are any changes in the PR that might impact the documentation, Promptless will suggest documentation updates. By default, these suggestions will be available in the Promptless dashboard for review. If auto-publish is enabled for your project, Promptless will automatically create a new PR with the suggested documentation changes and link to it in a comment on the original PR. If there are no changes to the documentation, Promptless will leave a comment indicating that no documentation updates were necessary.

During the review process, if you need additional changes or have specific requests for the documentation updates, you can use the follow-on request feature. This allows you to provide additional instructions or feedback to Promptless, which will then process your request and suggest updated changes based on your input.

### Slack Integration

When configured, Promptless can be triggered from Slack channels to find documentation updates that may be warranted from a thread. Primarily, this is used in Slack Connect support channels with customers -- where in a thread, a customer asks a question about your product, your team has answered it, and when Promptless is triggered, it suggests documentation updates based on the content of the thread. This is particularly useful if you notice a common question that you think should be answered in the docs. 

Promptless can be triggered directly from Slack in two ways:

1. **Message Action**: Use the Promptless message shortcut on any Slack message to trigger documentation analysis
2. **Mentions**: Tag Promptless in a channel to request documentation updates

### Intercom Integration

When configured, Promptless monitors your Intercom conversations for potential documentation updates. This integration helps identify common questions or issues that arise in customer conversations, automatically suggesting documentation improvements to better serve your users. Promptless analyzes the conversation content to determine if any documentation updates or additions would be beneficial.

Promptless is automatically triggered in Intercom in two ways:

1. **Conversation Close**: When a conversation with a customer is closed, Promptless analyzes the conversation for potential documentation updates
2. **Note Added**: When a team member adds a note to a conversation, Promptless reviews the context for documentation opportunities

### Follow-up Instructions

When reviewing any Promptless suggestion in the web app, you can provide follow-up instructions to refine or modify the suggested documentation updates. This feature (currently in beta) allows you to give additional context, request specific changes, or provide feedback that Promptless will use to generate updated documentation suggestions. You'll find this option directly in the suggestion review interface.

Promptless regularly adds new trigger types. If you need a specific trigger that isn't currently supported, please contact us at [help@gopromptless.ai](mailto:help@gopromptless.ai).