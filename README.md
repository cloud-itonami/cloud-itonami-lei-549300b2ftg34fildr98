# cloud-itonami-lei-549300b2ftg34fildr98

> **Independent third-party archive/analysis. Not affiliated with, endorsed by, or sponsored by Uber Technologies, Inc.**

This repository archives the publicly published U.S. Terms of Service of **Uber
Technologies, Inc.**, with source-url and retrieval-date provenance, per
[ADR-2607110300](https://github.com/com-junkawasaki/root/blob/main/90-docs/adr/2607110300-cloud-itonami-lei-corporate-tos-catalog.edn)
(`cloud-itonami-lei-corporate-tos-catalog`, `com-junkawasaki/root`). It is a read-only
reference/archive repository — it does not act, propose, or execute anything on the
company's behalf, and is not a governed Advisor/Governor actor.

## Company identity

- **Legal name**: Uber Technologies, Inc.
- **LEI (ISO 17442)**: [549300B2FTG34FILDR98](https://search.gleif.org/#/record/549300B2FTG34FILDR98) (GLEIF-verified, status ACTIVE, registration ISSUED)
- **Jurisdiction**: US
- **Website**: https://www.uber.com
- **Ticker**: UBER (NYSE)

## Contents

- `80-data/public/tos.journal.edn` — EDN quad-log of archived Terms of Service documents.
- `NOTICE` — copyright/attribution statement for the archived third-party text.
- `blueprint.edn` — machine-readable company identity record.

## Related cloud-itonami blueprint (passenger-road-transport vertical)

Uber operates one of the world's largest ride-hailing/taxi-dispatch networks —
`cloud-itonami-isic-4921`'s own README names "taxi/rideshare dispatch" explicitly
in its scope. This vertical's *generic, forkable* Open Business Blueprint
counterpart in the `cloud-itonami` fleet is
[`cloud-itonami-isic-4921`](https://github.com/cloud-itonami/cloud-itonami-isic-4921)
(ISIC 4921/4922 sibling pair — urban/suburban vs. intercity/chartered coach
scheduling-and-dispatch coordination, Advisor⊣Governor actor pattern). This
LEI-catalog entry is a **read-only ToS reference only** — it is not a fork of, and
has no code dependency on, isic-4921.

Noted for context, not asserted as legal analysis: Uber's own Terms of Service
(Section 8) frames itself primarily as a technology-platform intermediary between
riders and independent transportation providers, with dispute resolution
channeled through binding arbitration (Section 2). This is a materially different
liability posture from `transitops.governor`'s own architecture, which requires
independent, store-derived verification of vehicle registration and operator
licensing *before* any dispatch-scheduling proposal may commit — see
`cloud-itonami-isic-4921/docs/real-world-tos-governor-analysis.md` for the fuller,
evidence-cited comparison across this catalog.

## Design rationale

See ADR-2607110300 in `com-junkawasaki/root` (`90-docs/adr/`).
