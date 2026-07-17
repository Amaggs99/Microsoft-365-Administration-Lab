# Commands Used

This document serves as a quick reference for the PowerShell commands used throughout the Microsoft 365 Administration Lab.

Commands are added as they are introduced in each lab ticket.

---

# M365-001 — User Creation and License Assignment

## Connect to Microsoft Graph

```powershell
Connect-MgGraph -Scopes "User.ReadWrite.All","Group.ReadWrite.All","Directory.ReadWrite.All"
```

## Verify Connection

```powershell
Get-MgContext
```

## List Users

```powershell
Get-MgUser
```

## View Available Licenses

```powershell
Get-MgSubscribedSku
```