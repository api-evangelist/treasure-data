# Treasure Data

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

Enterprise customer data platform (now Treasure AI) with a REST API for managing jobs, databases, tables, bulk import, authentication, and running Presto or Hive queries on big data.

## Overview

Treasure Data (rebranded as Treasure AI in April 2026) provides a cloud-based Customer Data Platform (CDP) with a comprehensive set of REST APIs for data ingestion, job management, user administration, and workflow orchestration. The platform supports Presto and Hive query engines for big data analytics at scale.

## APIs

- **TD API** — Core REST API for databases, tables, jobs, bulk import, and authentication (`https://api.treasuredata.com/v3/`)
- **Bulk Loads API** — Manage bulk load sessions for external data ingestion
- **User API** — User and access control management
- **System API** — Infrastructure health and server status
- **Postback API** — JSON event ingestion for systems without SDK support
- **Treasure Workflow API** — Digdag-based workflow automation and orchestration

## Authentication

All API requests require a TD1 API key passed in the `Authorization` header:

```
Authorization: TD1 YOUR_API_KEY_HERE
```

## SDKs

- JavaScript: https://github.com/treasure-data/td-js-sdk
- Android: https://github.com/treasure-data/td-android-sdk
- iOS: https://github.com/treasure-data/td-ios-sdk
- React Native: https://github.com/treasure-data/td-react-native-sdk
- Digdag (workflow engine): https://github.com/treasure-data/digdag

## Resources

- **Website:** https://www.treasure.ai/
- **Documentation:** https://docs.treasure.ai/
- **API Developer Portal:** https://api-docs.treasuredata.com/
- **GitHub Org:** https://github.com/treasure-data
- **LinkedIn:** https://www.linkedin.com/company/treasure-data-inc-
- **X:** https://twitter.com/TreasureData
- **Blog:** https://www.treasure.ai/blog
- **Pricing:** https://www.treasure.ai/product/pricing/
- **Status:** https://status.treasure.ai/

## APIs.json

This repository follows the [APIs.json 0.19 specification](https://apisjson.org/). See `apis.yml` for the full index.
