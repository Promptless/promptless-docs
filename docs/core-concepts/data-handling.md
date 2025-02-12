# Data Handling in Promptless

Promptless is designed with data minimization in mind, ensuring that we only store what's necessary to provide our documentation automation service. This page explains how we handle your data when you use Promptless.

## What Promptless Stores

Promptless maintains only one type of customer data:
- **Documentation copies**: We store copies of your documentation to enable our automation features and track changes.

## How We Handle Integration Data

When you connect Promptless to your tools (like GitHub, Slack, Linear, or other integrations), we:

- **Do not store** any data from these integrations
- **Only use** these integrations for two purposes:
  1. Triggers: To detect when documentation updates might be needed
  2. Context: To inform and improve documentation updates

For example:
- When a GitHub PR triggers a documentation check, we analyze the changes in real-time without storing the PR content
- When using Slack integration, we process conversations to identify documentation needs but don't maintain copies of the conversations
- When accessing context from tools like Linear or Jira, we only use the information to inform documentation updates at the time of generation

## Data Privacy and Security

For detailed information about our data handling practices, security measures, and compliance standards, you can refer to our [Privacy Policy](https://gopromptless.ai/privacy). We've designed our system to be transparent and respectful of your data privacy while delivering effective documentation automation.

## Questions About Data Handling?

If you have specific questions about how we handle data or need more information, please contact us at help@gopromptless.ai.