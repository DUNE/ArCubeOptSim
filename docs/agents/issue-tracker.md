# Issue tracker: GitHub

Issues and specs for this repository live in GitHub Issues in
`DUNE/ArCubeOptSim`:

https://github.com/DUNE/ArCubeOptSim/issues

## Current access

The GitHub CLI is optional. Check whether it is available and
authenticated before using it; otherwise read issues in a browser.

If an issue cannot be accessed, report that limitation rather than
inferring its requirements.

## Baseline and upgrade

Issue #2 tracks the Geant4 10.7.4 upgrade:

https://github.com/DUNE/ArCubeOptSim/issues/2

The `g4-10.6.2` branch establishes a baseline before that upgrade.
Work on this branch should follow the baseline scope; issue #2
does not by itself authorize implementing the upgrade here.

Verify the relevant worktree and branch before making changes.
Read issue #2 when deriving requirements for the upgrade.
Use the relevant ticket for unrelated work.

## Optional future CLI access

If `gh` is installed and authenticated later, these read-only
commands may be used from any working directory:

- Read an issue:
  `gh issue view <number> --repo DUNE/ArCubeOptSim --json number,title,body,labels,comments`
- List issues:
  `gh issue list --repo DUNE/ArCubeOptSim --state open --json number,title,labels`

CLI availability is optional; browser access remains acceptable.

## Skill operations

When a skill says "fetch the relevant ticket", read the referenced
GitHub issue, including its comments and labels.

When a skill says "publish to the issue tracker", the destination
is GitHub Issues in `DUNE/ArCubeOptSim`. Follow the user's
authorization for the task before publishing.

Read `triage-labels.md` before any label operation.

## Pull requests as a triage surface

**PRs as a request surface: no.**

## Setup constraint

Do not create, edit, comment on, or close DUNE issues as part of
this setup. Do not change GitHub labels or issue-label assignments
as part of this setup.
