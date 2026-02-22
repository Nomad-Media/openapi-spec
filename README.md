# REST API OpenAPI Spec

**Version:** 2026-03

Raw backend REST API specs for the Nomad Media services.

> This is distinct from [`sdk-openapi-spec`](https://github.com/Nomad-Media/sdk-openapi-spec), which is the client SDK spec used to support the Javascript, Java and C# SDKs.

---

## Files

| File | Description |
|------|-------------|
| `swagger-admin.json` | Admin API spec — system administration, asset management, live streaming, user management |
| `swagger-portal.json` | Portal API spec — public-facing endpoints for media delivery, search, and viewer experience |

---

## Usage

Import into [Postman](https://www.postman.com/) or another API client to explore and test the backend endpoints directly.

**In Postman:**
1. Click **Import**
2. Select `swagger-admin.json` or `swagger-portal.json`
3. Set your `Authorization: Bearer <token>` header and `serviceApiUrl` variable

---

## API Documentation

Full endpoint documentation is available at [docs.nomad.media/api-reference](https://docs.nomad.media/api-reference).

---

## Related Repositories

- [`sdk-openapi-spec`](https://github.com/Nomad-Media/sdk-openapi-spec) — SDK-level spec
- [`sdk-javascript`](https://github.com/Nomad-Media/sdk-javascript) — Official JavaScript SDK
- [`sdk-python`](https://github.com/Nomad-Media/sdk-python) — Official Python SDK
- [`sdk-java`](https://github.com/Nomad-Media/sdk-java) — Official Java SDK
