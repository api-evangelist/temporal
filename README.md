# Temporal (temporal)
Temporal is an open-source durable execution platform for building reliable long-running distributed workflows and microservices.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/temporal/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - ProCode_API_Composition, Workflows

## Timestamps

- **Created:** 2026-03-03 
- **Modified:** 2026-04-19 

## APIs

### Temporal Server Frontend API
The Temporal Server Frontend API provides gRPC services for interacting with the Temporal Server, including WorkflowService for managing workflow executions, OperatorService for cluster operations, and HealthService for health checks. Client SDKs and the Temporal CLI use these gRPC services under the hood.

**Human URL:** [https://docs.temporal.io/self-hosted-guide/server-frontend-api-reference](https://docs.temporal.io/self-hosted-guide/server-frontend-api-reference)

#### Tags:

 - Durable Execution, gRPC, Workflows

#### Properties

- [Documentation](https://docs.temporal.io/self-hosted-guide/server-frontend-api-reference)
- [GitHubRepository](https://github.com/temporalio/api)

### Temporal Cloud Ops API
The Temporal Cloud Operations API is an open source, public HTTP API and gRPC API for programmatically managing Temporal Cloud control plane resources, including Namespaces, Users, Service Accounts, API keys, and other infrastructure components.

**Human URL:** [https://docs.temporal.io/ops](https://docs.temporal.io/ops)

#### Tags:

 - Cloud, Operations, Workflows

#### Properties

- [Documentation](https://docs.temporal.io/ops)
- [APIReference](https://saas-api.tmprl.cloud/docs/httpapi.html)
- [GitHubRepository](https://github.com/temporalio/cloud-api)
- [OpenAPI](openapi/cloud-ops-api.yml)

## Common Properties

- [Portal](https://temporal.io/)
- [Documentation](https://docs.temporal.io/)
- [GettingStarted](https://docs.temporal.io/cloud/get-started)
- [Quickstart](https://docs.temporal.io/quickstarts)
- [SDK](https://docs.temporal.io/develop)
- [CLI](https://docs.temporal.io/cli)
- [Pricing](https://temporal.io/pricing)
- [Blog](https://temporal.io/blog)
- [ChangeLog](https://temporal.io/change-log)
- [StatusPage](https://status.temporal.io)
- [Security](https://temporal.io/security)
- [TermsOfService](https://temporal.io/terms-of-service)
- [PrivacyPolicy](https://temporal.io/global-privacy-policy)
- [Login](https://cloud.temporal.io/login)
- [SignUp](https://docs.temporal.io/cloud/get-started)
- [GitHubOrganization](https://github.com/temporalio)
- [Training](https://learn.temporal.io/)

## Features

| Name | Description |
|------|-------------|
| Durable Execution | Automatically persists workflow state and resumes execution after failures, ensuring long-running processes complete reliably. |
| Namespace Management | Create and manage isolated namespaces for organizing workflows with independent retention policies and access controls. |
| User and Access Management | Manage users, service accounts, and API keys for fine-grained access control to Temporal Cloud resources. |
| Multi-Region Deployment | Deploy workflows across multiple cloud regions for low-latency execution and disaster recovery. |
| Workflow Versioning | Safely deploy workflow code changes with built-in versioning that prevents breaking running executions. |
| Visibility and Search | Query and filter workflow executions using custom search attributes for operational visibility and debugging. |
| mTLS Authentication | Secure namespace communication with mutual TLS certificate-based authentication and codec server encryption. |
| Async Operations | Track the status of long-running control plane operations like namespace creation and configuration changes. |

## Use Cases

| Name | Description |
|------|-------------|
| Microservice Orchestration | Coordinate complex multi-service transactions with automatic retries, compensation logic, and timeout handling. |
| Data Pipeline Processing | Build reliable ETL and data processing pipelines that handle failures gracefully and resume from the last checkpoint. |
| Order Fulfillment Workflows | Automate end-to-end order processing including payment, inventory, shipping, and notification steps with guaranteed completion. |
| Infrastructure Provisioning | Orchestrate cloud infrastructure deployment and configuration management with durable state tracking. |
| Subscription and Billing Management | Manage recurring billing cycles, subscription renewals, and payment processing with long-running timer-based workflows. |

## Integrations

| Name | Description |
|------|-------------|
| Go SDK | Native Go client library for building Temporal workflows and activities with full type safety. |
| TypeScript SDK | TypeScript/JavaScript SDK for building Temporal workflows in Node.js with async/await patterns. |
| Python SDK | Python SDK for building Temporal workflows with native async support and type hints. |
| Java SDK | Java SDK for building Temporal workflows with annotation-based workflow and activity definitions. |
| .NET SDK | .NET SDK for building Temporal workflows in C# with strong typing and async patterns. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Temporal Cloud Operations API](openapi/cloud-ops-api.yml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Temporal Cloud Operations API](capabilities/shared/cloud-ops.yaml) -- 18 operations for namespace, user, service account, API key, and region management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Cloud Operations](capabilities/cloud-operations.yaml) | Cloud Ops API | 18 | Platform Administrator |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
