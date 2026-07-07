# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

This is **Awesome WebSockets** — a curated "awesome list" of WebSocket-related resources. There is no application code, build system, or test suite. The entire content is a single Markdown document, `README.md`. Contributions are edits to that file.

## Repository structure

- `README.md` — the entire curated list. This is the only file that receives content changes.
- `CONTRIBUTING.md` — contribution rules (link format, ordering, capitalization).
- `.travis.yml` — CI that validates all links in `README.md`.
- `LICENSE.MD` — CC-BY license.

## Validating links (the only "test")

CI runs [`awesome_bot`](https://github.com/dkhamsing/awesome_bot) to check every link resolves. To reproduce locally:

```sh
gem install awesome_bot
awesome_bot README.md --allow-dupe --allow-redirect
```

`--allow-dupe` and `--allow-redirect` must be passed or CI will not match — some entries intentionally repeat links across categories, and many links redirect.

## Editing conventions (enforced when adding entries)

- Entry format is exactly: `- [Resource Name](link) - Short description.` (space-hyphen-space separator, trailing period).
- Do not repeat the resource name inside the description.
- Add entries in **alphabetical order within their category**. Note: existing categories are only loosely sorted, so match the local pattern of the section you are editing rather than assuming strict global order.
- Titles use [title capitalization](http://grammar.yourdictionary.com/capitalization/rules-for-capitalization-in-titles.html).
- Categories are organized primarily by programming language under "Tools per Language" (Agnostic, C, C++, Go, Java VM → Clojure/Java/Scala, Node.js, Python, Rust, etc.), plus top-level sections: CLI Tools, Real Life Stories, Security, and Theory (Articles & Papers, Talks, Tutorials, Books, Sites).

## Table of contents

Both `README.md` and `CONTRIBUTING.md` contain a DocToc-generated TOC wrapped in `<!-- START doctoc ... -->` / `<!-- END doctoc -->` markers. **Do not hand-edit the TOC.** After adding or renaming a section heading, regenerate it:

```sh
npx doctoc README.md
```
