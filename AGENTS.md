# BSH-Board Working Rules

## Scope
This repository contains hardware, KiCad, ESPHome and build artefacts for a B/S/H appliance interface board.

Treat it as a hardware/reference project with potentially hazardous real-world consequences.

## Smallest safe change
Make the smallest change that resolves the task. Do not mix PCB, schematic, enclosure, ESPHome and unrelated cleanup changes without a clear reason.

## Hardware safety
Do not weaken or remove electrical-safety warnings.

Changes that affect mains-adjacent interfaces, isolation assumptions, connectors, power rails, clearances, creepage, grounding or appliance integration must explicitly document the affected hardware assumption and verification performed.

## Upstream/reference respect
Preserve attribution and do not present upstream-derived material as original work.

## PR review remediation
When Codex review findings exist, use `skills/pr-review-resolution/SKILL.md`. Fix valid first-review findings in one bounded pass, validate the affected artefacts, request one fresh verification review, and do not merge automatically.

If two materially similar review cycles fail to converge, stop and report the disagreement.

## AI tooling
Do not add GitHub Copilot-specific instruction files, reviewers, workflows or automation.
