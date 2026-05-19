# Publication Decision

HarborSystems can be public in three different ways.

## Option A: Case Study Only

Best for immediate publication.

- Architecture diagrams.
- Screenshots with fake data.
- Product workflow notes.
- Public-safe API examples.
- No production source code.

## Option B: Open-Core Demo

Best for strong technical signal.

- Fresh repository.
- Simplified FastAPI service.
- Local PostGIS.
- Synthetic project/dataset/share workflows.
- No billing provider integration beyond stubs.

## Option C: Public Product Source

Most transparent, but requires the highest audit burden.

- Full secret scan.
- History rewrite or fresh export.
- Dependency/license review.
- Removal of sensitive business logic.
- Production environment split from public docs.

## Recommendation

Start with Option A and build toward Option B. Do not publish the existing production repo directly.

