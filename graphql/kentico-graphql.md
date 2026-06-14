# Kentico Xperience GraphQL API

Xperience by Kentico provides a per-channel headless GraphQL API whose schema is **auto-generated** at runtime from the content types configured in each headless channel. There is no single static schema — every headless channel exposes its own endpoint, and the types, queries, filters, and sorters are derived from the content type definitions registered in that channel. Schema exploration is available via the built-in Banana Cake Pop/Nitro IDE at `/graphql/ui`.

**Endpoint:** `https://<domain>/graphql/<headless-channel-guid>`

**Documentation:** https://docs.kentico.com/documentation/developers-and-admins/development/content-retrieval/retrieve-headless-content

**Authentication:** Bearer token — `Authorization: Bearer <ApiKey>`

**References:**
- Documentation: https://docs.kentico.com/documentation/developers-and-admins/development/content-retrieval/retrieve-headless-content
- Headless Channel Management: https://docs.kentico.com/documentation/developers-and-admins/configuration/headless-channel-management
- API Reference: https://api-reference.kentico.com/
- GitHub Org: https://github.com/Kentico
