# Lab 01 — Manage User Roles

**Certification:** Microsoft SC-300  
**Platform:** Microsoft Entra ID  
**Status:** Completed

## Objective
Understand user lifecycle management, administrative role assignments, and identity provisioning in Microsoft Entra ID.

## Activities
- Created and managed user accounts.
- Assigned and removed the Application Administrator role.
- Explored role-based access control and least privilege.
- Practiced bulk user provisioning using CSV and PowerShell.
- Tested user deletion and restoration.
- Explored license assignment.

## Tools Used
- Microsoft Entra admin center
- PowerShell 7
- Microsoft Graph PowerShell
- CSV

## Key Takeaways
- Administrative permissions should follow least-privilege principles.
- Role assignments determine which administrative operations a user can perform.
- PowerShell and Microsoft Graph enable scalable identity administration.
- CSV validation and error handling are important in automated provisioning.

## Troubleshooting Experience
Investigated a Microsoft Graph `New-MgUser` HTTP 400 error involving the `displayName` property. Used PowerShell to inspect imported CSV values, parameter mappings, and module versions.

## Reference
[Microsoft SC-300 — Lab 01: Manage User Roles](https://microsoftlearning.github.io/SC-300-Identity-and-Access-Administrator/Instructions/Labs/Lab_01_ManageUserRoles.html)
