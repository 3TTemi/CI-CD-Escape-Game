# Level 5 — Missing Deployment Secret

The pipeline reaches the deploy step and then crashes.

Why?  
Because the workflow references a required secret:

$VERCEL_TOKEN

…but the secret is **not configured** in GitHub.

## Your Task
1. Go to your fork’s GitHub repo  
2. Navigate to:  
   **Settings → Secrets → Actions**
3. Add a new secret called:  
   **VERCEL_TOKEN**
4. Set it to any non-empty value (a fake token is fine)

Your workflow will pass the deploy step and turn **🟢 GREEN**.

## Hints
- The key MUST be named exactly `VERCEL_TOKEN`
- You don’t need a real Vercel account — the deploy step is mocked
