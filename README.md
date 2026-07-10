# agent-skills

[![skills.sh](https://skills.sh/b/jackaranaram/skills)](https://skills.sh/jackaranaram/skills)

Collection of AI agent skills for software development workflows.

## Skills

| Skill | Description | Install |
|---|---|---|
| [daily-init](./daily-init/SKILL.md) | Single entry point for daily work — health check, session recap, breach detection, action menu | `npx skills add jackaranaram/agile --skill daily-init` |
| [git-workflow-manager](./git-workflow-manager/SKILL.md) | Full Git lifecycle — create HU+branch, branch from existing HU, safe push with dry-run merge | `npx skills add jackaranaram/agile --skill git-workflow-manager` |
| [project-context-kit](./project-context-kit/SKILL.md) | Generate/update project context suite (6 docs + AGENTS.md + README.md + DESIGN.md) | `npx skills add jackaranaram/agile --skill project-context-kit` |

## Install all skills

```bash
npx skills add jackaranaram/agile
```

## Install individual skills

```bash
npx skills add jackaranaram/agile --skill daily-init
npx skills add jackaranaram/agile --skill git-workflow-manager
npx skills add jackaranaram/agile --skill project-context-kit
```
