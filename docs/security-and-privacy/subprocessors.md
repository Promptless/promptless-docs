---
sidebar_position: 2
---

# Promptless Subprocessors

Promptless uses a number of third party services to deliver our services. This page provides high-level information about the subprocessors that Promptless uses to deliver our core docs automation service. For more detailed information about our security practices, data handling procedures, and privacy commitments, please schedule a call with our team by contacting us at help@gopromptless.ai.

## Language Models and AI Infrastructure Providers

Promptless is designed with a model-agnostic architecture, providing flexibility and choice in AI language models used for documentation generation. This approach offers several key advantages:

Model Selection
* Support for multiple leading language models
* Ability to switch between different model providers
* Custom model integration capabilities
* Performance optimization across different model types

### Current Primary Provider: Anthropic

Currently, all LLM requests are processed through **Anthropic**, which provides superior performance for our documentation generation use cases. Key benefits include:

* **No Training Data Usage**: Anthropic guarantees that data sent through their API is not used for model training. [View Anthropic's privacy commitments](https://privacy.anthropic.com/en/articles/7996868-is-my-data-used-for-model-training)
* **Enterprise-grade security**: Robust data protection and privacy controls
* **High-quality output**: Optimized performance for technical documentation tasks

Promptless may be able to provide add-ons that provide additional flexibility:
* Tailored hosted models by cloud providers, such as Anthropic on AWS
* Use of customer-managed model deployments
* Custom model fine-tuning options
* Model performance monitoring and optimization
* Dedicated model resources

**Note:** The Promptless team may recommend certain models for different parts of the documentation process based on output quality considerations for different use-cases, but the final choice of architecture is up to the customer. While we maintain model-agnostic capabilities, Anthropic currently provides the highest quality output for our documentation automation workflows.

**Note:** Regardless of model choice, Promptless does not use customer data for pre-training or fine-tuning language models. 

## Current Subprocessors

### Infrastructure and Hosting
- **Amazon Web Services (AWS)**
  - Primary cloud infrastructure provider
  - Data center locations: Primary is us-east-2, with secondary locations in other US regions
  - Services used: EKS, EC2, S3, RDS (Aurora), Lambda

### Authentication and Security
- **Clerk**: User authentication, SSO, identity management, and security token services
  - **Data Scope**: Only processes user authentication data and account information
  - **No Sensitive Customer Data**: Does not process or store any customer documentation, code, or sensitive business data

### Monitoring and Analytics
- **DataDog**: Infrastructure monitoring, application performance monitoring, log management, and security monitoring
  - **Data Scope**: Only receives system logs and infrastructure metrics
  - **No Sensitive Customer Data**: Does not process GitHub events, documentation content, or any customer-specific data

### Third-party Integrations 

Promptless supports a number of third-party integrations that customers can choose to use in their projects, such as Github, Slack, Intercom, Linear, Notion, Jira, and more. 

For the most current information about our subprocessors or to discuss specific security requirements, please contact our security team at help@gopromptless.ai.