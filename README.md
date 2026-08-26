# MBA Portfolio

This repository contains polished, public-facing versions of selected MBA coursework prepared for publication through Posit Connect Cloud.

## Purpose

The portfolio is designed to showcase applied MBA work in a professional format while keeping working notes, drafts, course administration, AI-use records, and internal project files separate from published content.

## Publishing Model

- **Private academic repository:** complete working archive and source of truth
- **This public repository:** curated publication layer only
- **Quarto:** renders polished web pages
- **Posit Connect Cloud:** hosts the published portfolio online

Only finished work appropriate for public viewing should be added here.

## Structure

```text
MBA_Portfolio/
├── _quarto.yml
├── index.qmd
├── about.qmd
├── README.md
├── leadership/
│   ├── index.qmd
│   └── reimagining-leadership/
│       ├── index.qmd
│       └── references.bib
├── global-strategy/
│   └── index.qmd
└── healthcare/
    └── index.qmd
```

## Publication Standards

Each published piece should:

1. Use a professional title rather than an assignment filename when appropriate.
2. Preserve the substance of the submitted work while removing course-platform artifacts that do not help a public reader.
3. Include the assignment or project context when useful.
4. Use verified citations and a bibliography.
5. Avoid publishing confidential, proprietary, patient-identifiable, instructor-restricted, or otherwise sensitive material.
6. Keep source data private unless it is appropriate and permitted to publish.
7. Be reviewed for formatting, citation accuracy, links, visuals, and public-facing context before deployment.

## Current Publications

### Leadership

- **Reimagining Leadership: Leaders Are Not Finished Products** — MBA leadership analysis examining ongoing leader development, feedback, selection, coaching, and accountability.

## Connect Cloud

This repository is configured as a Quarto website. In Posit Connect Cloud, use:

- **Repository:** `vandelynnichols/MBA_Portfolio`
- **Branch:** `main`
- **Primary file:** `_quarto.yml`

## Workflow

1. Finalize the academic submission in the private course repository.
2. Create or update the polished Quarto publication in this repository.
3. Verify citations, references, links, visuals, and public-facing language.
4. Commit the approved publication files here.
5. Allow Connect Cloud to republish from `main`.

The private course repository remains the academic archive. This repository is the curated public portfolio.