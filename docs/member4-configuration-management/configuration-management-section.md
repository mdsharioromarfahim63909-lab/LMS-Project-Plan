# 7. Configuration Management

> Report section prepared by **Member 4 — Md Sharior Omar Fahim (63909)**, GitHub & Configuration Management.
> Section number 7 follows Member 3's Risk & Issue Management section (Section 6).

## 7.1 Configuration Management Overview

Configuration management (CM) is the discipline of tracking and controlling changes to
project deliverables, documentation, and any other project artifacts throughout the
project lifecycle. For the LMS project, CM ensures that all project documents, design
files, and reports are stored securely, that changes are tracked with a full history of
who changed what and when, and that team members can collaborate without overwriting one
another's work.

The primary CM tool selected for this project is **GitHub**, a cloud-based platform built
on the **Git** version-control system. GitHub provides repository hosting, commit history,
branching, and collaboration features that together satisfy the configuration-management
requirements of the project.

## 7.2 Configuration Management Process

The CM process followed in this project consists of the following steps:

1. **Repository Setup** — A central GitHub repository (`LMS-Project-Plan`) was created to
   host all project artifacts.
2. **Folder Organisation** — Deliverables were organised into member-specific folders
   under a `docs/` directory for traceability.
3. **Version Tracking** — Every change is recorded as a Git commit with a descriptive
   message, timestamp, and author identity, creating a complete audit trail.
4. **Branching Strategy** — Feature branches (for example, `feature/cm-documentation`) were
   used to develop documentation in isolation before merging into the `main` branch,
   preventing incomplete work from affecting the baseline.
5. **Change Control** — All changes to the repository are visible in the commit history.
   Any file modification, addition, or deletion is logged permanently.
6. **Backup and Redundancy** — The repository exists both locally (on team members'
   machines) and remotely (on GitHub's servers), providing redundancy against data loss.

## 7.3 Repository Structure

```
LMS-Project-Plan/
├── README.md
├── .gitignore
├── docs/
│   ├── member1-introduction/
│   │   └── Member1.pdf
│   ├── member2-planning/
│   │   └── Member2.pdf
│   ├── member3-risk-management/
│   │   └── Member3.docx
│   ├── member4-configuration-management/
│   │   └── configuration-management-section.md
│   └── member5-final-report/
└── screenshots/
    ├── 01-repo-creation.png
    ├── 02-folder-structure.png
    └── ...
```

## 7.4 Version Control Evidence

*(Draft — commit table and screenshot references to be completed in the next revision.)*

A summary of the key commits made during the project will be inserted here, drawn directly
from the repository's commit history (`git log`).
