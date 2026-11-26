# Lab 06 — Add a Federated Identity Provider

**Certification:** Microsoft SC-300  
**Module:** 1 — Implement an Identity Management Solution  
**Platform:** Microsoft Entra ID / Google Cloud  
**Status:** Completed

## Objective
Understand identity federation by configuring Google as an external identity provider for Microsoft Entra B2B collaboration.

## Activities
- Created a Google Cloud project and configured its OAuth consent screen.
- Registered an OAuth client and configured authorized redirect URIs.
- Added a Google test user for authentication.
- Configured Google federation in Microsoft Entra External Identities.
- Invited an external user and tested invitation redemption.
- Validated federated authentication using a Google account.

## Tools Used
- Microsoft Entra admin center
- Google Cloud Console
- OAuth 2.0
- Microsoft 365

## Key Takeaways
- Identity federation allows external users to authenticate using their existing identity provider.
- OAuth client credentials and redirect URIs are essential federation configuration components.
- Authentication and authorization are distinct: successful Google authentication does not automatically grant access to every Microsoft 365 resource.
- Federation can simplify external collaboration without requiring separate passwords for every organization.

## Security Perspective
Federation extends an organization's trust boundary to external identity providers. Compromised external accounts, exposed OAuth client secrets, or incorrectly configured trust relationships may introduce security risks.

Important controls include:
- Protecting OAuth client secrets and restricting their access.
- Validating redirect URIs and reviewing federation configurations.
- Applying Conditional Access and least-privilege access where supported.
- Monitoring external user sign-ins, invitation activity, and identity provider configuration changes.
- Reviewing guest access and removing unnecessary accounts.

From a SOC perspective, successful federated authentication should be evaluated alongside sign-in risk, device context, access policies, and resource permissions.

Issues Encountered:
- I had entered a wrong redirect URI, so when access the tenant with the google test account, the expected URI was not in it. 
- Got a URI Redirect mismatch.
- Since I could not edit the the created client app in Google.
- Created a new one, updated the client ID and secret in Entra ID, then retried.
- Gave it time to sync and access was granted.

## Reference
[Microsoft SC-300 — Lab 06: Add a Federated Identity Provider](https://microsoftlearning.github.io/SC-300-Identity-and-Access-Administrator/Instructions/Labs/Lab_06_AddFederatedIdentityProvider.html)