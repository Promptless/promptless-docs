# Zendesk Integration

Promptless integrates with Zendesk to analyze support tickets and identify documentation gaps based on customer interactions. This integration enables Promptless to suggest documentation updates based on common support queries and ticket patterns.

## Setup

1. Navigate to your Promptless dashboard
2. Go to the Integrations section
3. Click "Add Integration" and select Zendesk
4. Authenticate with your Zendesk account
5. Configure the following settings:
   - Zendesk subdomain
   - Support groups to monitor
   - Ticket fields to analyze

## Features

- **Ticket Analysis**: Automatically analyzes support tickets to identify documentation gaps
- **Pattern Recognition**: Identifies common customer questions that might indicate missing or unclear documentation
- **Integration with Other Sources**: Combines Zendesk insights with other context sources for comprehensive documentation updates
- **Automated Suggestions**: Generates documentation update suggestions based on support ticket patterns

## Usage

Once configured, Promptless will:
- Monitor incoming support tickets
- Analyze ticket content and resolutions
- Suggest documentation updates when patterns emerge
- Create documentation update PRs when necessary

## Permissions

The Zendesk integration requires the following permissions:
- Read access to tickets
- Read access to ticket fields
- Read access to user profiles

## Support

For additional help with the Zendesk integration, contact help@gopromptless.ai