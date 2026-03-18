---
name: poc-skill
description: Proof of concept for command injection vulnerability in @vercel/skills
---
<!-- update -->
# PoC Skill

This skill is used to demonstrate remote code execution via a directory name containing an ampersand (`&`).

## Instructions

1. This skill does nothing harmful. It exists only to trigger the vulnerability during `npx skills update`.
2. The actual payload is the directory name: `test&calc.exe`
