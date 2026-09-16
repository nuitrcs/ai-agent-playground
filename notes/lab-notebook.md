# Lab Notebook

Add a dated entry every time you make a change to this repo. Newest entries at the top.

## 2026-09-16 — Roberto Brooks
- Ran `analysis/summarize.py` and hit `KeyError: 'cohort'` in `load_groups`.
- Cause: the script read `row["cohort"]`, but `data/reaction_times.csv` names that column `group`.
- Fix: changed `row["cohort"]` to `row["group"]` in `analysis/summarize.py`.
- Re-ran the script; it now prints count and mean response time for both groups (`control` and `treatment`).

## Example — 2026-01-01 — A. Researcher
- Ran `analysis/summarize.py` for the first time; confirmed the repo and my tool are connected.
- No changes made yet — just checking the pipeline works end to end.

<!-- Add your own entry above this line -->
