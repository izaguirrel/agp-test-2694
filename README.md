# AGP Test Repo for GUIDE-2694

This repo is for testing GUIDE-2694: package-scope PR dedup with cooldown window.

## Purpose

Test that AGP correctly:
1. Writes package markers in PR body
2. Skips when open PR exists (even with version drift)
3. Respects closed-PR cooldown window
4. Allows cooldown opt-out via agp.yml

## dependency

- eslint 9.14.0 (outdated - latest is 9.29.0)
