# Apache Shiro (apache-shiro)
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
