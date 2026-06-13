# Alloy

Alloy is an identity decisioning platform that provides a single REST API for running KYC/KYB workflows, evaluating applicant risk, automating compliance decisions, and managing ongoing monitoring throughout the customer lifecycle. The platform connects banks and fintechs to more than 85 data sources for fraud prevention, credit underwriting, transaction monitoring, and regulatory compliance.

## Links

- **Website**: https://www.alloy.com
- **Developer Portal**: https://www.alloy.com/developer
- **API Documentation**: https://developer.alloy.com/public/docs/introduction
- **API Reference**: https://developer.alloy.com/public/reference
- **Authentication Guide**: https://developer.alloy.com/public/docs/authentication-guide
- **Help Center**: https://help.alloy.com/hc/en-us
- **Status Page**: https://status.alloy.com
- **Blog**: https://www.alloy.com/blog
- **Security**: https://www.alloy.com/security
- **GitHub**: https://github.com/useAlloy
- **LinkedIn**: https://www.linkedin.com/company/alloy-apis
- **X**: https://x.com/usealloy

## APIs

- **Alloy Identity API** - Single REST API for KYC/KYB workflows, entity management, evaluations, journey applications, event monitoring, document verification, and investigations. Base URL: `https://sandbox.alloy.co/v1` (sandbox).

## Authentication

Alloy supports two authentication methods:

1. **Basic HTTP Authentication** - Base64-encoded `token:secret` in the `Authorization: Basic` header.
2. **OAuth 2.0 Client Credentials** - POST to `https://sandbox.alloy.co/v1/oauth/bearer` for a bearer token (valid 1 hour), then use `Authorization: Bearer <token>`.

Both methods use a `token` and `secret` issued per application, viewable in the Alloy dashboard.

## Key Capabilities

- Entity management (person and business entities)
- KYC/KYB workflow evaluations with 85+ data sources
- Journey applications with multi-step decisioning
- Ongoing monitoring (transactions, PII changes, logins)
- Document verification (web, iOS, Android SDKs)
- Investigations and case management
- Webhooks with Basic Auth, HMAC, and OAuth 2.0 support
- SAML SSO and SCIM provisioning
- Sandbox environment for testing

## SDKs

- iOS: https://github.com/useAlloy/alloy-codeless-lite-ios
- Android: https://github.com/useAlloy/alloy-codeless-lite-android

## Compliance

SOC 2 Type 2 certified, ISO 27001 data center, AES-256 encryption at rest, TLS 1.2 in transit, hosted on AWS.

## APIs.json

This repository is indexed as an APIs.json provider profile. See [apis.yml](apis.yml) for the machine-readable index.
