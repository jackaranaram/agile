# agent-skills

[![skills.sh](https://skills.sh/b/jackaranaram/skills)](https://skills.sh/jackaranaram/skills)

Collection of AI agent skills for software development workflows.

## Skills

| Skill | Description | Install |
|---|---|---|
| [daily-init](./daily-init/SKILL.md) | Single entry point for daily work — health check, session recap, breach detection, action menu | `npx skills add jackaranaram/skills --skill daily-init` |
| [git-workflow-manager](./git-workflow-manager/SKILL.md) | Full Git lifecycle — create HU+branch, branch from existing HU, safe push with dry-run merge | `npx skills add jackaranaram/skills --skill git-workflow-manager` |
| [project-context-kit](./project-context-kit/SKILL.md) | Generate/update project context suite (6 docs + AGENTS.md + README.md + DESIGN.md) | `npx skills add jackaranaram/skills --skill project-context-kit` |
| [skill-creator](./skill-creator/SKILL.md) | Create, iterate, and optimize AI agent skills with benchmarking and evals | `npx skills add jackaranaram/skills --skill skill-creator` |
| [docs-suite-creator](./docs-suite-creator/SKILL.md) | Generate/update 6 documentation files (ARCHITECTURE.md, CONTRACTS.md, DATABASE.md, MODEL.md, ROADMAP.md, SCOPE.md) | `npx skills add jackaranaram/skills --skill docs-suite-creator` |
| [safe-git-workflow](./safe-git-workflow/SKILL.md) | Safe Git push and PR creation workflow with conflict prevention and validation checks | `npx skills add jackaranaram/skills --skill safe-git-workflow` |
| [tbd-branch-creator](./tbd-branch-creator/SKILL.md) | Git branch creation using Trunk-Based Development with Conventional Commits | `npx skills add jackaranaram/skills --skill tbd-branch-creator` |

## Install all skills

```bash
npx skills add jackaranaram/skills
```

## Install individual skills

```bash
npx skills add jackaranaram/skills --skill daily-init
npx skills add jackaranaram/skills --skill git-workflow-manager
npx skills add jackaranaram/skills --skill project-context-kit
npx skills add jackaranaram/skills --skill skill-creator
npx skills add jackaranaram/skills --skill docs-suite-creator
npx skills add jackaranaram/skills --skill safe-git-workflow
npx skills add jackaranaram/skills --skill tbd-branch-creator
```
