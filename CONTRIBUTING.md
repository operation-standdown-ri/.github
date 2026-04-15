# Contributing to OSDRI

Thank you for considering a contribution. OSDRI's technology directly supports veterans navigating the disability claims process — your work helps real people.

## Before You Start

1. **Read [SECURITY.md](./SECURITY.md)** — understand our PHI/PII handling rules
2. **Read the repo's `CLAUDE.md`** (if present) — each project has specific context
3. **Read the repo's `README.md`** — local conventions, how to run tests

## Workflow

1. **Fork or branch** from `main`/`master`
2. **Make focused commits** — one logical change per commit
3. **Write meaningful commit messages** — explain *why*, not just *what*
4. **Open a PR** against the default branch
5. **Fill out the PR template** completely — especially the blast radius section
6. **Wait for review** — at least one approval from the repo's CODEOWNERS

## PR Requirements

- ✅ Passes CI (tests, linters)
- ✅ Blast radius documented (what breaks if this is wrong?)
- ✅ PHI/PII-free (no veteran data, even in examples)
- ✅ Security implications considered
- ✅ Breaking changes flagged in title: `BREAKING:`

## Questions

Ask in the PR itself, or email sschultz@osdri.org.

## First-Time Contributors

Look for issues labeled `good-first-issue` or `help-wanted`.
