# Mandatory Team Repository Standard

Each approved team must create its own GitHub repository.

## Repository Name

```text
MTL-DA-005-<team-name>
```

Example:

```text
MTL-DA-005-compliance-insight-lab
```

## Visibility

The repository may remain private during delivery.

If private, add the designated Mettelo reviewer GitHub account before final submission.

## Mandatory Structure

```text
MTL-DA-005-<team-name>/
│
├── README.md
├── CONTRIBUTIONS.md
├── requirements.txt
├── .gitignore
│
├── data/
│   ├── README.md
│   ├── raw/
│   └── processed/
│
├── docs/
│   ├── 01-discovery/
│   ├── 02-data-model/
│   ├── 03-kpi-catalogue/
│   ├── 04-compliance-analysis/
│   ├── 05-geographic-workload/
│   ├── 06-prioritisation-framework/
│   └── 07-technical-handover/
│
├── sql/
├── src/
├── notebooks/
├── analysis/
├── dashboard/
│   └── README.md
│
├── deliverables/
│   ├── executive-briefing/
│   └── presentation/
│
└── submission/
    └── FINAL_SUBMISSION.md
```

## README Requirements

The root README must contain:

- project ID/title;
- team name;
- members/roles;
- business-problem summary;
- solution overview;
- data acquisition instructions;
- architecture/data-flow summary;
- reproduction steps;
- dashboard link;
- deliverable links;
- limitations;
- source attribution.

## Git Workflow

Minimum expectations:

- issues for meaningful work;
- descriptive commits;
- branches for substantial changes;
- pull requests for material merges;
- peer review where practical;
- visible contribution from team members.

Do not upload the entire project in one final commit.

## Data Rules

Do not manually modify raw source data.

If automated extraction is used, keep the extraction process reproducible.

## Reproducibility

A technically competent reviewer must be able to reconstruct the analytical workflow from the repository instructions.

## Contribution Evidence

`CONTRIBUTIONS.md` must record actual individual contributions.

Commit count alone is not sufficient proof of contribution.
