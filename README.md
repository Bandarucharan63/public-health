# Fieldwork Health

## Run locally

Open PowerShell in this folder and run:

```powershell
.\serve.ps1
```

Then open `http://localhost:8000/`. Choose Admin or User at sign-in; this local preview does not validate passwords.

## Workspaces

- The user dashboard opens on the data overview with charts calculated from that user's dataset. User data is stored separately by email in the current browser.
- Admins can edit region/program assignments for a program group and update individual participant records. Admin edits are saved in the current browser and reflected in dashboard summaries and CSV exports.
- These browser-local changes are not shared across browsers or devices. The source CSV remains unchanged.