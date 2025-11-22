# Level 6 — Roll Back Production

A “production deployment” (faked for the escape room) is intentionally broken.

Your job is to perform a **rollback**.

## Your Task
1. Identify the last successful build (the facilitator will show your fake deploy history)
2. Perform a rollback by:
   - reverting the bad commit, OR
   - checking out the last good commit and pushing it, OR
   - restoring the last working version of `api/server.js`
3. Push your rollback fix

When CI runs and turns **🟢 GREEN**, you escape the final level.

## Hints
- Look at GitHub commit history
- Look for what changed between “working” and “broken”
- This level simulates real-world hotfixing 🔥

Congratulations — this is the end. 🎉
