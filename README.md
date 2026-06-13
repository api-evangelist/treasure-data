# Treasure Data

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
