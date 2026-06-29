<h1 align="center">Vinayak Gote</h1>
<h3 align="center">Java Backend Engineer · OSS Contributor (Zalando · Adyen · Picnic · Debezium) · NVIDIA AI Aerial / 6G Developer Program</h3>

<p align="center">
  <a href="https://linkedin.com/in/vinayakgote">LinkedIn</a> &nbsp;·&nbsp;
  <a href="https://github.com/Vinu2111">GitHub</a> &nbsp;·&nbsp;
  <a href="https://vinayak6g.hashnode.dev">Blog</a> &nbsp;·&nbsp;
  <a href="https://dev.to/vinayakgote">Dev.to</a> &nbsp;·&nbsp;
  <a href="mailto:vinayakgote44@gmail.com">Email</a> &nbsp;·&nbsp;
  <a href="https://portfolio-gules-ten-40.vercel.app">Portfolio</a>
</p>

<br/>

Backend engineer at **Wipro**, building production REST APIs for VodafoneIdea telecom systems with Spring Boot 3. My strategy for breaking into product companies I respect: contribute real code to their OSS repos before applying. That's led to **2 merged PRs** across Zalando and Adyen, with **9 open PRs** in active review across 5 organizations including Picnic, Debezium, and SigNoz.

Member of the **NVIDIA AI Aerial / 6G Developer Program** after two merged bug fixes in the Sionna SDK, with a public mention from NVIDIA core maintainer Merlin Nimier-David.

I write daily on [Hashnode](https://vinayak6g.hashnode.dev) and [Dev.to](https://dev.to/vinayakgote) backend engineering, OSS learnings, and Java deep-dives.

---

## 🟢 Currently

- Landed a Refaster rule in **Picnic/error-prone-support** (#2275) rewrites `Optional.of(x).orElse(y)` to `requireNonNull(x)`, approach approved by Stephan202
- Debezium PostgreSQL connector fix (#7462) — "Overall LGTM" from core maintainer vjuranek
- Building [`picnic-store-intelligence`](https://github.com/Vinu2111/picnic-store-intelligence) — an architectural prototype exploring Picnic's Page Platform philosophy (server-driven layouts + per-customer section ranking)
- Self-studying German toward Goethe-Institut certification

---

## 🤝 Open Source Contributions

### ✅ Merged — 2 PRs

| # | Org | Repository | What I did |
|---|---|---|---|
| 1 | **Zalando** | [zalando/logbook #2301](https://github.com/zalando/logbook/pull/2301) | Implemented `StatusCodeBasedSink` + `LevelBasedHttpLogWriter` — HTTP status-code-aware log levels (2xx/3xx → TRACE, 4xx → WARN, 5xx → ERROR) |
| 2 | **Adyen** | [adyen/adyen-java-api-library #1952](https://github.com/Adyen/adyen-java-api-library/pull/1952) | Fixed unescaped regex dots in `Service.createBaseURL` — shipped in **SDK v42.0.0** |

### ⏳ Open — 9 PRs in active review

| # | Org | Repository | What I did |
|---|---|---|---|
| 3 | **Picnic** | [error-prone-support #2275](https://github.com/PicnicSupermarket/error-prone-support/pull/2275) | Refaster rule: rewrites `Optional.of(x).orElse(y)` dead-code anti-pattern → `requireNonNull(x)`. Approach approved by Stephan202 |
| 4 | **Debezium / Red Hat** | [debezium #7462](https://github.com/debezium/debezium/pull/7462) | PostgreSQL connector slow-startup fix — `TypeRegistry.java` with ORDER BY, iterative resolution loop, batch fallback. "Overall LGTM" from vjuranek |
| 5 | **SigNoz** | [examples #63](https://github.com/SigNoz/examples/pull/63) | Spring Boot microservices distributed tracing demo with OpenTelemetry Java Agent auto-instrumentation |
| 6 | **Zalando** | [logbook #2237](https://github.com/zalando/logbook/issues/2237) | `SpringSecurityAttributeExtractor` — logs authenticated username in every HTTP request |
| 7 | **Zalando** | [logbook #2318](https://github.com/zalando/logbook/issues/2318) | Fixed JSON formatter embedding non-JSON bodies (ciphertext/binary) as raw invalid JSON |
| 8 | **Zalando** | [logbook #2174](https://github.com/zalando/logbook/issues/2174) | Fixed `LogbookClientHttpRequestInterceptor` crashing on startup without spring-web on classpath |
| 9 | **Zalando** | [logbook #2115](https://github.com/zalando/logbook/issues/2115) | Fixed `CachingHttpResponse` dropping attributes when `withoutBody()` is called |
| 10 | **Zalando** | [problem #557](https://github.com/zalando/problem/pull/557) | Added `toBuilder()` to the `Problem` interface for fluent problem mutation |
| 11 | **NVlabs** | [sionna #1155](https://github.com/NVlabs/sionna/pull/1155) + [#1156](https://github.com/NVlabs/sionna/pull/1156) | Fixed 3GPP spec compliance bugs in NVIDIA Sionna SDK — led to NVIDIA AI Aerial Program membership |

**Orgs touched:** 🇳🇱 Zalando &nbsp;·&nbsp; 🇳🇱 Adyen &nbsp;·&nbsp; 🇳🇱 Picnic &nbsp;·&nbsp; 🌍 Debezium (Red Hat) &nbsp;·&nbsp; 🌍 SigNoz &nbsp;·&nbsp; 🇺🇸 NVIDIA

---

## 🚀 Projects

### [Sionna Visualizer — 6G Research Dashboard](https://github.com/Vinu2111/sionna-visualizer)
*Angular 17 · Spring Boot 3 · Python FastAPI · PostgreSQL · JWT*

The missing visual layer for NVIDIA Sionna (200,000+ downloads). A full-stack dashboard that makes 6G simulation results visual, comparable, and shareable with a Publication Pipeline, multi-simulator comparison, and Claude API integration for natural language simulation.

NVIDIA core maintainer **Merlin Nimier-David** mentioned `@Vinu2111` by name in a GitHub discussion. Accepted into the **NVIDIA AI Aerial / 6G Developer Program**.

→ [Live](https://sionna-visualizer.vercel.app) · [GitHub](https://github.com/Vinu2111/sionna-visualizer)

---

### [Picnic Store Intelligence](https://github.com/Vinu2111/picnic-store-intelligence)
*Java 21 · Spring Boot 3.2 · PostgreSQL (Supabase) · Vanilla JS · Railway + Vercel*

An architectural prototype exploring two problems I found in Picnic's Page Platform engineering blog series: **server-driven section rendering** and **per-customer section ranking**.

The backend owns the entire page layout via a rule engine. The frontend is a dumb renderer with a UI component registry. A weighted scoring algorithm silently reranks sections per customer based on purchase behaviour — `score = (frequency × 0.5) + (recency × 0.3) + (time-of-day × 0.2)`.

→ [Live](https://picnic-store-intelligence.vercel.app) · [API / Swagger](https://picnic-store-intelligence-production.up.railway.app/swagger-ui.html) · [GitHub](https://github.com/Vinu2111/picnic-store-intelligence)

---

## 🔧 Stack

| Layer | Technologies |
|---|---|
| **Languages** | Java · Python · SQL · JavaScript |
| **Frameworks** | Spring Boot 3 · Spring Security · Spring Data JPA · FastAPI · Angular 17 |
| **Databases** | MySQL · PostgreSQL |
| **Cloud & Tools** | AWS (CCP certified) · Docker · Maven · Git · Postman · IntelliJ IDEA |
| **6G / AI** | NVIDIA Sionna SDK · NVIDIA AI Aerial / 6G Developer Program |

---

## 📝 Writing

I post daily — backend engineering concepts, OSS contribution walkthroughs, and Java deep-dives.

→ [Hashnode](https://vinayak6g.hashnode.dev) &nbsp;·&nbsp; [Dev.to](https://dev.to/vinayakgote)
