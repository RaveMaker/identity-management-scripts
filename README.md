# Identity Management Scripts

A collection of Active Directory and Windows workstation scripts for user lifecycle, domain join, and desktop provisioning.

Each tool lives in its own folder with a focused README. Edit the embedded configuration for your domain, then run or deploy as documented per script.

## Repository Structure

```text
identity-management-scripts/
├── disable-inactive-ad-users/
├── get-ad-users-last-logon-report/
├── map-drives-and-printers/
└── pc-renamer/
```

## Scripts

| Script | Description |
|--------|-------------|
| **disable-inactive-ad-users** | PowerShell — disable AD users inactive (or unused since creation) beyond a set number of days; writes a CSV report |
| **get-ad-users-last-logon-report** | VBScript — report last logon for users and computers across the domain (optional OU filter) |
| **map-drives-and-printers** | VBScript — map network drives and printers from AD group membership at logon |
| **pc-renamer** | PowerShell — rename a PC from its IP/VLAN mapping and join it to the correct AD OU (startup service) |

## Typical Use

1. Clone the repository (or copy the folder you need).
2. Open that script’s README and adjust domain, OU, paths, and credentials for your environment.
3. Run or install as described for that tool.

## Author

**Adam Mallul (RaveMaker)**

- GitHub: https://github.com/RaveMaker
- Website: https://ravemaker.net
