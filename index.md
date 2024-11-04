# Voice AI Assistant Documentation

## Overview
This repository contains the technical and product documentation for the Voice AI Assistant project - an AI-powered personal productivity tool focused on intelligent task and time management.

## Quick Links
- [Documentation Map](docs/00.2.Documentation-Map.md)
- [Product Vision](docs/01.PVD.md)
- [Technical Design](docs/03.TDD.md)
- [Development Backlog](docs/05.Backlog-Development.md)

## Repository Structure
Based on the GitHub Pages settings and documentation structure, let's update the README.md and repository structure:

1. First, rename `README.MD` to `index.md` for GitHub Pages to recognize it as the main page:

```markdown:_files/docs_SandrukAI/scrum-ai-focus-for-adhd-with-tracking-and-asistance/index.md
# Voice AI Assistant Documentation

## Overview
This repository contains the technical and product documentation for the Voice AI Assistant project - an AI-powered personal productivity tool focused on intelligent task and time management.

## Quick Links
- [Documentation Map](docs/00.2.Documentation-Map.md)
- [Product Vision](docs/01.PVD.md)
- [Technical Design](docs/03.TDD.md)
- [Development Backlog](docs/05.Backlog-Development.md)

## Repository Structure
```bash
.
├── index.md               # Main documentation page
├── .gitignore
├── .cursorignore
└── docs/                 # Documentation directory
    ├── 00.2.Documentation-Map.md
    ├── 01.PVD.md
    ├── 02.PRD.md
    ├── 03.TDD.md
    ├── 04.Lean-Canvas.md
    ├── 05.Backlog-Development.md
    └── system/
        └── 00.1.timeline-upgrades.md
```

## Document Conventions
- All documentation in Markdown format
- Semantic versioning (v1, v2, v3)
- Cross-referenced using relative links
- SSOT (Single Source of Truth) principles

## GitHub Pages Navigation
This documentation is available at:
- Main site: [developerisnow.github.io/scrum-ai-focus-for-adhd-with-tracking-and-asistance](https://developerisnow.github.io/scrum-ai-focus-for-adhd-with-tracking-and-asistance)
- Documentation Map: [/docs/00.2.Documentation-Map.md](/docs/00.2.Documentation-Map.md)
```

2. Create a `.nojekyll` file in the root to ensure proper rendering of files starting with underscore.

3. Update GitHub Pages settings:
- Source branch: `main`
- Source folder: `/ (root)`
- Enforce HTTPS: ✅ (already enabled)

4. The repository structure should match the tree in Documentation Map:
```bash
startLine: 2
endLine: 17
```

These changes will:
1. Enable proper GitHub Pages navigation
2. Maintain documentation structure
3. Provide clear navigation links
4. Follow GitHub Pages best practices

Would you like me to provide any additional configuration details?