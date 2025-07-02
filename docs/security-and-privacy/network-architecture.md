---
sidebar_position: 1
---

# Network Architecture

Promptless utilizes a secure, modern cloud-based network architecture designed for reliability, security, and scalability. Our infrastructure is built on industry-leading cloud platforms with multiple layers of security controls and redundancy.

## Infrastructure Overview

<img src="https://promptless-customer-doc-assets.s3.amazonaws.com/docs-images/org_2lvkgU9erOFxYhtEVVC0ymPrPdF/a84d7359-fce9-4362-96c8-1c7973da3ce1-current_agent_workflow_architecture.png" alt="Current Agent Workflow Architecture" style={{width:"800px", display: "block", margin: "0 auto", boxShadow: "0 4px 8px rgba(0, 0, 0, 0.1)", marginBottom: "20px"}} />


Our infrastructure is designed with the following key principles:
- Security by design at every layer
- High availability and fault tolerance
- Scalability and performance optimization
- Comprehensive monitoring and observability

## Key Security Measures

While we can't highlight all of Promptless's security measures here, we've highlighted some of the key ones below:
* Data encryption in transit: All data at rest is encrypted using TLS 1.2 or later.
* Data encryption at rest: Data stored in Promptless's database is encrypted with AES-256.
* Data access controls: We use a combination of access controls, including role-based access control (RBAC), to ensure that only authorized users have access to sensitive data.
* Principle of least privilege: We only give users the minimum permissions they need for their role.
* Logical separation of data: All data is tagged with customer identifiers, to ensure multiple layers of logical separation between Promptless users

## Multi-Tenant Security Model

Promptless uses a **strong logical separation** model for multi-tenant data security:

**Organization-Level Isolation**
- Every piece of data (users, suggestions, trigger events, etc.) is tagged with a specific organization ID
- All database queries are automatically scoped to the requesting organization
- Authorization mechanisms prevent cross-organization data access
- No shared data contexts between different customer organizations

Promptless's shared infrastructure provides increased scalability and security, since it reduces the number of infrastructure assets that need to be tracked and maintained and decreases the number of data access points across the system. 

For more detailed information about our network architecture or to discuss specific security requirements, please contact our security team at help@gopromptless.ai.