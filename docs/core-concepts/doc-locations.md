---
sidebar_position: 2
---

# Docs Locations

Most often, no matter which hosting provider (Readme, Mintlify, Docusaurus) you use, as long as your docs are sync-ed to github, all you need is to install the Promptless Github App.

We also offer beta support for additional CMS platforms including:
- Zendesk
- Intercom
- Pylon
- Webflow

## Intercom Integration

When using Intercom integration, Promptless supports article ID tracking in filenames. Articles synced from Intercom will include the article ID in the filename format (e.g., `123-article-title.html`). This allows Promptless to accurately track and update specific articles even if their titles change.

When syncing back to Intercom, Promptless will:
- Extract the article ID from the filename if present
- Use this ID to update the correct article in Intercom
- Maintain the connection between your local files and Intercom articles

This feature ensures more reliable synchronization between your documentation repository and Intercom Help Center.

Promptless is flexible and can integrate with any CMS platform that provides an API. If you're using a different CMS and would like to integrate it with Promptless, please contact us at hello@gopromptless.ai to discuss adding support for your CMS platform.