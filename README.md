# Emil Design Skills — Cowork plugin

A repackaging of **[emilkowalski/skills](https://github.com/emilkowalski/skills)** as a Claude **plugin** so the full set can be installed in **Cowork** (and Claude Code) by URL, instead of the `npx skills add` flow.

All 15 skills, their instructions, and supporting files are Emil Kowalski's original work, licensed MIT (see [LICENSE](./LICENSE)). This repo only adds the plugin manifests; it does not modify the skills.

## What's inside

15 design-engineering & animation skills:

`animate` · `animate-expo` · `animation-performance` · `animation-vocabulary` · `apple-design` · `ask-sonner` · `break-ui` · `emil-design-eng` · `find-animation-opportunities` · `improve-animations` · `mobile-native` · `pick-ui-library` · `prototype` · `review-animations` · `write-swift`

## Install in Cowork

1. In Cowork: **Customize → Plugins → Add**, and point it at this repo: `https://github.com/krystianaskywetzel-eng/emil-design-skills`
2. Install. The skills become available in your Cowork sessions.

> Menu labels vary between app versions; look for the Plugins section under Customize.

## Install in Claude Code

```bash
/plugin marketplace add krystianaskywetzel-eng/emil-design-skills
/plugin install emil-design-skills
```

## Updating

To pull in upstream changes from Emil's repo later, re-copy the skills into `plugins/emil-design-skills/skills/` from [emilkowalski/skills](https://github.com/emilkowalski/skills) and commit.

## Credit

Skills by **[Emil Kowalski](https://github.com/emilkowalski)** — [emilkowalski/skills](https://github.com/emilkowalski/skills). This is an unofficial repackaging for plugin-based installation; for updates, re-sync from the upstream repo.
