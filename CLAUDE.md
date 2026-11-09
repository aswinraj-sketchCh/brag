# /brag — agent rules

Agent skills that turn a project into a short launch video: `skills/brag/` (Hyperframes workflow) and `skills/brag-slim/` (single-file, no bundled assets). The launch site lives in `docs/`.

## Checks
- `node scripts/check-brag-slim.mjs` — validates the brag-slim skill.
- `node scripts/check-docs.mjs` — validates `docs/index.html` local references.
Run both before pushing.

## Rules
- `brag-slim` must stay a single SKILL.md with no bundled assets.
- Keep `plugin.json` and README install instructions consistent with the skill names.
