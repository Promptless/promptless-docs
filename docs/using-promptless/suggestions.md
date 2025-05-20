---
sidebar_position: 1
---

# Managing Documentation Suggestions

When Promptless is triggered by events like GitHub pull requests or Slack messages, it generates documentation suggestions that you can review, edit, and publish. This page explains how to work with these suggestions in the Promptless dashboard.

## Viewing Suggestions

All documentation suggestions are available in the [Change History](https://app.gopromptless.ai/change-history) section of the Promptless dashboard. This page displays a table of all suggestions, including:

- **Suggestion**: The title and description of the suggested documentation change
- **Files Changed**: A list of files that have been modified, added, or deleted as part of the suggestion
- **Trigger Events**: The events that triggered this suggestion, such as GitHub pull requests or Slack messages
- **Status**: The current status of the suggestion (pending, published, etc.)

![Suggestions Table](https://promptless-customer-doc-assets.s3.amazonaws.com/docs-images/suggestions-table-example.png)

Each suggestion may be associated with multiple trigger events. For example, a single documentation update might be triggered by both a GitHub pull request and a follow-up Slack conversation.

### Clickable Trigger Events

Trigger events in the Change History page are clickable links that take you directly to the original source:

- GitHub or Bitbucket pull requests open in a new tab to the PR that triggered the suggestion
- Slack messages open to the specific thread where the suggestion was requested
- Zendesk tickets link directly to the support conversation

This feature helps you quickly access the context that led to a documentation suggestion, making it easier to understand why certain changes were recommended.

## Reviewing Suggestion Details

Click on any suggestion in the table to view its details. The suggestion detail page shows:

1. The complete suggestion information, including title and description
2. All files that have been modified, with a diff view showing the changes
3. The trigger events that led to this suggestion
4. Options to publish, edit, or reject the suggestion

## Publishing Suggestions

When you're satisfied with a suggestion, you can publish it directly from the suggestion detail page. Depending on your project configuration, publishing will either:

- Create a pull request in your documentation repository with the suggested changes
- Directly commit the changes to your documentation repository
- Publish the changes to your documentation platform (for integrations like Zendesk or Intercom)

## Editing Suggestions

If a suggestion needs modifications before publishing, you can edit it directly in the Promptless dashboard:

1. Navigate to the suggestion detail page
2. Click the "Edit" button next to any file
3. Make your changes in the editor
4. Save your changes

You can also request additional changes from Promptless using the follow-on request feature, which allows you to provide specific instructions for how the suggestion should be modified.

## Rejecting Suggestions

If a suggestion is not needed, you can reject it:

1. Navigate to the suggestion detail page
2. Click the "Reject" button
3. Optionally, provide a reason for the rejection

Rejected suggestions are removed from your active suggestions list but remain in the system for reference.

## Filtering and Searching Suggestions

The Change History page provides options to filter and search suggestions:

- Filter by status (pending, published, rejected)
- Filter by trigger type (GitHub, Slack, etc.)
- Search by suggestion title or description
- Filter by date range

These filtering options help you manage large numbers of suggestions and find specific items quickly.

## Understanding Suggestion Status

Suggestions can have the following statuses:

- **Pending**: The suggestion has been created but not yet published or rejected
- **Published**: The suggestion has been published to your documentation
- **Rejected**: The suggestion has been reviewed and rejected

## Related Features

- **Auto-publish**: When enabled in your project settings, suggestions will be automatically published without manual review
- **Follow-on Requests**: Request additional changes or refinements to a suggestion
- **Notification Settings**: Configure how you want to be notified about new suggestions