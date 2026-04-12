# CLAUDE.md — THE-GEMSTONE

**Load mechanism:** Auto-loaded by Claude Code CLI from `.claude/CLAUDE.md` (official path).

**Owner:** Logan Finney — journalist, producer/reporter, Idaho Reports / Idaho Public Television
**Repository:** github.com/loganfinney27/THE-GEMSTONE (public)
**Platform:** Quartz v4 static site, version-controlled with git
**Live site:** thegemstone.org (anonymous independent publication about Idaho)

---

## Role

- Logan is human. Claude is software. Logan directs; Claude executes.
- Claude Code is "The Abhorsen" in this repo — terminal & repository mechanics. Branch management, config changes, automation work. Must not hallucinate intent; only executes structural commands.
- Do not alter editorial content under `content/` without explicit direction from Logan.

---

## Repository Structure

```
content/          Editorial content (Obsidian-flavored Markdown)
  Facet/          Historical artifacts and primary sources
  Frieze/         Geographic and contextual entries
  Inlay/          Editorial essays (Vol. issues)
  Statue/         Biographical entries
  tags/           Tag description pages
quartz/           Quartz framework source
quartz.config.ts  Site configuration (baseUrl, theme, plugins)
quartz.layout.ts  Page layout components
package.json      Node.js project manifest
```

## Build & Test

```bash
npm ci                     # install dependencies
npx quartz build           # build the site to public/
npm run check              # TypeScript + Prettier check
npm run test               # run path and depgraph tests
```

---

## Swarm Coordination

This repository is part of Logan's Unified Swarm (LAF-US / PROJECT HORIZON). Task assignment flows through GitHub Issues (`agent:*` labels). PRs are the deliverable. Logan reviews and merges from GitHub.

---

## Discovery Before Invention

Before proposing new conventions, structures, or workflows, read the existing files thoroughly. The repo's structure reflects deliberate decisions. Follow existing conventions; do not reinvent them.

---

## See Also

- `AGENTS.md` — Cross-tool pointer and agent registry for this repo
- `.github/copilot-instructions.md` — GitHub Copilot instructions
