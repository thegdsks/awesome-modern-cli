# About Awesome Modern CLI

## What is this?

A curated collection of modern command-line tools that replace or improve on classic Unix utilities. The kind of tools that make you wonder how you ever lived without them.

## Why does this exist?

Lists like [modern-unix](https://github.com/ibraheemdev/modern-unix) covered about 30 tools before going inactive. [awesome-cli-apps](https://github.com/agarrharr/awesome-cli-apps) has hundreds of entries but no way to tell what replaces what.

This list fills that gap. Every entry is organized by what classic tool it replaces, what language it's written in, and why you'd want to switch.

## How tools get included

A tool needs to meet all of these:

- **100+ GitHub stars** (shows real adoption, not just a weekend project)
- **Active maintenance** (at least one commit in the last 12 months)
- **Solves a real problem** (not a toy or proof of concept)
- **Installable** (published binaries, package manager, or straightforward build)

Tools that stop being maintained get reviewed and eventually removed. The weekly link checker catches repos that go offline.

## How it's organized

Tools are grouped by what they replace. If you use `grep` and want something better, go to [Text Search](README.md#text-search). If you use `top` and want something prettier, go to [System Monitoring](README.md#system-monitoring).

Each entry follows this format:

```
- [tool-name](url) - One sentence description. `Language`
```

Everything is alphabetically sorted within sections.

## The numbers

The list skews heavily toward Rust (about 52% of entries) and Go (about 16%). This isn't by design. It just turns out that when you search for "modern X replacement," the top result is usually written in one of those two languages.

## Who maintains this?

[Gagan Deep Singh](https://github.com/thegdsks). Contributions from the community via pull requests.
