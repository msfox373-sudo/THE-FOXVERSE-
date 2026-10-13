# The Foxverse

The Foxverse is an independent digital company that builds commercial, production-ready digital systems and licenses them repeatedly.

**Model:** Build once → improve → license repeatedly → customize when needed.

## Repository map

| Path | Purpose |
|---|---|
| `company/` | Identity, strategy, operations, policies |
| `engineering/` | Standards, workflows, architecture, security, testing, releases |
| `projects/` | One folder per product (code, docs, tests, config, changelog) |
| `shared/` | Reusable components, utilities, schemas, templates |
| `quality/` | Checklists, test strategies, release gates |
| `docs/` | Company overview, roadmap, architecture decisions (ADRs) |

## Start here

1. Business model: `company/strategy/BUSINESS_MODEL.md`
2. Engineering rules: `engineering/standards/`
3. Plans: `docs/ROADMAP.md`
4. Why things are the way they are: `docs/DECISIONS/`

## Rules of the repository

- This repository is **private**. The public website lives in a separate public repository.
- No secrets, keys, or customer data are ever committed. See `SECURITY.md`.
- Every product follows the standards in `engineering/standards/`.
- Every significant decision is recorded as an ADR in `docs/DECISIONS/`.

## License

All rights reserved. See `LICENSE`.
