<h1 align="center">Hi, I'm Vinayak Gote</h1>
<h3 align="center">Java Backend Engineer · Open Source Contributor (Zalando · Adyen · Uber · Picnic · Debezium) · NVIDIA AI Aerial / 6G Developer Program Member</h3>

<p align="center">
  <a href="https://linkedin.com/in/vinayakgote">LinkedIn</a> &nbsp;·&nbsp;
  <a href="https://github.com/Vinu2111">GitHub</a> &nbsp;·&nbsp;
  <a href="https://vinayak6g.hashnode.dev">Blog</a> &nbsp;·&nbsp;
  <a href="mailto:vinayakgote44@gmail.com">Email</a> &nbsp;·&nbsp;
  <a href="https://portfolio-gules-ten-40.vercel.app">Portfolio</a>
</p>

<br/>

Backend engineer with hands-on production experience at **Wipro**, building enterprise REST APIs for VodafoneIdea telecom systems.

Member of the **NVIDIA AI Aerial / 6G Developer Program** — building research tooling on top of the NVIDIA Sionna SDK.

Actively contributing to open source Java libraries used in production by companies worldwide — **3 merged PRs** across Uber, Zalando, and Adyen, with **8 open PRs** in active review across 5 organizations.

---

## 🤝 Open Source Contributions

### ✅ Merged — 3 PRs

| # | Organization | Repository | Contribution | Status |
|---|---|---|---|---|
| 1 | **Uber** | [uber/NullAway #1546](https://github.com/uber/NullAway/pull/1546) | Report error when `@Initializer` is incorrectly used on a constructor — merged by core maintainer Manu Sridharan | ✅ Merged |
| 2 | **Zalando** | [zalando/logbook #2301](https://github.com/zalando/logbook/pull/2301) | Implemented `StatusCodeBasedSink` and `LevelBasedHttpLogWriter` — HTTP status-code-aware log levels (2xx/3xx → TRACE, 4xx → WARN, 5xx → ERROR) | ✅ Merged |
| 3 | **Adyen** | [adyen/adyen-java-api-library #1952](https://github.com/Adyen/adyen-java-api-library/pull/1952) | Fixed unescaped regex dots in `Service.createBaseURL` — replaced `replaceFirst()` with `String.replace()` for literal URL matching. Shipped in **v42.0.0** | ✅ Merged |

### ⏳ Open PRs — 8 in active review

| # | Organization | Repository | Contribution | Status |
|---|---|---|---|---|
| 4 | **Debezium / Red Hat** | [debezium/debezium #7462](https://github.com/debezium/debezium/pull/7462) | Fix PostgreSQL connector slow startup with many custom types — `TypeRegistry.java` overhaul with ORDER BY, iterative resolution loop, and batch fallback query. Overall LGTM from core maintainer vjuranek | 🔄 Under Review |
| 5 | **SigNoz** | [SigNoz/examples #63](https://github.com/SigNoz/examples/pull/63) | Spring Boot microservices distributed tracing demo — OpenTelemetry Java Agent auto-instrumentation, distributed traces verified in SigNoz dashboard | 🔄 Under Review |
| 6 | **Picnic** | [PicnicSupermarket/error-prone-support #2264](https://github.com/PicnicSupermarket/error-prone-support/pull/2264) | New Refaster rule — detects `Optional.of(x).orElse(y)` dead-code anti-pattern where fallback is unreachable, rewrites to explicit `requireNonNull(x)` | 🔄 Under Review |
| 7 | **Zalando** | [zalando/logbook (issue #2237)](https://github.com/zalando/logbook/issues/2237) | Added `SpringSecurityAttributeExtractor` — logs authenticated username in every HTTP request | 🔄 Under Review |
| 8 | **Zalando** | [zalando/logbook (issue #2318)](https://github.com/zalando/logbook/issues/2318) | Fixed JSON formatter embedding non-JSON body (ciphertext/binary) as raw invalid JSON | 🔄 Under Review |
| 9 | **Zalando** | [zalando/logbook (issue #2174)](https://github.com/zalando/logbook/issues/2174) | Fixed `LogbookClientHttpRequestInterceptor` crashing on startup without spring-web on classpath | 🔄 Under Review |
| 10 | **Zalando** | [zalando/logbook (issue #2115)](https://github.com/zalando/logbook/issues/2115) | Fixed `CachingHttpResponse` dropping attributes when `withoutBody()` is called | 🔄 Under Review |
| 11 | **Zalando** | [zalando/problem #557](https://github.com/zalando/problem/pull/557) | Added `toBuilder()` method to the `Problem` interface for fluent problem mutation | 🔄 Under Review |

**Companies touched through OSS:** 🇳🇱 Zalando &nbsp;·&nbsp; 🇳🇱 Adyen &nbsp;·&nbsp; 🇳🇱 Picnic &nbsp;·&nbsp; 🇺🇸 Uber &nbsp;·&nbsp; 🌍 Debezium (Red Hat) &nbsp;·&nbsp; 🌍 SigNoz

---

## 🔧 Stack

| Layer | Technologies |
|---|---|
| **Languages** | Java · Python · SQL · Shell/Bash |
| **Frameworks** | Spring Boot 3 · Spring Security · Spring Data JPA · Hibernate · FastAPI · Angular 17 |
| **Databases** | MySQL · PostgreSQL |
| **Cloud** | AWS (Certified Cloud Practitioner) · EC2 · S3 · RDS |
| **Tools** | Docker · Maven · Git · Postman · IntelliJ IDEA |
| **6G / AI** | NVIDIA Sionna SDK · NVIDIA AI Aerial / 6G Developer Program |

---

## 🚀 Featured Project

### [Sionna Visualizer — 6G Research Dashboard](https://github.com/Vinu2111/sionna-visualizer)

> Built the missing visual layer for NVIDIA Sionna — a full-stack dashboard that makes 6G simulation results visual, comparable, and shareable.
> NVIDIA Sionna has **200,000+ downloads** with zero public dashboard previously existing. This solves that.
>
> Core maintainer **Merlin Nimier-David** mentioned `@Vinu2111` by name in a GitHub discussion — direct public recognition from an NVIDIA engineer.
