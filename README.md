# Formspree (formspree)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Formspree is a form backend for static and Jamstack sites. Two API surfaces matter: (1) the public form-submission endpoint (formspree.io/f/{hashid}) that accepts POST submissions and returns JSON when the Accept header is set, and (2) the Forms API (formspree.io/api/0/...) for programmatic submission retrieval, export and form management. Plugins and the Formspree CLI extend the surface.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/formspree/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/formspree/refs/heads/main/apis.yml)

## Tags

- Forms
- Backend
- Static Sites
- Email
- Webhooks
- JAMstack
- CLI

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Formspree Form Submission Endpoint

Public POST endpoint per form. Accepts standard HTML form posts and cross-origin AJAX (Accept: application/json) and returns JSON. No auth for the submission itself; per-form spam controls.

- **Human URL:** [https://help.formspree.io/hc/en-us/articles/360015233153-Form-Submissions-API](https://help.formspree.io/hc/en-us/articles/360015233153-Form-Submissions-API)
- **Base URL:** `https://formspree.io/f/<hashid>`

#### Tags

- REST
- Submissions
- AJAX

#### Properties

- [Documentation](https://help.formspree.io/hc/en-us/articles/360015233153-Form-Submissions-API)
- [Postman Collection](collections/formspree.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/formspree.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Formspree Forms API

REST API for retrieving submissions and managing forms. Endpoints under /api/0/forms/<hashid>/. Bearer auth using a public read-only API key or a Master API key (paid plans only). Supports since/limit/offset.

- **Human URL:** [https://help.formspree.io/sections/the-forms-api/](https://help.formspree.io/sections/the-forms-api/)
- **Base URL:** `https://formspree.io/api/0`

#### Tags

- REST
- Submissions
- Management
- Pagination

#### Properties

- [Documentation](https://help.formspree.io/sections/the-forms-api/)
- [A P I Keys](https://help.formspree.io/articles/the-forms-api/api-keys/)
- [Postman Collection](collections/formspree.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/formspree.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/formspree)
- [Website](https://formspree.io/)
- [Documentation](https://help.formspree.io/)
- [Pricing](https://formspree.io/plans)
- [Git Hub](https://github.com/formspree)
- [Status Page](https://www.formspreestatus.com/)
- [Plans](plans/formspree-plans-pricing.yml)
- [Rate Limits](rate-limits/formspree-rate-limits.yml)
- [Fin Ops](finops/formspree-finops.yml)
- [L L Ms Txt](https://formspree.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
