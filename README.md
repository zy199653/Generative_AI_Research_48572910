# AI_Research

put some stuff - all data for the project


> Tip: to avoid path issues with spaces and apostrophes, consider renaming  
> `research files` → `research_files` and `tutorial assignment'` → `tutorial_assignment`.

---

## How to Navigate

- **assignment/**  
  - `instructions/` (optional): task sheets and marking rubrics  
  - `submissions/`: answers and exported PDFs

- **reference/**  
  - `papers/`: journal/conference PDFs  
  - `notes/`: reading notes (use the same filename stem as the PDF)  
  - citation exports (e.g., `references.bib`, `library.enl`) live here

- **research files/**  
  - `data_raw/`: unmodified source data (treat as restricted if sensitive)  
  - `data_clean/`: cleaned/processed datasets (record changes in a data log)  
  - `code/`: scripts or notebooks  
  - `reports/`: analysis outputs (figures, HTML/PDF reports)  
  - `logs/`: experiment logs, decisions, and provenance notes

- **tutorial assignment'/**  
  - screenshots of the repo tree, commit history/activity, and README  
  - links to branches/PRs and notes on conflict resolution

---

## Naming Conventions

- **Files:** `topic_keyword-YYYYMMDD-vNN.ext`  
  e.g., `survey_clean-20250918-v01.csv`, `eda-demographics-20250918-v02.ipynb`
- **Branches:** `feat/<short-desc>-<sid>`, `fix/<short-desc>-<sid>`, `docs/<short-desc>-<sid>`
- **Commits:** small, clear messages, e.g.  
  - `feat: add cleaned survey data and EDA notebook`  
  - `fix: correct dtype for age column`  
  - `docs: update README with navigation guide`

Consistent names improve searchability, sorting, automation, and reproducibility.

---

## How to Contribute

1. **Fork & Clone**  
   Fork this repo to your account, then clone your fork locally.

2. **Create a Branch**  
   Use the branch naming scheme above (e.g., `feat/add-survey-cleaner-12345678`).

3. **Make Changes**  
   Place files in the correct folders. Do not commit personal or sensitive data.

4. **Commit Well**  
   Make small, logical commits with meaningful messages.

5. **Push & Open a Pull Request (PR)**  
   Push your branch to your fork and open a PR against the upstream `main`.  
   In the PR description, include purpose, key changes, risks, and test notes.

6. **Review & Merge**  
   At least one reviewer approval is required.  
   Resolve merge conflicts in the PR and explain the resolution briefly.

---

## Data & Privacy

- Treat raw data, interview transcripts, and consent forms as **restricted**.  
- Prefer a **private** repository for sensitive materials.  
- Use `.gitignore` to exclude large/binary/sensitive files from version control.  
- Keep `paper submitted.pdf` read-only as an archival record; continue edits in the working draft.

---

## Reproducibility Checklist

- Log preprocessing steps and major decisions in `research files/logs/`.  
- Pin critical library versions (e.g., `requirements.txt` or notes in notebooks).  
- Export figures/tables to `research files/reports/` with descriptive filenames.

---

## What to Capture for the Tutorial Submission

- A screenshot of the **organized repo tree** (with your username visible).  
- A screenshot of the **project history/activity** (e.g., Insights → Activity).  
- A screenshot of this **README** rendered on GitHub.

---

## Maintainers

- Reviewer: _Name (GitHub @handle)_  
- Developers: _Name (GitHub @handle)_, _Name (GitHub @handle)_

