# PPW

Career Evidence Hub for AI-native systems, products, workflows, and creative technology.

## v1 scope

- Home
- Work index
- ARAM case study
- Public Career Evidence project schema
- Public-safe project registry

## Information architecture

```text
Home
├─ Method
├─ Featured work
└─ Capabilities

Work
├─ ARAM
├─ INHA WORLD
├─ CHAEVI
├─ MADI + Observer
└─ TML / sui

data/
├─ career-evidence.schema.json
└─ projects.json
```

## Public evidence rule

This repository contains only public-safe portfolio material. Private operating records, credentials,
internal career scoring, application strategy, and unreviewed source material do not belong here.

## Local preview

No build step is required for the current static v1.

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Status

Work in progress. The first case study is ARAM; additional evidence-backed case studies will be added incrementally.
