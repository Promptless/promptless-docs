---
sidebar_position: 7
---

# Webflow Integration

Promptless offers integration with Webflow, allowing you to automatically update your Webflow-hosted documentation when changes occur in your organization.

## Overview

The Webflow integration enables you to:
- Connect to your Webflow sites and collections
- Automatically update content in your Webflow collections
- Select multiple collections for documentation updates
- Maintain consistent documentation across your Webflow sites

## Setup

To set up the Webflow integration:

1. Navigate to the **Integrations** page in your Promptless dashboard
2. Click on **Connect** next to the Webflow integration
3. Authenticate with your Webflow account credentials
4. Grant Promptless the necessary permissions to access your Webflow sites and collections

## Creating a Webflow Documentation Project

After connecting your Webflow account, you can create a new project that publishes to Webflow:

1. Go to the **Projects** page in your Promptless dashboard
2. Click **Create New Project**
3. Select your trigger source (GitHub, Bitbucket, Slack, etc.)
4. For the documentation location, select **Webflow**
5. Choose the Webflow site you want to publish to
6. Select one or more collections where your documentation content will be published
7. Configure any additional settings as needed
8. Click **Create Project**

## Multiple Collection Support

A key feature of the Webflow integration is the ability to select multiple collections for documentation updates. This allows you to:

- Organize your documentation across different collections based on content type
- Update related documentation in multiple collections simultaneously
- Maintain consistent documentation structure across your Webflow site

When creating or editing a project, you can select multiple collections from the dropdown menu in the Webflow configuration section.

## How It Works

When Promptless is triggered to update documentation:

1. It analyzes the trigger content (PR, Slack message, etc.)
2. Determines what documentation needs to be updated
3. Identifies the appropriate Webflow collections for the updates
4. Creates or updates the relevant items in your Webflow collections
5. Preserves metadata and formatting specific to your Webflow setup

## Limitations and Considerations

- The Webflow integration requires appropriate permissions to modify your collections
- Content structure in Webflow should be maintained for optimal results
- Custom fields in your Webflow collections are preserved during updates
- Images from other sources (like Slack) can be incorporated into your Webflow content

## Troubleshooting

If you encounter issues with your Webflow integration:

- Verify your Webflow authentication is current
- Check that you've selected the correct site and collections
- Ensure your Webflow collections have the necessary fields for documentation content
- Contact support at help@gopromptless.ai for assistance

For more information about using Webflow with Promptless, or to request specific features for your Webflow integration, please contact our support team.