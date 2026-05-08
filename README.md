# Formspree (formspree)

Formspree is a form backend service for static and Jamstack sites — collects submissions, validates, sends emails, and integrates via webhooks and Plugins. Two API surfaces: the public form-submission endpoint and the Forms API for programmatic submission retrieval and management.

**APIs.json:** [apis.yml](apis.yml)

## APIs
- **Form submission endpoint** — `https://formspree.io/f/<hashid>` — POST submissions, JSON or HTML response (Accept: application/json for AJAX).
- **Forms API** — `https://formspree.io/api/0` — `/forms/<hashid>/submissions` and account/form management. Bearer auth with public read-only or Master API keys.

## OpenAPI
Formspree does not publish a downloadable OpenAPI/Swagger document at a stable public URL as of 2026-05-08; pipeline did not retrieve a spec into `openapi/`.

## Tags
Forms, Backend, Static Sites, Email, Webhooks, JAMstack, CLI

## Common Properties
- [Website](https://formspree.io/) · [Docs](https://help.formspree.io/) · [Pricing](https://formspree.io/plans)
- [GitHub](https://github.com/formspree)
- [Plans](plans/formspree-plans-pricing.yml) — partially reconciled (Free tier exact; paid tier prices vary across sources)
- [Rate Limits](rate-limits/formspree-rate-limits.yml) — reconciled (submission caps + threshold notifications)
- [FinOps](finops/formspree-finops.yml) — reconciled, FOCUS-aligned

## Plans (reconciled)
- **Free** — 50 submissions/mo, 30-day archive.
- **Personal / Professional / Business** — paid tiers; live prices on formspree.io/plans.

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Maintainers
- **Kin Lane** — kin@apievangelist.com
