---
sidebar_position: 7
---

# Webflow Integration

Promptless offers integration with Webflow, allowing you to automatically update content in your Webflow collections when triggered by changes in your codebase or other integrated systems.

## Overview

The Webflow integration enables you to:
- Connect to your Webflow sites and collections
- Automatically update content in selected collections
- Support multiple collections within a single project
- Maintain metadata and content structure

## Setup

To set up the Webflow integration:

1. Navigate to the **Integrations** page in your Promptless dashboard
2. Click on **Connect** next to Webflow
3. Authenticate with your Webflow account
4. Grant Promptless the necessary permissions to access your sites and collections

## Creating a Webflow Project

After connecting your Webflow account, you can create a new project that publishes to Webflow:

1. Go to the **Projects** page and click **Create New Project**
2. Select your trigger source (GitHub, Bitbucket, Slack, etc.)
3. For the documentation location, select **Webflow**
4. Choose the Webflow site you want to publish to
5. Select one or more collections where content should be published
6. Configure any additional settings and save your project

## Multiple Collection Support

A unique feature of the Webflow integration is the ability to publish to multiple collections simultaneously. This is useful when your documentation spans different content types or sections in Webflow.

When setting up or editing a project, you can:
- Select multiple collections from the dropdown menu
- Manage all selected collections as part of a single documentation pipeline
- Promptless will intelligently route content to the appropriate collection based on the content structure

## Content Structure

When Promptless publishes to Webflow, it maintains the following structure:

- **Metadata**: Field data from your Webflow items is preserved in HTML comments at the top of each file
- **Body Content**: The main content is stored in the body field of your Webflow items
- **Images**: Any images included in your documentation are properly embedded in the Webflow content

## Limitations

The Webflow integration is currently in beta, with the following limitations:

- Content is published as HTML rather than using Webflow's visual editor
- Some complex Webflow elements may require manual adjustment after publishing
- Custom fields must be properly configured in your Webflow collections

## Troubleshooting

If you encounter issues with the Webflow integration:

- Verify that your Webflow authentication is current
- Check that you've selected the correct site and collections
- Ensure your Webflow collections have the necessary fields for your content
- Contact support at help@gopromptless.ai for assistance

For more information about using Webflow with Promptless, please contact our support team.