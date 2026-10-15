# Patient-controlled sedation

## Description

A clinical quality-improvement project evaluating patient-controlled sedation. The project is currently in the planning phase: drafting a guideline, a patient questionnaire, and an evaluation plan; arranging meetings with relevant units; and preparing for implementation.

## Team and contact

Martin Gerdin Wärnberg and Sara Ekvall. Contact: martin.gerdin-warnberg@regionstockholm.se.

## Data and approvals

Approvals are recorded in `doc/approvals/`. Relevant regional documents referenced during planning are collected in the project notebook (`doc/notebook.qmd`). Patient-level data are kept out out of this repository until the project is ready for archiving.

## Setup and workflow

Setup instructions go here once the analysis environment and tools are decided. The project notebook is a Quarto document; render it with:

```
quarto render doc/notebook.qmd
```

## Project layout

| Location | Contents |
| --- | --- |
| `data/` | Non-sensitive metadata: data dictionaries, code lists, and schemas. |
| `doc/notebook.qmd` | Dated decisions, methods, and analysis notes. |
| `doc/project-planning/` | Concept notes and proposals. |
| `doc/approvals/` | Departmental permissions. |
| `doc/protocols/` | Protocols, analysis plans, and procedures. |
| `results/` | Generated data, tables, and figures that are safe to store here. |
| `src/` | Data-access, cleaning, and analysis code. |
| `CITATION`, `LICENSE` | Citation instructions and reuse terms. |

Use document subfolders only when needed. Small projects can keep documents directly in `doc/`. Keep folder guidance in this README rather than separate folder READMEs.

## Working practices

- Keep raw data unchanged in approved storage. Record where the data came from, how to access them, and how they were changed.
- Never commit sensitive data or credentials. Avoid committing large or easily regenerated outputs.
- Use descriptive filenames and `YYYY-MM-DD` dates. Make analyses scriptable and test important steps.
- Track changes in version control and back up through approved locations.

## Licensing

See `LICENSE` for the terms. An open license does not give permission to share sensitive data.
