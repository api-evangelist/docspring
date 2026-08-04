# DocSpring

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

DocSpring is a PDF generation platform with a REST API for filling PDF templates with dynamic data, generating documents programmatically, and managing template libraries. It supports synchronous and asynchronous PDF generation, batch submissions, combined PDF merging, data request workflows, e-signatures, and HTML-to-PDF conversion.

## Links

- **Website:** https://docspring.com/
- **Documentation:** https://docspring.com/docs/
- **API Reference:** https://docspring.com/docs/api/
- **OpenAPI Spec:** https://docspring.com/api-docs/v1/openapi.json
- **Pricing:** https://docspring.com/pricing
- **Status Page:** https://status.docspring.com/
- **Blog:** https://docspring.com/blog/
- **GitHub Org:** https://github.com/DocSpring
- **LinkedIn:** https://www.linkedin.com/company/docspring
- **X (Twitter):** https://x.com/DocSpring

## API

Base URL: `https://sync.api.docspring.com/api/v1`

Authentication: HTTP Basic Auth using API Token ID (username) and API Token Secret (password).

Key endpoints:
- `POST /templates/{template_id}/submissions` — Generate a PDF from a template
- `POST /submissions/batches` — Batch generate up to 50 PDFs
- `GET /submissions/{submission_id}` — Check submission status
- `POST /combined_submissions` — Merge multiple PDFs
- `GET /templates` — List templates
- `PUT /data_requests/{data_request_id}` — Update data request (e-signature workflows)

## SDKs

- Ruby: https://github.com/DocSpring/docspring-ruby
- JavaScript: https://github.com/DocSpring/docspring-javascript
- PHP: https://github.com/DocSpring/docspring-php
- Go: https://github.com/DocSpring/docspring-go
- Java: https://github.com/DocSpring/docspring-java
- C#: https://github.com/DocSpring/docspring-csharp
- OpenAPI Generator: https://github.com/DocSpring/docspring-openapi-generator

## Pricing

| Plan | Price | Included PDFs | Overage |
|------|-------|--------------|---------|
| Starter | $49/month | 50 | $0.25/PDF |
| Professional | $99/month | 1,000 | $0.10/PDF |
| Business | $249/month | 5,000 | $0.05/PDF |
| Enterprise | Custom | Custom | Custom |

14-day free trial available. Test PDFs are free and unlimited on all plans.

## APIs.json

This repository contains an [APIs.json](apis.yml) index file cataloging the DocSpring API.
