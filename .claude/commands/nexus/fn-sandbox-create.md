---
description: Create a new Flow Nexus sandbox environment
argument-hint: [template] [name]
---

Create a sandbox environment with specified template and name.

Parse arguments:
- Template type: $1 (e.g., node, python, react, nextjs, vanilla, base, claude-code)
- Sandbox name: $2 (optional, defaults to template name)

Use the mcp__flow-nexus__sandbox_create tool with:
- template: $1
- name: $2 (or $1 if not specified)

After creation, verify with: npx flow-nexus system

