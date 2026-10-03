# Daniël van Ginneken

Software developer focused on backend systems, distributed architectures, and infrastructure, based in the Netherlands.

I build backend services, event-driven systems, and the platforms they run on — from ASP.NET Core applications and PostgreSQL databases to Linux servers, networking, and observability.

---

Studying Computer Science at Avans University of Applied Sciences and currently interning as a fullstack developer at Basic-Fit. Before that, I spent almost four years at Dentech, growing from junior support engineer to system support engineer. My background spans both infrastructure (Linux, Proxmox, Cisco, VLANs) and backend engineering (ASP.NET Core, PostgreSQL, RabbitMQ), allowing me to think about systems at every layer, from network topology to application design.

**Current engineering interests:** event-driven architectures · distributed systems · observability · backend API design · infrastructure automation · cloud-native systems

---

## Projects

### [PatientPingeling](https://github.com/PatientPingeling/PatientPingeling)
*Multi-tenant notification platform — ASP.NET Core · RabbitMQ · PostgreSQL · OpenTelemetry*

Event-driven notification dispatch system that routes messages across multiple providers (email, SMS, push). Designed around clean architecture with per-tenant configuration, asynchronous message processing via RabbitMQ, a provider abstraction layer for pluggable notification providers, and distributed tracing, metrics, and structured logging through OpenTelemetry. Deployed via Docker Compose.

### [OpenCaptive](https://github.com/danielvanginneken/OpenCaptive)
*Modern captive portal platform — ASP.NET Core · PostgreSQL · Docker · Networking*

Open-source captive portal platform designed for modern networks. Focused on authentication, tenant management, extensibility, and operational simplicity. Built with a backend-first architecture and designed to integrate with networking environments commonly found in MSP, hospitality, education, and enterprise deployments.

### Homelab
*Self-hosted infrastructure — Proxmox · Linux · Docker · VLANs · Monitoring*

Personal infrastructure stack consisting of virtualized workloads, VLAN-segmented networking, containerized services, centralized monitoring, backup strategies, and automation. Used to experiment with production-style infrastructure patterns, observability, security, and deployment workflows.

---

## Currently Building

### SynqWealth
*Personal finance and wealth management platform — ASP.NET Core · PostgreSQL · TypeScript*

Personal finance platform unifying bank accounts and investment positions into a single view: transaction ingestion and categorisation, transfer matching between own accounts, budgeting, and long-term wealth tracking. Currently being ported from its original TypeScript API to ASP.NET Core, largely as a deliberate exercise in porting a working system rather than rewriting one.

**On the bench:** *Aegis.Auth* (identity & access management — centralized identity, MFA, OAuth/OIDC, RBAC) and *StrengthSuite* (workout tracking and progression analysis). Both are designs I return to, not active builds.

---

## Stack

```text
Backend        C# / .NET, ASP.NET Core, Entity Framework Core
Messaging      RabbitMQ
Databases      PostgreSQL, SQL Server
Frontend       React, TypeScript, Next.js
Observability  OpenTelemetry, Metrics, Tracing, Structured Logging
Infrastructure Linux, Proxmox, Docker
Networking     Cisco IOS, VLANs, Routing, Firewalls, DNS, DHCP
Automation     PowerShell, Bash
```

---

**Currently learning:** distributed systems design, cloud-native architectures, software architecture, observability, and scalable backend systems.

[CV (PDF)](https://github.com/danielvanginneken/danielvanginneken/releases/latest) · [LinkedIn](https://www.linkedin.com/in/danielvanginneken) · [Website](https://danielvanginneken.com) · [GitHub](https://github.com/danielvanginneken) · dcjvanginneken@gmail.com
