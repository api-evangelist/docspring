# DocSpring

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
