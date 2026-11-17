# Paradev Agent Skills

Paradev was formerly called Superset. Skill names and the `superset` CLI keep the old name.

Official [agent skills](https://skills.sh) from [Paradev](https://paradev.com) — the desktop app for running 10+ parallel AI coding agents on your machine, each in its own isolated Git worktree.

## Install

```bash
npx skills add paradevai/skills
```

## Skills

> These ship automatically with the [Paradev desktop app](https://paradev.com) — if you use Paradev, your agents already have them (namespaced `superset:*` in Claude Code). Install from here for standalone agents.

| Skill | Use it to |
| --- | --- |
| [`superset-orchestrate`](skills/superset-orchestrate/SKILL.md) | Coordinate multiple terminal coding agents through the Paradev CLI with isolated workspaces, follow-ups, dependency tracking, and structured handoffs. |
| [`superset-setup`](skills/superset-setup/SKILL.md) | Make a repository Paradev-ready: author `.superset/config.json` setup scripts and verify them with a real workspace. |
| [`superset-automate`](skills/superset-automate/SKILL.md) | Turn a recurring chore into a scheduled Paradev automation and review its first run. |
| [`superset-standup`](skills/superset-standup/SKILL.md) | Digest what your agents did across workspaces, tasks, and terminals: what needs review, what's blocked. |
| [`superset-doctor`](skills/superset-doctor/SKILL.md) | Diagnose and fix Paradev problems: expired auth, offline hosts, stale versions. |
| [`superset-feedback`](skills/superset-feedback/SKILL.md) | File a bug report or feature request — privately to the Paradev team or as a public GitHub issue. |
| [`superset-10x`](skills/superset-10x/SKILL.md) | Audit how you use Paradev and learn the advanced features you're missing. |
| [`superset-contribute`](skills/superset-contribute/SKILL.md) | Set up a Paradev open-source contribution end to end, following the repo's contribution rules. |
| [`superset-mcp`](skills/superset-mcp/SKILL.md) | Connect an agent to the Paradev MCP server: setup one-liners for Claude Code, Codex, and Gemini CLI, the OAuth/API-key auth flow, and the 27-tool catalog. |

`superset-orchestrate` replaces the former `superset` and `superset-orchestration` skills.

## Resources

- [Documentation](https://docs.paradev.com) · [llms.txt](https://paradev.com/llms.txt)
- [MCP server docs](https://docs.paradev.com/mcp-server)
- [Agent auth walkthrough](https://paradev.com/auth.md)
- [Paradev on GitHub](https://github.com/paradevai/paradev)
