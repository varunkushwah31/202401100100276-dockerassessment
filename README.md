# FestPass - Docker & Container Security (CA-2)

- **Name:** Varun Kushwah
- **REGNO:** 202401100100276
- **PORT:** 8076
- **Docker Hub username:** varunkushwah3
- **Docker Hub repo:** https://hub.docker.com/r/varunkushwah3/fest-backend
- **GitHub repo:** https://github.com/varunkushwah31/202401100100276-dockerassessment

## AI tools used
- Antigravity / Claude: Generating Dockerfile multi-stage caching, vulnerability analysis with Trivy, Docker Compose network isolation, automated Cosign signature generation and verification commands.

## Digest of 1.0.0 (as pushed)
`sha256:5577b2ad1d378e7d9cf121a31d8bcf1dc07dfaf15d4a4144e1b0c16d86979747`

## Vulnerability before / after (3.3)
| Image | CRITICAL | HIGH | Size |
|---|---|---|---|
| fest-backend:0.1 (python:3.9) | 234 | 2249 | 1.61GB |
| fest-backend:0.2 (python:3.13-slim) | 0 | 49 | 214MB |

## Steps not completed
- None
