# Repository guidance

When working within the parent OpSim workspace, keep that workspace
as the main working directory. Keep repository-specific guidance
inside this repository.

Git operations must target the relevant worktree and branch.
Verify the target worktree and checked-out branch before making
changes; directory names do not establish branch identity.

The parent workspace may contain sibling worktrees and supporting
directories such as `resources_tutorials` and `software`.

## Agent skills

### Issue tracker

Issues and specs live in GitHub Issues in `DUNE/ArCubeOptSim`.
Before working with tickets, read `docs/agents/issue-tracker.md`.

### Triage labels

The triage-label mapping is undecided. Before triaging issues,
read `docs/agents/triage-labels.md`.

### Domain docs

Use a single-context layout: root `GLOSSARY.md` and `docs/adr/`.
Before exploring domain concepts or design decisions, read
`docs/agents/domain.md`.
