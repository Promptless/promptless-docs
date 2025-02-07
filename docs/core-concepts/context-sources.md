---
sidebar_position: 1
---

# Context Sources

Context sources are integrations that connect Promptless to your organization's existing tools and data, enabling it to understand and operate within your company's specific context. By leveraging these integrations, Promptless can generate more relevant and accurate documentation updates that align with your team's terminology, workflows, and existing knowledge base.

## Data Privacy

Promptless prioritizes your data privacy and security. We do not store any of your organization's data from these context sources. Instead, our agents query the relevant APIs in real-time when documentation updates are needed, ensuring that we only access the information necessary for the specific documentation task at hand.

## Supported Integrations

### Slack
- **Purpose**: Provides access to support conversations, team discussions, and institutional knowledge
- **Key Benefits**:
  - Analyzes support conversations to identify documentation gaps
  - Understands company-specific terminology and common pain points
  - Enables direct interaction with Promptless through mentions and message actions

### Jira
- **Purpose**: Connects to your project management and issue tracking
- **Key Benefits**:
  - References related tickets when suggesting documentation updates
  - Understands feature context from epics and user stories
  - Maintains alignment between documentation and project status

### Linear
- **Purpose**: Integrates with your product development workflow
- **Key Benefits**:
  - Links documentation updates to relevant issues
  - Understands feature context and implementation details
  - Maintains documentation synchronization with development cycles

## Setting Up Context Sources

1. Navigate to your project settings in the Promptless dashboard
2. Select "Context Sources" from the configuration menu
3. Enable and configure desired integrations:
   - For Slack: Authorize the Promptless app in your workspace
   - For Jira: Provide API credentials and select relevant projects
   - For Linear: Connect your Linear account and select teams

## Examples

Here are some examples of how context sources enhance documentation updates:

```
# Without Context Sources
"Update the authentication documentation"

# With Context Sources
"Update the authentication documentation to clarify the OAuth2 refresh token 
process, which has been a common support topic (see Slack thread #12345). 
This relates to the SSO enhancement project (Jira-123) and addresses the 
reported token expiration issues (Linear-456)."
```

## Additional Context Sources

Need integration with other tools? Contact [help@gopromptless.ai](mailto:help@gopromptless.ai) to request additional context sources. We're continuously expanding our integration options to better serve your documentation needs.