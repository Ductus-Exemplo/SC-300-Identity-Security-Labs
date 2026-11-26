# Lab 05 — Add Guest Users to the Directory

**Certification:** Microsoft SC-300  
**Module:** 1 — Implement an Identity Management Solution  
**Platform:** Microsoft Entra ID  
**Status:** Completed

## Objective
Understand how to onboard external guest users into Microsoft Entra ID for secure B2B collaboration.

## Activities
- Invited individual guest users through Microsoft Entra ID.
- Performed bulk guest invitations using a CSV file.
- Used Microsoft Graph PowerShell to invite external users.
- Verified guest user accounts and reviewed bulk invitation results.

## Tools Used
- Microsoft Entra admin center
- Microsoft Graph PowerShell
- PowerShell 7
- CSV

## Key Takeaways
- Microsoft Entra B2B collaboration enables external identities to access organizational resources.
- Guest users can be invited individually or through bulk operations.
- Microsoft Graph PowerShell supports automated guest onboarding.
- Guest account creation and invitation redemption are separate stages.

## Security Perspective
External guest accounts expand an organization's identity attack surface. Unnecessary guest accounts, excessive permissions, and unmanaged invitations can introduce security risks.

From an Identity Security and SOC perspective, important controls include:

- Restricting guest invitation permissions.
- Applying least-privilege access.
- Monitoring guest invitations and unusual external sign-ins.
- Periodically reviewing guest access and removing accounts that are no longer required.

Guest onboarding should be governed throughout the identity lifecycle, from invitation to access removal.

## Reference
[Microsoft SC-300 — Lab 05: Add Guest Users to the Directory](https://microsoftlearning.github.io/SC-300-Identity-and-Access-Administrator/Instructions/Labs/Lab_05_AddGuestUsersToTheDirectory.html)
