# Use the Arsenal skill

The maintained source is [skills/manage-ai-arsenal](skills/manage-ai-arsenal/SKILL.md).
The same folder works for Codex and Claude. It contains instructions and an entry
template, not credentials, an installer, an MCP server or a copy of the catalog.
Each agent still needs its own access to the private repositories.

## On this Windows computer

Personal copies can be placed in the host's skill directory:

- Codex's existing local setup: `C:\Users\laura\.codex\skills\manage-ai-arsenal`.
- Claude Code: `C:\Users\laura\.claude\skills\manage-ai-arsenal`.

These two copies were installed and checked against the source on October 30,
2026. Discovery/activation still needs to be checked in each host's skill picker.

Current Codex documentation also lists `~/.agents/skills` for user skills and
`.agents/skills` for repository skills. Install in one discovery location per
host; do not add duplicate copies under both paths. This machine's existing
Codex skill setup uses `.codex/skills`.

Start a new session and check the skill picker. In Codex CLI/IDE, invoke
`$manage-ai-arsenal`; in Claude Code, invoke `/manage-ai-arsenal`. Natural language
such as “add these to the arsenal” can also select the skill when available.
Files installed on this computer do not install into Replit, another computer,
Claude's hosted chat, or another OpenAI environment.

## Claude chat and Cowork

Download the separately supplied `manage-ai-arsenal.zip`, which contains the
skill folder with SKILL.md at its top level. In Claude, open Customize > Skills,
choose + / Create skill > Upload a skill, upload the ZIP and enable it. Code
execution/file creation and account or organization settings must permit skills.
Local Claude Code skills and uploaded Claude chat skills are separate installs.

## ChatGPT

The ChatGPT desktop app supports standalone skills and a Skills sidebar; select
an available skill with an @ mention. Installing locally does not prove the skill
is enabled in every ChatGPT mode, account, browser or cloud environment. Check
the skill picker there. If that surface offers a custom-skill import, use the
provided folder/ZIP as its accepted format; an ordinary chat attachment alone
does not establish persistent installation.

For broader ChatGPT web/mobile distribution, OpenAI documents plugins as the
cross-surface packaging route. This task supplies a standalone skill, not an
installed plugin. When a surface cannot install it, attach SKILL.md and its
reference for that chat and explicitly ask the agent to follow it; this is a
per-chat fallback. GitHub writes still require tools and repository access.

## Updates

Edit the source in this repository, validate it, then deliberately replace the
installed copies or upload a new ZIP. Refresh/restart the host if needed and
check the skill picker. Installed/uploaded copies are snapshots. There is no
background update job, automatic catalog synchronization, or automatic permission
grant. Do not overwrite an independently edited installed copy without review.

## Documentation checked October 30, 2026

- [OpenAI: build skills](https://learn.chatgpt.com/docs/build-skills)
- [OpenAI: skills and plugins](https://learn.chatgpt.com/docs/skills-and-plugins)
- [Anthropic: agent skills](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/overview)
- [Anthropic: use skills in Claude](https://support.claude.com/en/articles/12512180-use-skills-in-claude)
