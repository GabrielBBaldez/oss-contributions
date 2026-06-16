# Open Source Contributions

![Open source](https://img.shields.io/badge/open_source-contributions-2ea44f?style=flat-square)
![Java](https://img.shields.io/badge/Java-Spring_Kafka_AWS-orange?style=flat-square)
![Ecosystems](https://img.shields.io/badge/ecosystems-Apache_·_CNCF_·_Crowdin-blue?style=flat-square)

A running log of my open-source pull requests — across data infrastructure, developer tooling, observability, and self-hosted platforms. Primarily Java backend (Spring / Kafka / AWS), with some Kotlin/Android and Angular.

Every entry links to the actual pull request, and the list grows as I open new ones.

_Last updated: 2026-06-16_

## Summary

| Status | Count |
|--------|-------|
| ✅ Merged | 19 |
| 🟡 Open (in review) | 11 |

Projects: **Apache SeaTunnel**, **Apache Iceberg**, **Crowdin**, **Meilisearch**, **OpenTelemetry (CNCF)**, **WSO2 Identity Server**, **OWASP Dependency-Track**, **Vault-Web**, **Hermes**.

---

## <img src="https://github.com/apache.png?size=48" width="24" align="top"/> Apache SeaTunnel — `apache/seatunnel`
Distributed data integration platform (Apache TLP).

| PR | Description | Status |
|----|-------------|--------|
| [#11053](https://github.com/apache/seatunnel/pull/11053) | MongoDB-CDC: `latest` startup mode without an initial snapshot | ✅ Merged |
| [#11030](https://github.com/apache/seatunnel/pull/11030) | Zendesk source connector fixes | 🟡 Open — approved by the PMC Chair |
| [#11028](https://github.com/apache/seatunnel/pull/11028) | Shopify source connector fixes | 🟡 Open — approved |
| [#11057](https://github.com/apache/seatunnel/pull/11057) | MySQL-CDC: snapshot-only startup mode | 🟡 Open |

## <img src="https://github.com/apache.png?size=48" width="24" align="top"/> Apache Iceberg — `apache/iceberg`
Leading open table format for data lakehouses (Apache TLP).

| PR | Description | Status |
|----|-------------|--------|
| [#16794](https://github.com/apache/iceberg/pull/16794) | AWS: use assumed-role credentials for REST SigV4 signing (fixes credential divergence with S3 Tables / Glue REST catalogs) | 🟡 Open |

## <img src="https://github.com/crowdin.png?size=48" width="24" align="top"/> Crowdin
Localization platform — Java SDK and CLI.

**`crowdin/crowdin-api-client-java`** — 7 PRs, all merged in **release [1.33.0](https://github.com/crowdin/crowdin-api-client-java/releases/tag/1.33.0)** (the entire release changelog is credited to me):

| PR | Description | Status |
|----|-------------|--------|
| [#378](https://github.com/crowdin/crowdin-api-client-java/pull/378) | `updateOption` for source strings | ✅ Merged |
| [#380](https://github.com/crowdin/crowdin-api-client-java/pull/380) | Export Bundle support | ✅ Merged |
| [#381](https://github.com/crowdin/crowdin-api-client-java/pull/381) | Glossary export filters | ✅ Merged |
| [#382](https://github.com/crowdin/crowdin-api-client-java/pull/382) | Pre-Translation scope options | ✅ Merged |
| [#379](https://github.com/crowdin/crowdin-api-client-java/pull/379) | `styleGuideIds` for AI Translation | ✅ Merged |
| [#383](https://github.com/crowdin/crowdin-api-client-java/pull/383) | Generic task vendor requests | ✅ Merged |
| [#384](https://github.com/crowdin/crowdin-api-client-java/pull/384) | AI prompt `projectDescription` (incl. breaking change) | ✅ Merged |
| [#385](https://github.com/crowdin/crowdin-api-client-java/pull/385) | Jackson 3 migration | 🟡 Open — parked for the 2.0 major |

**`crowdin/crowdin-cli`**:

| PR | Description | Status |
|----|-------------|--------|
| [#1032](https://github.com/crowdin/crowdin-cli/pull/1032) | Respect ignore patterns with language placeholders on `upload translations` | ✅ Merged |
| [#1033](https://github.com/crowdin/crowdin-cli/pull/1033) | Clear message instead of a stack trace on unsupported Java versions | 🟡 Open |

## <img src="https://github.com/open-telemetry.png?size=48" width="24" align="top"/> OpenTelemetry — `open-telemetry/opentelemetry-android` (CNCF)
Android observability instrumentation.

| PR | Description | Status |
|----|-------------|--------|
| [#1811](https://github.com/open-telemetry/opentelemetry-android/pull/1811) | Power Save Mode instrumentation (new opt-in module, Kotlin) | 🟡 Open — approved |

## <img src="https://github.com/Vault-Web.png?size=48" width="24" align="top"/> Vault-Web — self-hosted personal cloud (Java microservices + Angular)

**`Vault-Web/cloud-page`** (file manager backend):

| PR | Description | Status |
|----|-------------|--------|
| [#75](https://github.com/Vault-Web/cloud-page/pull/75) | Include folder sizes in directory listing | ✅ Merged |
| [#76](https://github.com/Vault-Web/cloud-page/pull/76) | Javadocs for service classes | ✅ Merged |
| [#78](https://github.com/Vault-Web/cloud-page/pull/78) | Fix path traversal on file upload (security) | ✅ Merged |
| [#79](https://github.com/Vault-Web/cloud-page/pull/79) | Per-user trash (soft delete) with scheduled cleanup | ✅ Merged |
| [#81](https://github.com/Vault-Web/cloud-page/pull/81) | Configurable rate limiting (per-user / per-IP) for file operations | ✅ Merged |
| [#82](https://github.com/Vault-Web/cloud-page/pull/82) | Sort folder content by size and last-modified (not only name) | ✅ Merged |

**`Vault-Web/vault-web`** (Angular frontend):

| PR | Description | Status |
|----|-------------|--------|
| [#231](https://github.com/Vault-Web/vault-web/pull/231) | Show folder sizes in the cloud view (maintainer-invited) | ✅ Merged |
| [#238](https://github.com/Vault-Web/vault-web/pull/238) | Trash UI for the cloud view, consuming the soft-delete endpoints (maintainer-invited) | ✅ Merged |
| [#239](https://github.com/Vault-Web/vault-web/pull/239) | Redirect to login on expired session (auth / session fix) | ✅ Merged |
| [#241](https://github.com/Vault-Web/vault-web/pull/241) | Sorting controls for the cloud page (Closes #213) | ✅ Merged |

## <img src="https://github.com/outsourc-e.png?size=48" width="24" align="top"/> Hermes — `outsourc-e/hermes-workspace`
Web workspace for the Hermes agent.

| PR | Description | Status |
|----|-------------|--------|
| [#617](https://github.com/outsourc-e/hermes-workspace/pull/617) | Read `HERMES_API_TOKEN` from an env file fallback | 🟡 Open |

## <img src="https://github.com/wso2.png?size=48" width="24" align="top"/> WSO2 Identity Server — `wso2-extensions/identity-inbound-auth-oauth`
Open-source IAM / identity server (OAuth2 & OIDC components).

| PR | Description | Status |
|----|-------------|--------|
| [#3256](https://github.com/wso2-extensions/identity-inbound-auth-oauth/pull/3256) | Reject `/oauth2/userinfo` requests carrying multiple `Authorization` headers (RFC 9110) | 🟡 Open |

## <img src="https://github.com/meilisearch.png?size=48" width="24" align="top"/> Meilisearch — `meilisearch/meilisearch-java`
Official Java SDK for the Meilisearch search engine.

| PR | Description | Status |
|----|-------------|--------|
| [#971](https://github.com/meilisearch/meilisearch-java/pull/971) | Personalized search support (`personalize` parameter, Meilisearch 1.47.0) | 🟡 Open |

## <img src="https://github.com/DependencyTrack.png?size=48" width="24" align="top"/> OWASP Dependency-Track — `DependencyTrack/dependency-track`
Component analysis / SCA platform (OWASP flagship project).

| PR | Description | Status |
|----|-------------|--------|
| [#6426](https://github.com/DependencyTrack/dependency-track/pull/6426) | Surface the server release version in the OpenAPI spec (`x-server-version` + title) | 🟡 Open |
