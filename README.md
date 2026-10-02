# UI/UX Pro Max project snapshot

This repository has a root documentation layer and a nested project directory at `ui-ux-pro-max-skill-main/`. The nested directory contains Claude Code skill files, plugin metadata, design data and scripts, plus a CLI package.

## Start here

- [Nested project README](ui-ux-pro-max-skill-main/README.md): project scope and usage
- [CLI README](ui-ux-pro-max-skill-main/cli/README.md): CLI commands and development notes
- [Root security guidance](SECURITY.md): review design data and tool permissions
- [Content review](CONTENT_REVIEW.md): checked paths and evidence limits

The root itself has no `SKILL.md`, `package.json`, or `docs/README.md`. The recursive tree on `docs/ui-ux-skill-evidence-and-scope` confirms those sources exist under the nested project directory instead. The nested README identifies an external project URL; synchronization with that upstream source was not verified. Its fixed counts and accessibility badge are copied claims and were not independently validated.

## Evidence limits

The tree confirms source-file presence only. The CLI was not run, and no generated design, accessibility result, benchmark, compatibility, or platform conformance was tested. Skill guidance is not proof of design quality or legal compliance. The nested CLI README's assistant target list is incomplete for this snapshot; check the [local CLI type definitions](ui-ux-pro-max-skill-main/cli/src/types/index.ts) for declared identifiers.
