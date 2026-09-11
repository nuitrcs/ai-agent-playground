# Lab Notebook

Add a dated entry every time you make a change to this repo. Newest entries at the top.

## 2026-09-11 — Codex
- The script failed with `KeyError: 'cohort'` because it tried to read a `cohort` column, but the CSV header names that column `group`.
- I fixed the lookup by changing `row["cohort"]` to `row["group"]`, then ran the script and confirmed it prints counts and mean response times for both groups.

## Example — 2026-01-01 — A. Researcher
- Ran `analysis/summarize.py` for the first time; confirmed the repo and my tool are connected.
- No changes made yet — just checking the pipeline works end to end.

<!-- Add your own entry above this line -->
