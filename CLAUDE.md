# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Repository Is

This is the **deployed output** (GitHub Pages) for https://himalayasharma.github.io/. It contains only generated HTML, CSS, JS, and static assets — **do not edit files here directly**. All changes will be overwritten on the next build.

## Source Repository

The Hugo source is at `/home/himalaya/starter-hugo-academic/`. That is where all content editing, theme configuration, and development should happen. It has its own CLAUDE.md with detailed architecture guidance.

## Build Workflow

```bash
cd /home/himalaya/starter-hugo-academic
hugo --gc --minify        # Build site into public/
```

The built output from `public/` is then copied/deployed to this repository. Hugo version 0.97.3 is required (pinned in netlify.toml). Netlify also auto-deploys on push to the source repo.

## Updating This Repository

After building in the source repo, copy the `public/` output here and commit. Do not manually edit generated files — make changes in the source repo instead.
