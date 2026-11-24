# Lab 04 — Configure External Collaboration Settings

**Certification:** Microsoft SC-300  
**Module:** 1 — Implement an Identity Management Solution  
**Platform:** Microsoft Entra ID  
**Status:** Completed

## Objective
Configure external collaboration settings to securely manage guest access within a Microsoft Entra ID tenant.

## Activities
- Enabled guest self-service sign-up via user flows.
- Reviewed and enabled email one-time passcode authentication.
- Configured restrictive guest directory access permissions.
- Reviewed and configured guest invitation permissions.
- Examined domain-based collaboration restrictions.

## Tools Used
- Microsoft Entra admin center
- Microsoft Entra External Identities

## Key Takeaways
- Microsoft Entra B2B collaboration enables external users to access organizational resources.
- Guest access levels determine which directory information external users can view.
- Guest invitation permissions control who can onboard external identities.
- Domain allowlists and blocklists help govern external collaboration.

## Security Perspective
External identities introduce additional risks, including unauthorized access, excessive permissions, and unintended information exposure.

Applying least-privilege guest permissions, restricting invitation capabilities, and reviewing external identities regularly can reduce these risks.

From a SOC perspective, guest invitations, unusual external sign-ins, and changes to external collaboration settings are useful activities to monitor for potential misuse.

## Reference
[Microsoft SC-300 — Lab 04: Configure External Collaboration Settings](https://microsoftlearning.github.io/SC-300-Identity-and-Access-Administrator/Instructions/Labs/Lab_04_ConfigureExternalCollaborationSettings.html)