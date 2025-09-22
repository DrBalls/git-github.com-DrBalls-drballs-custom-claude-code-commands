---
description: Authenticate with Flow Nexus using email
argument-hint: [email] [password]
---

Authenticate to Flow Nexus using provided credentials.

If password not provided, prompt for secure entry.

Use the mcp__flow-nexus__user_login tool with:
- email: $1
- password: $2 (or prompt if not provided)

After authentication, verify status with: npx flow-nexus auth status
