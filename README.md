# Scalable Architecture

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

A subject-matter collection covering APIs, patterns, tools, and frameworks for building scalable system architecture. This topic encompasses microservices design, service mesh, event-driven architecture, CQRS, saga patterns, container orchestration, caching, message queuing, and observability patterns for distributed systems.

**URL:** [https://raw.githubusercontent.com/api-evangelist/scalable-architecture/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/scalable-architecture/refs/heads/main/apis.yml)

## Tags

Cloud Architecture, Cloud Native, Distributed Systems, High Availability, Infrastructure, Microservices, Performance, Resilience, Scalability, Service Mesh

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-02

## APIs

### Istio Service Mesh API
Leading open-source service mesh providing traffic management, mTLS security, and observability for Kubernetes microservices. CNCF graduated project.

**Human URL:** [https://istio.io/](https://istio.io/)

#### Tags

CNCF, Kubernetes, Microservices, Observability, Security, Service Mesh, Traffic Management

#### Properties

- [Documentation](https://istio.io/latest/docs/)
- [GitHub](https://github.com/istio/istio)
- [Getting Started](https://istio.io/latest/docs/setup/getting-started/)
- [Changelog](https://istio.io/latest/news/releases/)

### Linkerd API
Lightweight, security-first service mesh for Kubernetes with automatic mTLS, golden metrics observability, and minimal operational complexity. CNCF graduated project.

**Human URL:** [https://linkerd.io/](https://linkerd.io/)

#### Tags

CNCF, Kubernetes, Microservices, mTLS, Observability, Security, Service Mesh

#### Properties

- [Documentation](https://linkerd.io/2.x/overview/)
- [GitHub](https://github.com/linkerd/linkerd2)
- [Getting Started](https://linkerd.io/2.x/getting-started/)

### Envoy Proxy Admin API
High-performance edge and service proxy powering Istio, Linkerd, and most service meshes; Admin API for configuration, statistics, and cluster management. CNCF graduated project.

**Human URL:** [https://www.envoyproxy.io/](https://www.envoyproxy.io/)

#### Tags

CNCF, Load Balancing, Open Source, Proxy, Service Mesh, Traffic Management

#### Properties

- [Documentation](https://www.envoyproxy.io/docs/envoy/latest/operations/admin)
- [GitHub](https://github.com/envoyproxy/envoy)

### Apache Kafka REST Proxy API
RESTful interface to Apache Kafka for producing and consuming messages in event-driven scalable architectures. Core to distributed data pipelines.

**Human URL:** [https://kafka.apache.org/](https://kafka.apache.org/)

#### Tags

Apache Kafka, Event Streaming, Event-Driven, Message Broker, Microservices, Pub-Sub

#### Properties

- [Documentation](https://docs.confluent.io/platform/current/kafka-rest/api.html)
- [GitHub](https://github.com/confluentinc/kafka-rest)
- [OpenAPI](https://raw.githubusercontent.com/confluentinc/kafka-rest/master/api/v3/openapi.yaml)

### Redis REST API (Redis Stack)
In-memory data structure store used as a cache, message broker, and streaming engine. REST API access via Redis Stack modules for JSON and search.

**Human URL:** [https://redis.io/](https://redis.io/)

#### Tags

Caching, Data Store, In-Memory, Message Broker, Open Source, Pub-Sub, Redis

#### Properties

- [Documentation](https://redis.io/docs/)
- [GitHub](https://github.com/redis/redis)
- [Pricing](https://redis.io/pricing/)

### RabbitMQ Management HTTP API
REST API for managing RabbitMQ exchanges, queues, bindings, users, and virtual hosts—critical for scalable event-driven microservice architectures.

**Human URL:** [https://www.rabbitmq.com/](https://www.rabbitmq.com/)

#### Tags

AMQP, Event-Driven, Message Broker, Microservices, Open Source, RabbitMQ

#### Properties

- [Documentation](https://www.rabbitmq.com/management.html)
- [GitHub](https://github.com/rabbitmq/rabbitmq-server)
- [OpenAPI](https://raw.githubusercontent.com/rabbitmq/rabbitmq-server/main/deps/rabbitmq_management/priv/www/api/index.json)

### Kubernetes API
Foundation of cloud-native container orchestration; REST API for managing the full lifecycle of containerized workloads including Deployments, Services, HPA, and cluster state. CNCF graduated project.

**Human URL:** [https://kubernetes.io/](https://kubernetes.io/)

#### Tags

CNCF, Cloud Native, Containers, Kubernetes, Orchestration, Open Source

#### Properties

- [Documentation](https://kubernetes.io/docs/reference/)
- [GitHub](https://github.com/kubernetes/kubernetes)
- [OpenAPI](https://raw.githubusercontent.com/kubernetes/kubernetes/master/api/openapi-spec/swagger.json)
- [Getting Started](https://kubernetes.io/docs/tutorials/)

### Argo Workflows API
Kubernetes-native workflow engine for orchestrating parallel jobs used in scalable data pipelines, CI/CD, and ML workflows. CNCF graduated project.

**Human URL:** [https://argoproj.github.io/argo-workflows/](https://argoproj.github.io/argo-workflows/)

#### Tags

CNCF, CI/CD, Kubernetes, Orchestration, Pipelines, Workflow

#### Properties

- [Documentation](https://argoproj.github.io/argo-workflows/)
- [GitHub](https://github.com/argoproj/argo-workflows)
- [OpenAPI](https://raw.githubusercontent.com/argoproj/argo-workflows/main/api/openapi-spec/swagger.json)

## Schemas

| Artifact | Description |
|---|---|
| [Microservice Schema](json-schema/scalable-architecture-microservice-schema.json) | JSON Schema for a microservice including API contract, dependencies, resource requirements, scaling config, and resilience settings. |
| [Domain Event Schema](json-schema/scalable-architecture-event-schema.json) | CloudEvents-compliant JSON Schema for domain events enabling loose coupling across microservices via Kafka, RabbitMQ, and cloud message brokers. |

## Structures

| Artifact | Description |
|---|---|
| [Microservice Structure](json-structure/scalable-architecture-microservice-structure.json) | Hierarchical field documentation for microservice definitions in a scalable architecture. |
| [Domain Event Structure](json-structure/scalable-architecture-event-structure.json) | Hierarchical field documentation for CloudEvents-compliant domain events including partitioning, correlation, and dead letter metadata. |

## Linked Data

| Artifact | Description |
|---|---|
| [Scalable Architecture Context](json-ld/scalable-architecture-context.jsonld) | JSON-LD context mapping architecture vocabulary to schema.org, Kubernetes, and CNCF namespaces. |

## Examples

| Artifact | Description |
|---|---|
| [Microservice Example](examples/scalable-architecture-microservice-example.json) | Example microservice definition for an order-service with circuit breaker, retry, HPA scaling, and full observability config. |
| [Domain Event Example](examples/scalable-architecture-event-example.json) | Example CloudEvents-compliant order.created domain event with correlation ID, partition key, and order payload for Kafka-based event streaming. |

## Vocabulary

| Artifact | Description |
|---|---|
| [Scalable Architecture Vocabulary](vocabulary/scalable-architecture-vocabulary.yml) | Normative vocabulary covering microservices, service mesh, event-driven patterns, resilience, observability, and SRE concepts. |

## Common Properties

- [CNCF Landscape](https://landscape.cncf.io/)
- [GitHub Organization](https://github.com/cncf)
- [Blog](https://www.cncf.io/blog/)

## Maintainers

**API Evangelist** — [kin@apievangelist.com](mailto:kin@apievangelist.com) — [https://apievangelist.com](https://apievangelist.com)
