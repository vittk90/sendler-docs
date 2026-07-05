# Sendler GitBook — bilingual docs (EN + RU)

Two mirrored doc trees, each with its own `SUMMARY.md`:

```
en/   ← English (primary)
ru/   ← Русский
```

## How to publish on GitBook

**Option A — Language variants (recommended):**
1. Push this repo to GitHub.
2. In GitBook, create a Space, enable Git Sync, set **Project directory = `en`**.
3. Create a second Space (or a variant of the first), Git Sync the same repo with **Project directory = `ru`**.
4. Group both spaces in one collection / link them as language variants.

**Option B — Single space:**
Point Git Sync at `en/`, and add the RU pages as a "Русская версия" group inside `en/SUMMARY.md` (move `ru/` under `en/`).

## Structure (both languages)

- Welcome / Введение
- Getting Started / Начало работы
- Trading: Market · Auctions · Portfolio
- Alchemy Lab: Overview · Crafting · Running a Lab · Economics & Glossary
- Adam Mint
- Explorer: Overview · Reputation · Duplo · FT Holders
- FAQ
