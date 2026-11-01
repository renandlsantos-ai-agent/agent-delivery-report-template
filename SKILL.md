---
name: delivery-report
description: Use at the end of every coding task. Write a short delivery report covering what changed, why, what was skipped, what could break and what could not be verified.
---

# Delivery report

Before you say a task is done, end your reply with a delivery report using these sections:

1. **What changed**: list each file touched and the behavior change in plain words.
2. **Why**: the reason behind each meaningful choice.
3. **What I skipped**: anything left out, simplified, stubbed or postponed. Say "Nothing" only if true.
4. **What could break**: risks, affected callers, data or config.
5. **What I could not verify**: tests you did not run, environments you did not check, assumptions you made.
6. **How to check it**: the exact commands or steps to confirm the change.

Rules:
- Be honest and specific. Never claim a test passed unless you ran it and saw it pass.
- Keep it short. Bullets, no filler.
- If the task failed or is partial, say so in the first line.
