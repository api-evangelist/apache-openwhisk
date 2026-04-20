# Apache OpenWhisk (apache-openwhisk)
Apache OpenWhisk is an open-source serverless cloud platform that executes functions in response to events at any scale. It supports multiple programming languages and provides a rich programming model for creating serverless APIs and event-driven applications.

**URL:** [https://raw.githubusercontent.com/api-evangelist/apache-openwhisk/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-openwhisk/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Cloud Native, Event-Driven, FaaS, Serverless, Apache, Open Source, Functions

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache OpenWhisk REST API
The OpenWhisk API provides REST endpoints for managing actions, triggers, rules, packages, and activations, supporting serverless function development in JavaScript, Python, Swift, Java, Go, PHP, and custom Docker runtimes.

**Human URL:** [https://openwhisk.apache.org/documentation.html](https://openwhisk.apache.org/documentation.html)

#### Tags:

 - FaaS, Functions, REST, Serverless, Apache, Open Source, Cloud Native

#### Properties

- [Documentation](https://openwhisk.apache.org/documentation.html)
- [OpenAPI](openapi/apache-openwhisk-rest-api.yaml)

## Common Properties

- [GitHubOrganization](https://github.com/apache/openwhisk)
- [Documentation](https://openwhisk.apache.org/)
- [SpectralRules](rules/apache-openwhisk-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-openwhisk-vocabulary.yaml)
- [NaftikoCapability](capabilities/serverless-workflow.yaml)
- [JSON-LD](json-ld/apache-openwhisk-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Serverless Functions | Execute stateless functions in response to events without managing infrastructure |
| Multi-Language Support | Supports Node.js, Python, Java, Go, PHP, Ruby, Swift, and custom Docker runtimes |
| Event Triggers | Named event channels that fire actions based on external events |
| Action Sequences | Compose multiple actions into sequential pipelines |
| Package System | Pre-built integrations via /whisk.system namespace |
| REST API | Full REST API for managing all platform resources programmatically |
| Docker Actions | Custom runtime support via Docker containers for any language |

## Use Cases

| Name | Description |
|------|-------------|
| Event-Driven Microservices | Build loosely coupled microservices that respond to events |
| IoT Data Processing | Process sensor and device events at scale without infrastructure management |
| API Backend | Create REST APIs backed by serverless functions |
| Scheduled Tasks | Run periodic jobs using alarm triggers |
| Chatbots & Webhooks | Handle Slack, GitHub, and other webhook events |

## Integrations

| Name | Description |
|------|-------------|
| Slack | Respond to Slack events and slash commands |
| GitHub | Automate workflows based on GitHub repository events |
| Apache Kafka | Process Kafka message stream events |
| Cloudant | React to CouchDB/Cloudant database changes |
| IBM Cloud | Available as IBM Cloud Functions on IBM Cloud |
| Kubernetes | Deploy OpenWhisk on Kubernetes using Helm charts |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache OpenWhisk REST API](openapi/apache-openwhisk-rest-api.yaml)

### JSON Schema

- [Action](json-schema/apache-openwhisk-action-schema.json)
- [Trigger](json-schema/apache-openwhisk-trigger-schema.json)
- [Rule](json-schema/apache-openwhisk-rule-schema.json)
- [Package](json-schema/apache-openwhisk-package-schema.json)
- [Activation](json-schema/apache-openwhisk-activation-schema.json)
- [And more...](json-schema/)

### JSON Structure

- [Apache OpenWhisk JSON Structures](json-structure/)

### JSON-LD

- [Apache OpenWhisk Context](json-ld/apache-openwhisk-context.jsonld)

### Examples

- [Apache OpenWhisk Examples](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [OpenWhisk REST API](capabilities/shared/openwhisk-rest-api.yaml) — Core REST API operations for serverless management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Serverless Workflow](capabilities/serverless-workflow.yaml) | OpenWhisk | 10 | DevOps Engineer, Backend Developer, Platform Administrator |

## Vocabulary

- [Apache OpenWhisk Vocabulary](vocabulary/apache-openwhisk-vocabulary.yaml) — Unified taxonomy mapping serverless resources, actions, workflows, and personas

## Rules

- [Apache OpenWhisk Spectral Rules](rules/apache-openwhisk-spectral-rules.yml) — 10 rules enforcing Apache OpenWhisk API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
