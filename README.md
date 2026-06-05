# Formspree (formspree)

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
