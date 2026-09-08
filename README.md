# Wellworn skills

Installable procedures that pair with Wellworn verdicts. Each folder is one skill in the open Agent Skills format (a `SKILL.md` with frontmatter, plus optional scripts and references).

```
npx skills add WellWorn-dev/skills
```

Every skill states the versions it was verified against and the date. When a verdict flips to RECHECK, its skill is re-verified before the flag clears.

| Skill | Verified against | Date |
|---|---|---|
| `wellworn` | Wellworn MCP | 2026-09-08 |
| `better-auth-nextjs` | better-auth 1.7.3, Next.js 16.3, drizzle-orm 0.45 | 2026-09-08 |

License: MIT.
