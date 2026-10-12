# Awesome-Identity-User-Access-Governance

## Top Identity & User Access Governance Tools Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Identity Lifecycle Management, Access Certification & Privileged Access Governance*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Identity & User Access Governance Tools**. These tools help organizations manage user identities, automate access provisioning and de-provisioning, enforce least-privilege policies, run access certification campaigns, and maintain compliance with regulatory frameworks like SOX, HIPAA, and GDPR.



**Examples** include Salesforce User Management, SailPoint Identity Security, Saviynt Enterprise Identity Cloud, Okta Identity Governance, Microsoft Entra ID Governance, Ping Identity, Omada Identity, One Identity, Lumos, and ConductorOne (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom governance workflows, and transparent access control — ideal for organizations prioritizing data sovereignty, developers building identity platforms, and teams avoiding per-user pricing.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Salesforce User Management](https://www.salesforce.com/)**  

  User administration within Salesforce with profiles, permission sets, role hierarchies, and login access policies.



- **[SailPoint Identity Security](https://www.sailpoint.com/)**  

  Enterprise identity security platform with AI-driven identity governance, access certifications, and privileged access management.



- **[Saviynt Enterprise Identity Cloud](https://saviynt.com/)**  

  Cloud identity governance platform with application access governance, privileged access management, and third-party risk management.



- **[Okta Identity Governance](https://www.okta.com/)**  

  Identity governance solution within Okta with access certifications, access requests, and identity lifecycle management.



- **[Microsoft Entra ID Governance](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)**  

  Microsoft's identity governance suite with entitlement management, access reviews, lifecycle workflows, and privileged identity management.



- **[Ping Identity](https://www.pingidentity.com/)**  

  Identity platform with identity governance and administration (IGA), lifecycle management, and AI-driven access certification .



- **[Omada Identity](https://www.omada.net/)**  

  Identity governance and administration platform with access governance, provisioning, and compliance management.



- **[One Identity](https://www.oneidentity.com/)**  

  Identity governance and administration suite with access certification, role management, and privileged access governance.



- **[Lumos](https://www.lumos.com/)**  

  Identity governance platform with app discovery, access reviews, and automated provisioning for modern SaaS stacks.



- **[ConductorOne](https://www.conductorone.com/)**  

  Identity security and access governance platform with automated access reviews, provisioning, and least-privilege enforcement.



## Open-Source GitHub Projects



- **[Evolveum MidPoint](https://github.com/Evolveum/midpoint)**  

  Comprehensive open-source Identity Management (IDM) and Identity Governance (IGA) platform. Handles user lifecycle management, provisioning/deprovisioning, role-based access control, certification campaigns, and synchronization across heterogeneous systems. Supports SCIM, LDAP, and multiple connectors .



- **[Apache Syncope](https://github.com/apache/syncope)**  

  Apache's open-source identity management platform with user provisioning, access certification, role management, and workflow-driven governance. Java-based with extensive connector framework .



- **[WrenIDM (OpenICF)](https://github.com/WrenSecurity/wrenidm)**  

  Community-developed identity management system with flexible data model, multiple extension points, and scripting support (JavaScript, Groovy). Fork of ForgeRock OpenIDM Community Edition .



- **[Janssen Project](https://github.com/JanssenProject/jans)**  

  Linux Foundation project providing enterprise-grade IAM components including OAuth/OpenID Auth Server, Agama low-code identity orchestration, SCIM for user management, and Cedarling policy decision point for authorization. Self-funded and vendor-neutral .



- **[Gravitee Access Management](https://github.com/gravitee-io/gravitee-access-management)**  

  Open-source IAM solution with OAuth 2.0, OpenID Connect, and SAML support. Features user management, SSO, MFA, and fine-grained authorization .



- **[OSIAM (Open Source Identity and Access Management)](https://github.com/osiam/osiam)**  

  MIT-licensed IAM implementing OAuth 2.0 and SCIMv2 for user provisioning and access management .



- **[FusionDirectory](https://github.com/fusiondirectory/fusiondirectory)**  

  Modern, efficient, and secure Identity Management (IAM) solution with LDAP directory management and web-based administration .



- **[MaxKey](https://github.com/dromara/MaxKey)**  

  Leading IAM/IDaaS product under Apache License 2.0. Supports OAuth2.x, OpenID Connect, SAML2.0, CAS, JWT, SCIM, with unified RBAC permission control and user lifecycle management .



- **[BoxyHQ Jackson](https://github.com/boxyhq/jackson)**  

  SSO service supporting SAML and OpenID Connect with SCIM 2.0 for automatic user and group provisioning/deprovisioning. Streamlines enterprise SSO and directory sync .



- **[Casdoor](https://github.com/casdoor/casdoor)**  

  Open-source UI-first identity and access management platform with OAuth, OIDC, SAML, and RBAC support. Includes user management, authentication, and authorization .



- **[Zitadel](https://github.com/zitadel/zitadel)**  

  Open-source identity infrastructure with OIDC, SAML, MFA, and fine-grained authorization. API-first and cloud-native .



- **[Casbin](https://github.com/casbin/casbin)**  

  Authorization library supporting ACL, RBAC, and ABAC across Go, Java, Node.js, Python, .NET, Rust, PHP, and Elixir. Model-based policy configuration .



- **[OpenFGA](https://github.com/openfga/openfga)**  

  Open-source fine-grained authorization engine based on Relationship-Based Access Control (ReBAC), inspired by Google Zanzibar. Models access through relationships between users and objects .



### Additional Strong Open-Source Options



- **[ORY Kratos](https://github.com/ory/kratos)** — Headless identity server for user login, registration, 2FA, and profile management. Replaces Auth0, Okta, Firebase .

- **[SuperTokens](https://github.com/supertokens/supertokens-core)** — Open-source login and session management supporting passwordless, social login, email and phone auth .

- **[Permit – OPAL](https://github.com/permitio/opal)** — Open Policy Administration Layer for Open Policy Agent (OPA) detecting policy and data changes in real-time .

- **[FreeIPA](https://github.com/freeipa/freeipa)** — Integrated security information management solution combining Linux, 389 Directory Server, MIT Kerberos, NTP, DNS, and Dogtag Certificate System .

- **Access Review Tools** — Granted (access request and approval workflows), Teleport (infrastructure access review), AccessBot (Slack-based access requests) .



**Frameworks for building custom systems**: Combine **Evolveum MidPoint** or **Apache Syncope** for identity governance, **Janssen Project** for auth server and SCIM, **OpenFGA** or **Casbin** for fine-grained authorization, **BoxyHQ Jackson** for SSO/SCIM integration, and **Keycloak** for authentication to build a complete self-hosted identity governance stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Identity governance tools must comply with data protection regulations (GDPR, CCPA), industry standards (SOC 2, ISO 27001, SOX), and access control requirements.

- Self-hosted open-source solutions require proper security hardening, directory integration, and ongoing governance process design.



---



**Made for identity architects, security teams, compliance officers, and developers building identity governance platforms.**  

Let's make identity and user access governance more open, auditable, and developer-friendly.
