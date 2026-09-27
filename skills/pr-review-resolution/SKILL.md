---
name: pr-review-resolution
description: Resolve the first Codex pull-request review in one bounded remediation pass for this hardware/reference repository.
---

# PR Review Resolution

1. Read the PR diff, first Codex findings and only directly relevant files.
2. Classify each finding as valid/actionable, already resolved, not applicable, or conflicting with authoritative hardware/project information.
3. Fix valid findings using the smallest safe change.
4. Preserve electrical-safety warnings, upstream attribution and hardware assumptions.
5. Do not make unrelated PCB/schematic/configuration refactors.
6. Run only relevant validation that is actually available.
7. Verify every original valid finding is resolved.
8. Request one fresh Codex verification review.
9. Do not merge automatically.

If two materially similar review cycles fail to converge, stop and report the disagreement.
