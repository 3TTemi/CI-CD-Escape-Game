# Level 1 — The YAML Is Angry

Your CI pipeline is failing before it even starts running.

Why?  
Because the YAML workflow file in `.github/workflows/escape-room.yml` is **broken**.

## Your Task
Fix the YAML so that GitHub Actions can:
- parse the workflow file
- install dependencies
- run the test suite

When your GitHub Actions run turns **🟢 GREEN**, you escape Level 1.

## Hints
- YAML is extremely picky about **indentation**
- colons matter (`key: value`)
- action steps must be nested correctly

Good luck. 😈
