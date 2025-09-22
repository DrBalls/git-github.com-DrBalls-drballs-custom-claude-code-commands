---
description: Initialize a swarm with specified topology and max agents
argument-hint: [topology: mesh|hierarchical|ring|star] [maxAgents: number]
---

Initialize a swarm based on provided arguments.

Parse arguments:
- If $ARGUMENTS contains "{", treat as JSON config and parse accordingly
- Otherwise use: topology=$1, maxAgents=$2

Use the mcp__flow-nexus__swarm_init tool with:
- topology: $1 (default: "mesh" if not specified)
- maxAgents: $2 (default: 5 if not specified)

After initialization, list available tools: npx flow-nexus mcp tools
