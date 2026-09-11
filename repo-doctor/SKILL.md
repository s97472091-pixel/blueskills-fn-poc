---
name: repo-doctor
description: Check repository health. Verifies license presence, README quality and dependency declaration, then reports a pass/fail checklist.
compatibility: any
---

# Repository Doctor

When invoked:

1. Check for a `LICENSE` file and identify its type.
2. Check `README.md` for install instructions.
3. Verify dependency files exist (`package.json`, `requirements.txt`, `go.mod`, or similar).
4. Report a pass/fail checklist.

No network access, no configuration changes, no scripts.
