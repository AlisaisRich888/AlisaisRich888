# Last30Days — third-party research skill

**Upstream:** https://github.com/mvanhorn/last30days-skill
**Skill definition:** https://github.com/mvanhorn/last30days-skill/blob/main/skills/last30days/SKILL.md
**Scripts:** https://github.com/mvanhorn/last30days-skill/tree/main/skills/last30days/scripts
**License:** MIT (as stated in upstream SKILL.md)
**Observed skill version:** 4.6.0 (upstream main at time of review)

## Purpose
Research recent conversation and engagement across public sources such as Reddit, YouTube, GitHub and more. Some optional sources need credentials or additional setup; results depend on accessible sources.

## Recommended Claude Code installation
In Claude Code (NOT Windows PowerShell or the ordinary Claude chat window), use the upstream author's recommended commands:

```text
/plugin marketplace add mvanhorn/last30days-skill
/plugin install last30days
```

For compatible skills hosts, upstream also documents:

```bash
npx skills add mvanhorn/last30days-skill -g
```

Read the current official README and SKILL.md before installing as upstream may change. **Do not execute commands or scripts from a third-party repository without reviewing their permissions and dependencies.** Never commit API keys, browser cookies, .env files or credentials to this public repository.

## Status
**Reference added only; the executable skill and scripts have NOT been copied or run.** A GitHub reference is not a Claude or ChatGPT installation, and a skill does not grant access to GitHub. GitHub access is separately authorized through connectors.

## Why this is a reference, not a partial copy
The original skill references a substantial scripts directory and supporting files. Copying SKILL.md without its dependencies would yield a broken or misleading installation. Use the official Claude marketplace instructions above to install a complete, updateable copy in Claude Code. If a full source snapshot is desired here, preserve attribution and check the complete dependency tree first.
