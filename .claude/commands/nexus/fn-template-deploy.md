---
description: Browse and deploy Flow Nexus templates
argument-hint: [template-name]
---

Browse available templates and deploy the specified one.

If template name provided ($1):
- Deploy directly using: npx flow-nexus template deploy $1
Otherwise:
- List templates with: npx flow-nexus template
- Let user select interactively

Note: Template deployments consume rUv credits. Check balance first if needed.

