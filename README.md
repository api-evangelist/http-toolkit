# HTTP Toolkit

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

HTTP Toolkit is a beautiful, cross-platform, and open-source tool for debugging, testing, and building with HTTP(S) on Windows, Linux, and Mac. It provides one-click interception of HTTP/HTTPS traffic from browsers, mobile devices, Docker containers, and common language runtimes, enabling developers to inspect, mock, and rewrite live traffic in their development and testing workflows.

## Links

- **Website:** https://httptoolkit.com
- **Documentation:** https://httptoolkit.com/docs/
- **Blog:** https://httptoolkit.com/blog/
- **Pricing:** https://httptoolkit.com/pricing/
- **GitHub Org:** https://github.com/httptoolkit
- **Server Repository:** https://github.com/httptoolkit/httptoolkit-server
- **LinkedIn:** https://www.linkedin.com/company/http-toolkit
- **X (Twitter):** https://twitter.com/httptoolkit
- **Bluesky:** https://bsky.app/profile/httptoolkit.com
- **Mastodon:** https://mastodon.social/@httptoolkit

## APIs

### HTTP Toolkit Server API

The HTTP Toolkit server exposes a local REST API and a GraphQL management API used by the web UI to manage proxy operations, interceptors, certificates, and application launches. The server runs entirely on localhost and uses token-based authentication for security.

- **REST API port:** 45456
- **GraphQL management port:** 45457
- **Authentication:** `HTK_SERVER_TOKEN` environment variable
- **Source:** [src/api/rest-api.ts](https://github.com/httptoolkit/httptoolkit-server/blob/main/src/api/rest-api.ts)

## Plans

| Plan | Price | Key Features |
|------|-------|-------------|
| Hobbyist | Free | Basic interception, manual rewriting, built-in HTTP client |
| Professional | ~$14/month | Automated mocking, API validation (2600+ APIs), import/export |
| Team | Contact for pricing | All Pro features, centralized billing, team workspaces |

Annual billing for Professional saves approximately 25%.

## Contents

- `apis.yml` — APIs.json 0.19 index for HTTP Toolkit
- `plans/http-toolkit-plans-pricing.yml` — API Commons Plans 0.1 pricing details
- `rate-limits/http-toolkit-rate-limits.yml` — API Commons Rate Limits 0.1
- `finops/http-toolkit-finops.yml` — FinOps Framework FOCUS 1.0 cost analysis
