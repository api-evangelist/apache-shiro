# Apache Shiro (apache-shiro)

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

Apache Shiro is a powerful and easy-to-use Java security framework that performs authentication, authorization, cryptography, and session management. It provides a clean API for securing applications from the smallest mobile applications to the largest enterprise systems.

**URL:** [https://raw.githubusercontent.com/api-evangelist/apache-shiro/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-shiro/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Authentication, Authorization, Cryptography, Java, Security, Apache, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Shiro REST API
Shiro provides REST endpoints for authentication (login/logout/token), authorization (permission and role checking), session management, user management, and cryptographic password hashing in Shiro-secured applications.

**Human URL:** [https://shiro.apache.org/documentation.html](https://shiro.apache.org/documentation.html)

#### Tags:

 - Authentication, Authorization, REST, Apache, Open Source

#### Properties

- [Documentation](https://shiro.apache.org/documentation.html)
- [OpenAPI](openapi/apache-shiro-rest-api.yaml)

## Common Properties

- [GitHubOrganization](https://github.com/apache/shiro)
- [Documentation](https://shiro.apache.org/)
- [SpectralRules](rules/apache-shiro-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-shiro-vocabulary.yaml)
- [NaftikoCapability](capabilities/shiro-workflow.yaml)
- [JSON-LD](json-ld/apache-shiro-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Authentication | Pluggable authentication with username/password, remember-me, and token support |
| Authorization | Role-based and permission-based access control with wildcard permissions |
| Session Management | Native session management independent of HTTP containers |
| Cryptography | Password hashing with salt, bcrypt, Argon2, and SHA-256 |
| Multiple Realms | JDBC, LDAP, properties file, and custom realm support |
| Web Integration | Filter-based web application security with URL pattern matching |
| Annotations | AOP and annotation-based security for method-level authorization |

## Use Cases

| Name | Description |
|------|-------------|
| Web Application Security | Secure Java web applications with authentication and URL-based access control |
| REST API Security | Protect REST APIs with token authentication and permission checks |
| Microservice Auth | Stateless JWT authentication for microservice architectures |
| Admin Portal Security | Role-based admin interface with fine-grained permissions |

## Integrations

| Name | Description |
|------|-------------|
| Spring Framework | Shiro Spring integration for bean-level security |
| Jakarta EE | Java EE web filter integration for servlet containers |
| LDAP/Active Directory | LDAP realm for enterprise user directory authentication |
| JDBC | Database-backed realm for user and permission storage |
| Hazelcast | Distributed session management with Hazelcast |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache Shiro REST API](openapi/apache-shiro-rest-api.yaml)

### JSON Schema

- [Login Request](json-schema/apache-shiro-login-request-schema.json)
- [Session](json-schema/apache-shiro-session-schema.json)
- [Permission Check Result](json-schema/apache-shiro-permission-check-result-schema.json)
- [And more...](json-schema/)

### JSON Structure

- [Apache Shiro JSON Structures](json-structure/)

### JSON-LD

- [Apache Shiro Context](json-ld/apache-shiro-context.jsonld)

### Examples

- [Apache Shiro Examples](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Security Workflow](capabilities/shiro-workflow.yaml) | Apache Shiro | 8 | Application Developer, Security Administrator |

## Vocabulary

- [Apache Shiro Vocabulary](vocabulary/apache-shiro-vocabulary.yaml) — Unified taxonomy mapping security resources, actions, workflows, and personas

## Rules

- [Apache Shiro Spectral Rules](rules/apache-shiro-spectral-rules.yml) — Rules enforcing Apache Shiro API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
