# Organization Management

Organizations in Promptless provide a way to manage teams, users, and access controls. This guide covers the key aspects of organization management and configuration.

## Organization Settings

The Organization Settings page provides administrators with comprehensive control over their organization's configuration and user management.

### Domain-Based Join Policies

Organization administrators can configure how new users join their organization through domain-based policies:

- **Automatic Join**: Administrators can enable automatic organization joining for users with pre-approved email domains
- **Domain Verification**: Add new email domains to a list of verified domains
- **Domain Selection**: Choose from email domains currently used by existing organization members

#### Setting Up Domain-Based Join

1. Navigate to the Organization Settings page
2. Locate the "Join Policies" section
3. Enable "Domain-Based Join"
4. Add verified domains from the list of existing user domains
5. Save your changes

Once configured, new users who sign up with an email address matching any of the verified domains will automatically become members of your organization.

### Manual User Management

For organizations that prefer manual user management or need to add users with non-verified domains:

- Send individual invitations to users
- Review pending join requests
- Manage existing member permissions

## Best Practices

- Regularly review and update your domain list
- Maintain a list of approved domains that match your organization's security requirements
- Consider combining domain-based and manual approaches for maximum flexibility

## Security Considerations

- Only add domains that are explicitly controlled by your organization
- Regularly audit the list of verified domains
- Monitor automatic joins through domain verification

For additional support or questions about organization management, contact help@gopromptless.ai.