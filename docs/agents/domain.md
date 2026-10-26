# Domain docs

## Layout

This repository uses a single-context domain documentation layout:

- `GLOSSARY.md` at the repository root defines domain terms.
- `docs/adr/` contains architecture decision records.

All paths in this document are relative to the repository root.

Sibling worktrees and supporting directories in the parent OpSim
workspace do not constitute additional domain contexts within
this repository.

## Before exploring

Read `GLOSSARY.md` if it exists, then read ADRs relevant to the
area being investigated.

If these documents do not exist, proceed silently. Do not suggest
creating them merely because they are absent. The domain-modeling
skill creates them when terms or decisions are resolved.

## Use the glossary's vocabulary

Use defined domain terms consistently in issue titles, proposals,
hypotheses, tests, and code.

When a needed concept is missing, check whether an existing term
already covers it. Record a genuine terminology gap for
domain-modeling when relevant to the work.

## Surface ADR conflicts

If a proposal contradicts an existing ADR, identify that ADR and
explain why the decision may need to be revisited.
