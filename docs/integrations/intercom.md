---
sidebar_position: 3
---

# Intercom Integration

Promptless offers integration with Intercom to help you maintain accurate and up-to-date documentation in your Intercom Help Center. This integration allows Promptless to monitor your Intercom articles, analyze their content, and suggest updates when relevant changes are detected in your codebase or support conversations.

## Overview

The Intercom integration enables Promptless to:

- Sync your Intercom Help Center articles into the Promptless system
- Maintain article metadata including article IDs and parent-child relationships
- Process HTML content from Intercom articles
- Generate appropriate documentation update suggestions based on triggers

## Setup Requirements

To use the Intercom integration with Promptless, you'll need:

1. A Promptless account with admin access
2. An Intercom account with access to your Help Center
3. API credentials for your Intercom workspace

## Configuration Steps

1. **Contact Promptless Support**: Since Intercom integration is currently in beta, reach out to us at help@gopromptless.ai to enable this feature for your account.

2. **Provide API Access**: You'll need to provide Promptless with API access to your Intercom workspace. Our team will guide you through this process.

3. **Configure in Dashboard**: Once enabled, you can configure the Intercom integration in your Promptless dashboard:
   - Navigate to the Integrations section
   - Select Intercom from the available doc locations
   - Enter your API credentials and select which Help Center collections to sync

4. **Create a Project**: Create a new project in Promptless that uses your Intercom Help Center as the documentation source.

## How It Works

When configured, Promptless will:

1. Periodically sync your Intercom articles to maintain an up-to-date representation of your Help Center
2. Store article content and metadata including article IDs and hierarchical relationships
3. Process the HTML content of your articles for analysis
4. When triggers (like code changes or support conversations) indicate potential documentation needs, Promptless will suggest updates to your Intercom articles

## Limitations

As this integration is in beta, please note the following limitations:

- Complex HTML formatting may not be fully preserved in update suggestions
- Article permissions and visibility settings are not currently managed by Promptless
- Updates must be manually applied in your Intercom Help Center

## Getting Help

If you encounter any issues with the Intercom integration or have questions about its capabilities, please contact our support team at help@gopromptless.ai.