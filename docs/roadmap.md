# Roadmap

> **Learn deeply. Build incrementally. Explain everything.**

This roadmap defines the long-term engineering journey behind **Platform Engineering Lab**.

The goal of this repository is not to complete courses or collect certifications. Instead, it is to progressively acquire the knowledge, practical experience, and engineering discipline required to design, build, operate, and evolve production-grade cloud-native systems.

Every capability is developed through a consistent engineering workflow:

```text
Plan
    ↓
Study
    ↓
Experiment
    ↓
Build
    ↓
Review
    ↓
Document
    ↓
Reflect
```

Learning is considered complete only when the knowledge has been applied in the project, documented, and reflected upon.

## Repository Evolution 
This repository intentionally grows in small, incremental steps. 
New technologies are introduced only when they solve a real engineering problem within the project. 
The goal is to understand not only *how* to use a technology, but also *why* it exists and what trade-offs it introduces.
The repository evolves together with the engineer building it. Each phase extends the existing foundation rather than replacing it, allowing both the software and the engineering practices to mature organically.
**Complexity is introduced deliberately**. Every dependency, framework, tool, or architectural pattern should have a clear justification. The simplest solution that satisfies the current requirements is preferred until new requirements justify additional complexity.

---

# Engineering Principles

This repository follows a few core principles.

## Build Incrementally

The project grows through small, focused improvements rather than large rewrites.

Every Pull Request should leave the repository in a better state than before.

## Production Over Demo

The objective is not to create tutorials or throwaway examples.

Every implementation should be written as if another engineer will maintain it in production.

## Cloud-Provider Agnostic

The project is intentionally built on open standards and portable technologies.

Cloud integrations are optional extensions rather than core requirements.

## Observability by Design

Every component should be designed to be understandable and debuggable.

Observability is treated as a fundamental engineering concern rather than an afterthought.

## Explain Every Decision

Every significant engineering decision should be documented.

Understanding *why* a solution exists is just as important as understanding *how* it works.

## Learn Continuously

The repository is both a software project and an engineering journal documenting continuous learning and improvement.

---

# Learning Resources

Different resources serve different purposes.

## Theory

* Official documentation
* Books
* Technical blogs
* Conference talks
* Udemy

## Hands-on Labs

* KodeKloud
* iximiuz Labs

## Practical Application

Every important concept should eventually be implemented somewhere in this repository.

Theory without implementation is incomplete.

---

# Roadmap

The roadmap is organized into engineering capabilities rather than technologies.

Each phase builds naturally upon the previous one.

---

# Phase 1 — Go Foundations

## Objective

Build a production-quality HTTP service while mastering modern Go development practices.

## Topics

* Project structure
* Modules and packages
* Error handling
* Interfaces
* Context propagation
* HTTP servers
* Middleware
* Configuration
* Structured logging
* Testing
* Benchmarking
* Profiling
* Graceful shutdown

## Deliverables

* Production-quality HTTP service
* Unit tests
* Performance benchmarks
* Engineering documentation

---

# Phase 2 — Observability

## Objective

Understand how modern production systems become observable.

## Topics

* Metrics
* Prometheus
* OpenTelemetry
* Tracing
* Logging
* Grafana
* Loki
* Tempo
* Alerting

## Deliverables

* Prometheus metrics
* Distributed tracing
* Structured logs
* Dashboards
* Alerts

---

# Phase 3 — Linux & Networking

## Objective

Understand the operating system and networking foundations behind modern applications.

## Topics

* Processes
* Threads
* Scheduling
* TCP/IP
* DNS
* HTTP
* Filesystems
* Namespaces
* cgroups
* Sockets

## Deliverables

* Linux experiments
* Networking exercises
* Learning notes

---

# Phase 4 — Containers

## Objective

Package and run applications consistently across environments.

## Topics

* Container images
* Multi-stage builds
* Image optimization
* Container networking
* Security

## Deliverables

* Production-ready container image
* Local development environment

---

# Phase 5 — Kubernetes

## Objective

Deploy and operate cloud-native applications using Kubernetes.

## Topics

* Deployments
* Services
* Ingress
* ConfigMaps
* Secrets
* RBAC
* Probes
* Autoscaling
* Helm

## Deliverables

* Kubernetes deployment
* Helm chart
* Operational documentation

---

# Phase 6 — Platform Engineering

## Objective

Build the engineering platform that supports software delivery.

## Topics

* CI/CD
* GitHub Actions
* GitOps
* Infrastructure as Code
* Secrets management
* Platform automation

## Deliverables

* Automated CI pipeline
* GitOps deployment workflow

---

# Phase 7 — Distributed Systems

## Objective

Design reliable distributed applications.

## Topics

* Service discovery
* Messaging
* Retry strategies
* Idempotency
* Rate limiting
* Circuit breakers
* CAP theorem
* Consensus
* Leader election

## Deliverables

* Multi-service architecture
* Failure simulations
* Distributed tracing

---

# Phase 8 — eBPF & Cloud-Native Networking

## Objective

Understand modern networking and kernel observability.

## Topics

* eBPF
* Cilium
* Tetragon
* XDP
* Network policies
* Service mesh concepts

## Deliverables

* eBPF experiments
* Kubernetes networking labs

---

# Phase 9 — Performance Engineering

## Objective

Measure, analyze, and improve system performance.

## Topics

* Profiling
* Benchmarking
* Memory optimization
* CPU optimization
* Load testing
* Scalability

## Deliverables

* Benchmark suite
* Performance reports
* Optimization case studies

---

# Phase 10 — Production Engineering

## Objective

Operate systems using production-grade engineering practices.

## Topics

* Incident response
* Root cause analysis
* SLOs
* SLIs
* Error budgets
* Capacity planning
* Reliability
* Security

## Deliverables

* Operational playbooks
* Incident simulations
* Reliability improvements

---

# How Progress Is Measured

Progress is measured by engineering capability rather than completed courses.

A phase is considered complete when:

* The concepts are understood.
* The knowledge has been applied in code.
* The implementation is tested.
* Engineering decisions are documented.
* Lessons learned have been recorded.
* The solution could be confidently explained during a senior engineering interview.

---

# Long-Term Vision

The long-term goal is to become a platform engineer capable of designing, implementing, operating, and evolving production-grade cloud-native systems using open standards and modern engineering practices.

By the end of this journey, this repository should demonstrate not only technical knowledge, but also engineering discipline, architectural thinking, operational excellence, and continuous learning.

