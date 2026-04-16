# StratiSYSTEM OS

**The modern infrastructure operating system**

StratiSYSTEM™ is a unified infrastructure operating system that lets organizations run compute virtualization, storage virtualization, or both from a common software foundation. It supports tiered, hyper-converged, and hybrid deployment models, runs on standard x86 hardware, and is designed to scale from compact environments to large multi-node infrastructure.

StratiSYSTEM is the software foundation behind SteelDome’s platform portfolio:

- **StratiSTOR** for software-defined storage
- **StratiSERV** for virtualization and container orchestration
- **HyperSERV** for integrated hyper-converged infrastructure

Whether the goal is to modernize virtualization, deploy scalable storage, build private cloud infrastructure, extend services to the edge, or standardize a full-stack software-defined platform, StratiSYSTEM provides a common operating layer for performance, resilience, and operational consistency.

---

## Table of Contents

- [Overview](#overview)
- [Why StratiSYSTEM](#why-stratisystem)
- [Platform Components](#platform-components)
- [Deployment Models](#deployment-models)
- [Core Capabilities](#core-capabilities)
- [Common Use Cases](#common-use-cases)
- [Getting Started](#getting-started)
- [Documentation](#documentation)
- [Who It’s For](#who-its-for)
- [Support](#support)

---

## Overview

StratiSYSTEM is a modular infrastructure OS built to unify software-defined storage, virtualization, orchestration, and modern infrastructure services under one operating foundation.

It is designed for organizations that want to:

- Deploy infrastructure in minutes instead of spending days or weeks assembling fragmented stacks
- Eliminate hardware and vendor lock-in
- Scale compute and storage independently or together
- Support virtual machines, containers, and block, file, and object workloads on one platform
- Simplify operations across core, edge, and distributed environments
- Standardize infrastructure around a flexible, automation-ready software layer

At its core, StratiSYSTEM transforms standard hardware into a cohesive infrastructure platform that can be adapted to different workload types, operating models, and long-term growth strategies.

<img width="3075" height="1722" alt="image" src="https://github.com/user-attachments/assets/9c06ae6a-0624-41ae-bfbe-71e9666ec771" />

---

## Why StratiSYSTEM

Traditional infrastructure often forces organizations into rigid hardware choices, fragmented tooling, disruptive upgrade cycles, and operational inconsistency.

StratiSYSTEM takes a different approach.

It provides a modular, vendor-agnostic operating foundation that allows infrastructure teams to standardize on one software platform while choosing the deployment architecture that best fits the workload. Instead of maintaining separate stacks for storage, compute, and orchestration, teams can operate from a unified environment designed for scale, flexibility, and resilience.

### What that means in practice

- **Hardware freedom**: Deploy on standard x86 infrastructure and align hardware strategy to your own operational goals
- **Architectural flexibility**: Run storage and compute separately or together depending on performance, density, or operational requirements
- **Resilience by design**: Support continuity through distributed architectures built for availability and fault tolerance
- **Automation readiness**: Integrate with APIs, orchestration frameworks, monitoring platforms, and external tooling
- **Non-disruptive growth**: Expand and evolve infrastructure without unnecessary operational disruption

---

## Platform Components

### StratiSTOR

StratiSTOR is SteelDome’s software-defined storage layer, delivering scalable **block, file, and object** services with enterprise-grade performance and resilience.

StratiSTOR is designed for environments that require:

- Dedicated storage clusters
- Tiered architectures with independent storage scaling
- High-capacity and high-throughput environments
- Backup, archive, and multi-site data services
- A storage foundation for virtualization, analytics, AI, media, and research workloads

### StratiSERV

StratiSERV is the software-defined compute layer for **virtual machines, containers, and modern workload orchestration**.

It is built to simplify deployment, management, and scaling of compute infrastructure through capabilities such as:

- Unified VM and container management
- High availability and live migration
- Snapshot-based operations and automated failover
- Role-based access control and multi-tenant operations
- GPU-enabled workloads
- Centralized dashboards, automation workflows, and API integration

### HyperSERV

HyperSERV combines StratiSTOR and StratiSERV into a single **hyper-converged infrastructure (HCI)** platform.

This model unifies compute, storage, and orchestration on the same nodes and is well suited for organizations that want:

- Simplified deployment and lifecycle management
- A smaller infrastructure footprint
- Unified scaling of compute and storage
- High-throughput environments for enterprise, AI, edge, and service-provider use cases
- Multi-protocol storage access alongside VM and container services

---

## Deployment Models

StratiSYSTEM is designed to support multiple architectural approaches under the same operating foundation.

### Tiered

Use dedicated compute and storage layers when you want to scale each independently or maintain architectural separation between services.

Typical fit:

- High-density storage environments
- Dedicated virtualization clusters
- Performance isolation between compute and storage tiers
- Large-scale enterprise and service-provider designs

### Hyper-Converged

Run compute and storage together on the same nodes through HyperSERV to simplify management, reduce footprint, and create a unified operational model.

Typical fit:

- Private cloud environments
- Edge and remote office deployments
- Compact production clusters
- Organizations prioritizing operational simplicity

### Hybrid and Federated

Mix tiered and hyper-converged models across sites, regions, or workload domains while maintaining a common software foundation.

Typical fit:

- Multi-site deployments
- Regional infrastructure growth
- Mixed workload environments
- Distributed operations spanning core and edge

---

## Core Capabilities

### Unified infrastructure foundation

StratiSYSTEM provides a common operating layer across storage, virtualization, orchestration, networking, and service control so organizations can standardize operations without locking themselves into a single hardware or architecture model.

### Flexible scale from compact to large environments

The platform supports **single-node, dual-node, multi-node, and large-scale cluster** deployment patterns, allowing organizations to start small and expand as requirements grow.

### Software-defined storage and compute

Across the platform, SteelDome supports:

- **Block, file, and object storage services**
- **Virtual machine and container orchestration**
- **Private cloud and hybrid infrastructure models**
- **Distributed and edge deployment patterns**

### API-first automation

The StratiSYSTEM REST API provides a unified interface for managing **compute, storage, networking, and service orchestration** across the distributed cluster. This makes the platform suitable for automation, integration, and lifecycle management at cluster scale.

### Open integration model

StratiSYSTEM is designed for modern environments that need integration with external monitoring, orchestration, and automation frameworks. Public cloud storage integration and OpenStack support are also documented as part of the broader platform capability set.

### Operational resilience

The platform is built around distributed, resilient architectures intended to support continuity through component, node, and broader infrastructure failures, with support for high availability, replication, and scalable growth models across the product stack.

---

## Common Use Cases

### Private cloud and virtualization modernization

Replace fragmented or legacy virtualization stacks with a unified platform for VMs, containers, automation, and operational control.

### Artificial intelligence and accelerated infrastructure

Use StratiSTOR to feed large datasets into GPU-enabled environments on StratiSERV, or deploy HyperSERV for AI-ready infrastructure that supports model training, inference, analytics, and MLOps workflows.

### Managed services and multi-tenant platforms

Build IaaS, backup, disaster recovery, hosted desktop, and hybrid infrastructure offerings from one software-defined foundation with support for role-based access control and multi-tenant operations.

### Healthcare infrastructure

Support EHR/EMR systems, PACS and medical imaging archives, secure remote access, and compliance-driven infrastructure with scalable storage, resilient virtualization, and unified operations.

### Media and entertainment workflows

Power real-time editing, post-production, rendering, transcoding, digital asset management, distributed collaboration, and AI-assisted media pipelines with high-throughput compute and storage.

### Scientific research and HPC-adjacent environments

Support genomics, bioinformatics, simulation, modeling, AI-driven analysis, and large-scale collaborative research through scalable storage and flexible compute delivery.

### Edge and distributed operations

Standardize infrastructure delivery across core, edge, branch, and remote sites while preserving centralized control and consistent operations.

---

## Getting Started

StratiSYSTEM is installed as an operating system on each node.

### High-level installation flow

1. Boot each target node using the StratiSYSTEM OS ISO.
2. Mount the ISO through your out-of-band management interface such as **Dell DRAC**, **HPE iLO**, **Supermicro IPMI**, or equivalent remote management tooling.
3. Install the operating system on each node.
4. Build out the target architecture as StratiSTOR, StratiSERV, or HyperSERV depending on the intended deployment model.
5. Use the platform documentation and API to configure services, scale the environment, and automate operations.

For larger rollouts, the documentation also notes support for deployment workflows using **Clonezilla** and other third-party image deployment platforms.

---

## Documentation

Official documentation is available on the SteelDome Wiki.

### Core documentation

- **Wiki Home**: https://wiki.steeldome.com/
- **StratiSYSTEM OS Overview**: https://wiki.steeldome.com/en/stratisystem-os-overview
- **StratiSYSTEM Installation Guide**: https://wiki.steeldome.com/en/stratisystem-installation-guide
- **StratiSYSTEM API Guide**: https://wiki.steeldome.com/en/stratisystem-api-guide
- **Features and Specifications**: https://wiki.steeldome.com/en/features-and-specifications

### Product overviews

- **Introduction to StratiSTOR**: https://wiki.steeldome.com/en/introduction-to-stratistor
- **Introduction to StratiSERV**: https://wiki.steeldome.com/en/introduction-to-stratiserv
- **Introduction to HyperSERV**: https://wiki.steeldome.com/en/introduction-to-hyperserv

### Selected use case references

- **HPC and Supercomputing**: https://wiki.steeldome.com/en/use-case-hpc-sc
- **Artificial Intelligence**: https://wiki.steeldome.com/en/use-case-ai
- **Managed Service Providers**: https://wiki.steeldome.com/en/use-case-msp
- **Healthcare**: https://wiki.steeldome.com/en/use-case-healthcare
- **Scientific Research**: https://wiki.steeldome.com/en/use-case-research
- **Media and Entertainment**: https://wiki.steeldome.com/en/use-case-media
- **Legal**: https://wiki.steeldome.com/en/use-case-legal

---

## Who It’s For

StratiSYSTEM is designed for organizations and teams that need a more unified and adaptable infrastructure operating model, including:

- Enterprise infrastructure and platform teams
- Private cloud architects and virtualization operators
- Managed service providers and hosting companies
- Research and data-intensive computing environments
- Healthcare organizations with security and continuity requirements
- Media organizations running high-performance content workflows
- Edge and distributed operations teams

---

## Support

For product documentation, deployment guidance, and platform overviews, start with the official SteelDome Wiki:

**https://wiki.steeldome.com/**

If this repository is being used for customer, partner, or internal enablement, align issue tracking, documentation changes, and support workflows with your standard SteelDome process.

---

**StratiSYSTEM™ OS**  
One operating system. Infinite possibilities.
