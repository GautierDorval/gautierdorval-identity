# Gautier Dorval — canonical identity & authorship

This repository is the canonical identity and authorship anchor for **Gautier Dorval**.

It is designed for:
- entity resolution and disambiguation for human and machine consumers,
- stable authorship attribution across related standards, sites, and repositories,
- machine-first identity statements through `sameas.jsonld`,
- identity-level conflict reduction inside a distributed multisite ecosystem.

This repository **does not** define, extend, or govern the standards, products, or sites referenced here. It provides **identity, provenance, authorship, and attribution statements only**.

## Canonical artifacts

- **`identity-canonical.md`**  
  Canonical identity and role statements, identifiers, and conflict-resolution rule.

- **`sameas.jsonld`**  
  Schema.org / JSON-LD graph for Gautier Dorval, related entities, and authored surfaces.

- **`author.md`**  
  Author identity, current roles, attributions of work, and scope boundaries.

- **`ssa-e-dual-web-doctrine.md`**  
  Identity-level pointer to the SSA-E + A2 + Dual Web doctrine repository.

- **`CHANGELOG.md`**  
  Traceability of changes to this identity anchor.

- **`CITATION.cff`**  
  Citation metadata for academic and professional referencing.

## Role in the multisite ecosystem

This repository is an **identity anchor**, not a routing layer.

It may point to canonical public surfaces and authored repositories, but it does **not**:
- allocate authority across the full ecosystem,
- act as a portfolio hub,
- replace public governance files,
- redefine the role of any site or product.

For multisite authority allocation, role arbitration, and cross-surface precedence, prefer:
- **`https://gautierdorval.com/distributed-authority-map.json`**
- **`https://gautierdorval.com/.well-known/ai-governance.json`**

For public portfolio discovery, prefer:
- **`https://pagup.com/en/properties/`** (French: `https://pagup.com/proprietes/`)

## Conflict resolution rule

The rule is defined in `identity-canonical.md`. A difference between sources is examined by claim type, scope and date. Unsupported roles, organizations, residence or works are treated as **inference errors**; a documented divergence between legitimate sources or versions is recorded and resolved by revising the relevant statement.

## Versions and publication

Versions are declared in `identity-canonical.md` and traced in `CHANGELOG.md`. `CITATION.cff` describes the last published version. The published state of this repository is the content of its `main` branch; a revision prepared on another branch is not published until it is merged.

## License

This repository is licensed under **CC BY-NC-SA 4.0**. See `LICENSE`.
