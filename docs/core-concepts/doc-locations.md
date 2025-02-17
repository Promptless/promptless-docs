---
sidebar_position: 2
---

# Docs Locations

Promptless supports multiple documentation hosting platforms through its Github App integration. The primary method of connecting documentation is by syncing with Github repositories, which works with popular hosting providers like Readme, Mintlify, and Docusaurus.

## Github-Synced Documentation

When you connect your documentation through Github:
1. Install the Promptless Github App and grant access to your documentation repository
2. When creating a project, specify:
   - The repository containing your documentation
   - The directory within the repository (if your docs aren't in the root)
3. Promptless will analyze your documentation to understand its structure
   - You'll see an "In Progress" status during initial analysis
   - Once complete, the status will update to "Complete"
   - If multiple projects use the same documentation location, Promptless will reuse the analysis results

## Additional CMS Platforms

We also offer beta support for additional content management systems:
- Zendesk
- Intercom
- Pylon

Each platform has its own setup process and may require additional configuration. Contact us at hello@gopromptless.ai to learn more about using Promptless with these platforms.