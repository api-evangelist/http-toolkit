# HTTP Toolkit

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
