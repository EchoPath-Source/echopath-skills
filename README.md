# EchoPath Skills

Public skill hub for EchoPath XR / Echo Labs workflow skills.

This repository is structured as a marketplace-ready directory of lightweight AI skills, templates, and workflow agents. Each skill folder is designed to be discoverable on skill marketplaces such as ClawHub/OpenClaw while pointing users to the full paid version on Gumroad when appropriate.

## Current skills

| Skill | Status | Purpose |
|---|---:|---|
| [OSF Pre-Registration Generator](skills/osf-preregistration/) | Free / Lite | Helps independent researchers draft clearer OSF-ready pre-registration plans before data collection. |
| [Literature Synthesis Builder](skills/literature-synthesis/) | Free / Lite | Turns source notes and papers into structured, balanced literature syntheses. |
| [Creator Project Brief Architect](skills/creator-project-brief/) | Free / Lite | Converts loose project ideas into execution-ready briefs with milestones and risk planning. |

## Repository structure

```text
echopath-skills/
├── skills/
│   └── osf-preregistration/
│       ├── SKILL.md
│       ├── README.md
│       ├── phases.md
│       └── free-checklist.md
├── marketplace/
│   ├── gumroad-listing-osf-preregistration.md
│   └── clawhub-listing-osf-preregistration.md
├── assets/
│   └── README.md
└── README.md
```

## Free vs. paid strategy

The public repository contains free/lite versions that demonstrate the workflow and help marketplace users discover the skill. Paid Gumroad versions may include expanded templates, complete phase prompts, example outputs, updates, and support materials.

## Public positioning

EchoPath Skills focuses on practical creator, research, and development workflows. The goal is to package repeatable workflows into clear, useful, downloadable tools that save time and improve output quality.

## Notes

This repository is public-facing. Do not commit private credentials, proprietary kernel code, private simulation data, or confidential EchoPath XR internals here.
