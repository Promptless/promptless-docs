# Intercom Integration

Promptless offers beta support for Intercom integration, allowing you to automatically update and maintain your Intercom help center documentation. This guide walks you through setting up and using the Intercom integration with Promptless.

## Prerequisites

Before setting up the Intercom integration, ensure you have:
- A Promptless account
- Admin access to your Intercom workspace
- GitHub repository configured with Promptless

## Setup Process

1. **Enable Intercom Integration**
   - Log in to your Promptless dashboard
   - Navigate to Integrations settings
   - Select "Add New Integration"
   - Choose Intercom from the available platforms

2. **Configure Authentication**
   - Generate an Intercom Access Token from your Intercom Developer Hub
   - Add the access token to your Promptless configuration
   - Select the Intercom workspace you want to connect

3. **Link Help Center**
   - Choose which Intercom Help Center collections to sync
   - Map your documentation structure
   - Configure update preferences

## Usage

Once configured, Promptless will:
- Monitor your configured triggers (GitHub PRs, Slack conversations)
- Suggest updates to your Intercom help center articles
- Create documentation update PRs when necessary
- Maintain sync between your primary documentation and Intercom content

## Limitations

As this integration is in beta:
- Some advanced features might be limited
- Changes are reviewed before being pushed to Intercom
- Custom HTML widgets and complex layouts might require manual adjustment

## Support

For questions or issues with the Intercom integration:
- Contact our support team at help@gopromptless.ai
- Mention specific Intercom-related concerns
- Provide your workspace ID for faster assistance

## Best Practices

1. **Regular Sync Checks**
   - Monitor the sync status in your dashboard
   - Review suggested updates promptly
   - Keep your access tokens up to date

2. **Content Structure**
   - Maintain consistent formatting across platforms
   - Use standard Markdown where possible
   - Document custom implementations

3. **Version Control**
   - Keep track of major content changes
   - Use descriptive commit messages
   - Review automated updates regularly

## Future Updates

As we continue to develop the Intercom integration, we'll add:
- Enhanced formatting support
- Direct preview capabilities
- Advanced synchronization options

Stay updated on new features by following our release notes and announcements.