# Triage labels

## Status: undecided

The existing labels and triage conventions in `DUNE/ArCubeOptSim`
could not be inspected during setup. No label mapping has been
selected or verified.

Prefer the repository's existing labels over Matt Pocock's defaults.
The canonical roles below describe meanings, not labels to create
or apply.

| Canonical role | Repository label | Meaning |
| --- | --- | --- |
| `needs-triage` | Undecided | Maintainer needs to evaluate the issue |
| `needs-info` | Undecided | Waiting for more information |
| `ready-for-agent` | Undecided | Fully specified and ready for agent implementation |
| `ready-for-human` | Undecided | Requires human implementation |
| `wontfix` | Undecided | Will not be actioned |

## Resolving the mapping

Before applying triage labels, inspect the repository's existing
labels and how maintainers use them on issues. Browser access is
acceptable:

- Labels: https://github.com/DUNE/ArCubeOptSim/labels
- Issues: https://github.com/DUNE/ArCubeOptSim/issues

Read relevant issue descriptions and comments to understand
conventions.

If `gh` is installed and authenticated later, these optional
read-only commands may help:

- `gh label list --repo DUNE/ArCubeOptSim --limit 100`
- `gh issue list --repo DUNE/ArCubeOptSim --state all --limit 100 --json number,title,labels`

Map roles only where the existing conventions support the mapping.
Leave uncertain roles undecided and ask the user rather than
inventing a mapping.

While the mapping is undecided, report triage recommendations in
prose without applying labels.

## Setup constraint

Do not create, rename, delete, or otherwise change GitHub labels
as part of this setup. Do not apply or remove issue labels as part
of this setup.
