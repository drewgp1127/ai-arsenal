# Arsenal skill handoff

Owner approved building one shared capture/review/find/maintenance skill with
manual promotion and setup guidance on October 30, 2026 Pacific. Scope includes
both resource collections, with catalog work separate from tool installation.

Maintained source: skills/manage-ai-arsenal. SKILL-SETUP.md documents personal
Codex/Claude Code folders, Claude upload, ChatGPT discovery and cross-environment
limits. Personal installs and upload packages are snapshots, not a sync service.

Global repository was clean at a5cfcdb5a74ddab122e02e90b041f4e00a198ec3 before this
task. No FirstIQ application or instruction files are changed by this task; its
existing catalog and PR workflow govern any future edits made using the skill.

Validation: run the bundled skill-creator quick_validate.py on the source skill;
check relative Markdown references and the repository diff; inspect the ZIP
members; compare installed files against the source. These checks validate the
package, not host activation or a live resource mutation. No real inbox entries
are added just to test the skill. Verify installation/activation separately in
each host's skill picker and retain any reported setup limitations.

Completed on this computer: source validated with the bundled quick validator,
all repository-relative Markdown links resolved, and the ZIP contains exactly
SKILL.md, agents/openai.yaml and references/entry-template.md under one skill
folder. The default Python lacked PyYAML; a temporary workspace-only validation
dependency and Python's UTF-8 mode allowed the unmodified validator to pass.
No global Python dependency change was made.

Installed copies under C:/Users/laura/.codex/skills/manage-ai-arsenal and
C:/Users/laura/.claude/skills/manage-ai-arsenal match the source by SHA-256.
Host activation is not verified in this existing chat. Claude chat and other
ChatGPT surfaces have not been installed or enabled. Upload ZIP is available in
the sibling ai-arsenal-staging folder; it contains no catalogs or secrets.
