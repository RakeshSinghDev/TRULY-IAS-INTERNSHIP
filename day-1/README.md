
# Day 1 – TRULY IAS INTERNSHIP

## Topics Covered

### 1. SAML 2.0
- Introduction to SAML 2.0 and Federation
- SAML Assertion and its components
  - Subject
  - Conditions
  - Authentication Statement
  - Attribute Statement
  - Digital Signature
- SAML Web Browser SSO Flow
- Main SAML entities:
  - User / Principal
  - Identity Provider (IdP)
  - Service Provider (SP)
- Circle of Trust
- SP-Initiated SSO Flow
- Assertion Consumer Service (ACS)
- SAML 2.0 vs OAuth 2.0 vs OpenID Connect

### 2. OAuth 2.0
- OAuth 2.0 Authorization Framework
- OAuth 2.0 main players:
  - Resource Owner
  - Client
  - Authorization Server
  - Resource Server
- Access Token
- Refresh Token
- Token format and claims
- OAuth 2.0 Authorization Code Flow
- Protected Resource Access

### 3. OpenID Connect (OIDC)
- OIDC as an identity layer on top of OAuth 2.0
- Authentication vs Authorization
- OIDC Providers and Relying Parties
- Access Token vs ID Token
- ID Token (JWT)
- OIDC scopes and claims
- Claims mapping
- OIDC Authorization Code Flow
- UserInfo endpoint
- Basic identity/profile information

## Key Takeaways

- SAML is widely used for enterprise Single Sign-On (SSO).
- OAuth 2.0 is primarily an authorization framework for delegated access.
- OIDC adds authentication and identity information on top of OAuth 2.0.
- SAML uses XML-based assertions, while OAuth 2.0 commonly uses access tokens and OIDC uses ID tokens (JWT).
- Identity Provider (IdP) authenticates the user, while the Service Provider (SP) consumes the SAML assertion.
- In OAuth 2.0, the Resource Server protects APIs/resources and validates access tokens.
- In OIDC, the ID Token carries identity claims about the authenticated user.

## Notes

Handwritten notes for today's topics are available in this folder.

- SAML 2.0 – Assertion & Components
- SAML 2.0 Federation
- OAuth 2.0
- OpenID Connect (OIDC)
