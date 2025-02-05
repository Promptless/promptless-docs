# Notion Integration

Promptless can integrate with Notion to use your workspace content as a context source, enabling more accurate documentation suggestions based on your organization's knowledge base.

## Prerequisites

- A Promptless account
- Admin access to your Notion workspace
- Notion workspace with the content you want to use as context

## Setup Steps

1. **Create a Notion Integration**
   - Go to [Notion Developers](https://developers.notion.com)
   - Click "View my integrations"
   - Create a new integration
   - Save the Integration Token for later use

2. **Configure Workspace Access**
   - In your Notion workspace, share the pages you want to use with your integration
   - Click "Share" on each page/database
   - Select your integration from the dropdown
   - Grant appropriate access permissions

3. **Connect to Promptless**
   - Log in to your Promptless dashboard
   - Navigate to Settings > Integrations
   - Click "Add Integration"
   - Select "Notion" from the available options
   - Enter your Notion Integration Token
   - Select the pages/databases you want to use as context

## Usage

Once configured, Promptless will automatically:
- Index the content from your connected Notion pages
- Use this content as context when suggesting documentation updates
- Reference relevant Notion pages in documentation suggestions

## Permissions

Promptless requires the following Notion permissions:
- Read access to specified pages and databases
- Read user information for content attribution
- No write permissions are required

## Troubleshooting

If you encounter issues:
1. Verify your Integration Token is correct
2. Check that pages are properly shared with the integration
3. Ensure your Notion workspace is accessible
4. Contact help@gopromptless.ai for additional support

## Additional Resources

- [Notion API Documentation](https://developers.notion.com/docs)
- [Promptless Context Sources Overview](/docs/core-concepts/context-sources)