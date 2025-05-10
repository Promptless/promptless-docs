---
sidebar_position: 7
---

# Document360 Integration

**Used for: Context and Publishing**

Promptless integrates with Document360, allowing you to sync and manage your Document360 knowledge base content through the Promptless platform.

## What is Document360?

Document360 is a knowledge base platform that helps organizations create, organize, and share documentation. The integration with Promptless allows you to automatically keep your Document360 documentation up-to-date as your product evolves.

## Setup

To set up the Document360 integration:

1. Navigate to the [integrations page](https://app.gopromptless.ai/integrations) in your Promptless dashboard
2. Click "Connect Document360"
3. Enter your Document360 API token
4. Name your integration (e.g., "Company Knowledge Base")
5. Click "Connect"

:::note
You can find your Document360 API token in your Document360 account settings under API Access. Make sure your API token has the necessary permissions to read and write content.
:::

## How It Works

The Document360 integration works by:

1. **Initial Sync**: When first connected, Promptless creates a local copy of all your Document360 content, preserving the project and category structure
2. **Content Updates**: When Promptless generates documentation updates, it can publish these changes to your Document360 knowledge base
3. **Metadata Preservation**: Promptless maintains all Document360-specific metadata including authors, version numbers, and publication status

## Project Setup

When creating a new project in Promptless:

1. Select Document360 as your documentation platform
2. Choose which Document360 projects you want to include
3. Configure your trigger sources (GitHub, Slack, etc.)
4. Set up auto-publishing preferences if desired

## Content Synchronization

Promptless synchronizes the following elements from your Document360 knowledge base:

- Project versions
- Category structure
- Article content
- Article metadata (authors, publication status, etc.)
- Article URLs and slugs

## Limitations

- Document360 webhooks are not currently supported, so changes made directly in Document360 won't automatically trigger Promptless updates
- Complex custom HTML and JavaScript components in Document360 articles may require manual review

## Need Help?

For any questions or issues with the Document360 integration, please contact our support team at help@gopromptless.ai.