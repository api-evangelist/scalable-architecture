# Scalable Architecture

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

## Structures

| Artifact | Description |
|---|---|
| [Microservice Structure](json-structure/scalable-architecture-microservice-structure.json) | Hierarchical field documentation for microservice definitions in a scalable architecture. |

## Linked Data

| Artifact | Description |
|---|---|
| [Scalable Architecture Context](json-ld/scalable-architecture-context.jsonld) | JSON-LD context mapping architecture vocabulary to schema.org, Kubernetes, and CNCF namespaces. |

## Examples

| Artifact | Description |
|---|---|
| [Microservice Example](examples/scalable-architecture-microservice-example.json) | Example microservice definition for an order-service with circuit breaker, retry, HPA scaling, and full observability config. |

## Vocabulary

| Artifact | Description |
|---|---|
| [Scalable Architecture Vocabulary](vocabulary/scalable-architecture-vocabulary.yml) | Normative vocabulary covering microservices, service mesh, event-driven patterns, resilience, observability, and SRE concepts. |

## Maintainers

**API Evangelist** — [kin@apievangelist.com](mailto:kin@apievangelist.com) — [https://apievangelist.com](https://apievangelist.com)
