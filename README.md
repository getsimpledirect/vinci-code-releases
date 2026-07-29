# Vinci Code

**Vinci Code is a coding agent that runs in your terminal.**

This repository is where you **report issues** and **download releases**. The source is private;
everything user-facing — bug reports, feature requests, release notes — happens here.

## Install

Requires Node.js v22.19 or newer.

```sh
curl -fsSL https://vinci.getsimpledirect.com/install | sh
```

Then run `vinci` and type `/login` to connect.

Vinci Code updates itself: signed releases install automatically before your next task, so you
normally never run the installer twice.

## Report a bug or request a feature

Open an issue using one of the templates:

- **[Report a bug](../../issues/new?template=bug.yml)** — something is broken or behaves wrong
- **[Request a feature](../../issues/new?template=feature.yml)** — something is missing or awkward

Two things make a report genuinely useful:

1. **What you expected versus what happened.** Concrete beats general.
2. **Your version** — run `/version` inside Vinci Code, or `vinci --version`.

Please don't paste API keys, tokens, or private source. If reproducing the problem needs
something sensitive, say so in the issue and we'll find another way.

## Staying up to date

Vinci Code updates itself — signed releases install automatically before your next task — so the
install command above is normally the only one you ever run.

Release notes are published under [Releases](../../releases). Check `/version` inside Vinci Code to
see what you're on.

## Privacy

Vinci Code is zero-data-retention by default: your conversations and code are not stored
server-side. Issues you file here are public — treat them as public.

## Credits and license

Vinci Code is built and maintained by [SimpleDirect](https://getsimpledirect.com).

It is a thin fork of **[Pi (pi-mono)](https://github.com/badlogic/pi-mono)**, Copyright (c) 2025
Mario Zechner, used under the MIT License. Upstream Pi source is used unmodified; SimpleDirect's
additions live in a separate directory. The MIT License and copyright notice are retained per the
license terms.
