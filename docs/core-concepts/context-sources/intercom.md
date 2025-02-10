# Setting Up Intercom Integration

This guide walks you through the process of connecting your Intercom workspace to Promptless.

## Prerequisites
- A Promptless account
- Admin access to your Intercom workspace

## Setup Steps

1. **Access Your Intercom Settings**
   - Log in to your Intercom workspace
   - Navigate to Settings > Developer Hub
   - Click on "New App"

2. **Configure OAuth Settings**
   - Enable OAuth for your app
   - Add the following redirect URL:
     
   - Under "Permissions", select the following scopes:
     - Read conversations
     - Read and list users and companies
     - Read tickets
     (Note: Additional permissions may be required based on your specific use case)

3. **Connect to Promptless**
   - Go to your Promptless dashboard
   - Navigate to Integrations > Add New
   - Select Intercom from the available integrations
   - Click "Connect with Intercom"
   - Follow the authorization prompt to grant Promptless access to your Intercom workspace

## Verification
After completing the setup, Promptless will:
- Start monitoring your Intercom conversations for documentation gaps
- Allow you to trigger documentation updates directly from Intercom conversations
- Include relevant Intercom context when suggesting documentation updates

## Support
If you need assistance with your Intercom integration, contact us at help@gopromptless.ai.