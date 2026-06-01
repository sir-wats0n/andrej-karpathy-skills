# Karpathy guidelines — user rule (copy-paste)

Add in **Cursor Settings → Rules → User Rules** (or replace the existing `skill\karpathy-guidelines` entry).

## Compact rule (recommended)

```markdown
When writing or editing code, follow Karpathy guidelines:

1. **Think first** — State assumptions; ask if unclear; surface tradeoffs. Do not pick an interpretation silently.
2. **Simplicity** — Minimum code for the request. No extra features, abstractions, config hooks, or defensive code beyond scope. If overcomplicated, simplify.
3. **Surgical edits** — Change only what was asked; match existing style. Remove orphans your edit created, not pre-existing dead code unless asked.
4. **Verifiable goals** — Define how to verify (tests, commands, checks). For multi-step work, list steps each with a verify line.

Use judgment on trivial one-liners; apply full rigor on non-trivial work.
```

## Also installed (file-based)

`%USERPROFILE%\.cursor\rules\karpathy-guidelines.mdc` — global rule with `alwaysApply: true`. New chats should pick it up automatically; if not, use the User Rules paste above.
