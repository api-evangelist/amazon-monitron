# Amazon Monitron (amazon-monitron)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Amazon Monitron is an end-to-end system that uses machine learning to detect abnormal behavior in industrial machinery. It includes sensors, a gateway, and the Monitron mobile app to enable predictive maintenance and reduce unplanned downtime.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-monitron/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Broadcasting, Media Processing, Media

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon Monitron API
Amazon Monitron is an end-to-end system that uses machine learning to detect abnormal behavior in industrial machinery. It includes sensors, a gateway, and the Monitron mobile app to enable predictive maintenance and reduce unplanned downtime.

**Human URL:** [https://aws.amazon.com/monitron/](https://aws.amazon.com/monitron/)

#### Tags:

 - Broadcasting, Media Processing, Media

#### Properties

- [Documentation](https://docs.aws.amazon.com/monitron/)
- [OpenAPI](openapi/amazon-monitron-openapi-original.yml)
- [GettingStarted](https://aws.amazon.com/monitron/getting-started/)
- [Pricing](https://aws.amazon.com/monitron/pricing/)
- [FAQ](https://aws.amazon.com/monitron/faqs/)

## Common Properties

- [Portal](https://aws.amazon.com/monitron/)
- [Documentation](https://docs.aws.amazon.com/monitron/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/media/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/monitron/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)

## Features

| Name | Description |
|------|-------------|
| ML-Based Anomaly Detection | Machine learning models trained on industrial machinery data to detect abnormal behavior automatically. |
| Project Management | Organize machine monitoring deployments into projects with access control. |
| End-to-End System | Integrated hardware sensors, gateway, cloud processing, and mobile app in one solution. |
| Predictive Maintenance | Identify potential equipment failures before they occur to schedule proactive maintenance. |
| User Access Control | Manage project administrators and user associations with fine-grained permissions. |

## Use Cases

| Name | Description |
|------|-------------|
| Industrial Equipment Monitoring | Monitor motors, pumps, fans, and compressors for early signs of failure. |
| Predictive Maintenance Programs | Build data-driven maintenance schedules based on actual equipment health. |
| Downtime Reduction | Reduce unplanned production downtime by catching issues before equipment fails. |
| Plant-Wide Monitoring | Deploy sensors across entire manufacturing facilities for comprehensive asset health. |

## Integrations

| Name | Description |
|------|-------------|
| AWS IoT Core | Monitron gateway connects to the cloud via AWS IoT Core. |
| Amazon Kinesis | Stream Monitron measurement data to Kinesis for real-time analytics. |
| Amazon S3 | Export historical sensor data to S3 for long-term analysis. |
| AWS IAM | Control API access and project permissions with IAM policies. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon Monitron OpenAPI](openapi/amazon-monitron-openapi-original.yml)

### JSON Schema

- 4 schema files in [json-schema/](json-schema/)

### JSON Structure

- 4 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Amazon Monitron API Context](json-ld/amazon-monitron-monitron-api-context.jsonld)

### Examples

- 4 example files in [examples/](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon Monitron](capabilities/shared/monitron.yaml) — 12 operations for media processing

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Amazon Monitron Workflow](capabilities/amazon-monitron-media-workflow.yaml) | Amazon Monitron | 8 | Broadcast Engineer |

## Vocabulary

- [Amazon Monitron Vocabulary](vocabulary/amazon-monitron-vocabulary.yaml) — Unified taxonomy mapping resources, actions, workflows, and personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon Monitron Spectral Rules](rules/amazon-monitron-spectral-rules.yml) — 20 rules across 8 categories enforcing Amazon Monitron API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
