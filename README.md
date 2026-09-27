# **StratiSYSTEM™ OS**

## **The Universal Infrastructure Operating System**

**StratiSYSTEM OS** is SteelDome Technologies’ full-stack infrastructure operating system for building storage, virtualization, hyper-converged infrastructure, private cloud, Kubernetes, AI, HPC, edge, and data-intensive platforms from standard server hardware.

Rather than assembling independent hypervisors, storage systems, container platforms, networking tools, monitoring frameworks, and management planes, StratiSYSTEM provides a common software foundation across the infrastructure stack.

Organizations can deploy dedicated storage with **StratiSTOR**, dedicated compute and virtualization with **StratiSERV**, or combine both through **HyperSERV**, SteelDome’s **hyper-converged infrastructure (HCI)** architecture.

StratiSYSTEM supports architectures ranging from compact single-node and edge systems to multi-node enterprise clusters, large storage environments, GPU infrastructure, HPC systems, private clouds, and rack-scale AI platforms.

The platform is designed around a simple principle:

> **The hardware architecture can change without forcing the operational model to change.**

Storage and compute can run independently, together, or across multiple locations while retaining the same StratiSYSTEM management, automation, monitoring, and operational framework.

### SteelDome platform components

- **StratiSTOR** — software-defined storage for block, file, object, high-performance data services, and distributed storage workloads
- **StratiSERV** — software-defined compute, virtual machine infrastructure, container orchestration, GPU workloads, and infrastructure management
- **HyperSERV** — integrated **hyper-converged infrastructure (HCI)** combining StratiSTOR and StratiSERV on the same systems
- **StratiSYSTEM OS** — the common operating system, management framework, automation layer, and infrastructure foundation behind all three architectures

Whether the goal is replacing a legacy virtualization platform, consolidating infrastructure, delivering high-performance file services, deploying Kubernetes, building a sovereign private cloud, supporting GPU workloads, feeding AI pipelines, operating a Lustre environment, or creating a large-scale storage platform, StratiSYSTEM provides a consistent foundation.

For platform demonstrations, architecture overviews, feature walkthroughs, and advanced use cases, visit the SteelDome Technologies YouTube channel:

https://www.youtube.com/@SteelDomeTechnologies

**One operating system. Infinite possibilities.**

---

# Table of Contents

- [Overview](#overview)
- [Platform Architecture](#platform-architecture)
- [Platform Components](#platform-components)
  - [StratiSTOR](#stratistor)
  - [StratiSERV](#stratiserv)
  - [HyperSERV HCI](#hyperserv-hci)
- [Storage and Data Services](#storage-and-data-services)
- [High-Performance SMB, NFS, and S3](#high-performance-smb-nfs-and-s3)
- [Lustre and HPC Storage](#lustre-and-hpc-storage)
- [Virtualization](#virtualization)
- [Containers and Kubernetes](#containers-and-kubernetes)
- [GPU and Accelerated Computing](#gpu-and-accelerated-computing)
- [GPU Thermal Management](#gpu-thermal-management)
- [SDCache Acceleration](#sdcache-acceleration)
- [Networking](#networking)
- [High Availability and Clustering](#high-availability-and-clustering)
- [Data Protection and Recovery](#data-protection-and-recovery)
- [Infrastructure Automation and APIs](#infrastructure-automation-and-apis)
- [Monitoring and Hardware Visibility](#monitoring-and-hardware-visibility)
- [Security](#security)
- [Deployment Models](#deployment-models)
- [Hardware Flexibility](#hardware-flexibility)
- [Common Use Cases](#common-use-cases)
- [Getting Started](#getting-started)
- [Documentation](#documentation)
- [Who Its For](#who-its-for)
- [Support](#support)

---

# Overview

StratiSYSTEM is a modular infrastructure operating system built to unify software-defined storage, virtualization, container orchestration, high-performance data services, networking, acceleration, monitoring, and infrastructure management.

It transforms standard x86 servers into complete infrastructure platforms without requiring organizations to adopt a proprietary hardware architecture.

StratiSYSTEM is designed for organizations that want to:

- Replace fragmented infrastructure stacks with a common operating platform
- Deploy storage, compute, containers, and HCI from the same software foundation
- Scale compute and storage independently or together
- Support virtual machines and containers within the same infrastructure
- Deliver block, file, object, and high-performance parallel storage
- Build private and sovereign cloud environments
- Deploy GPU-enabled AI and accelerated computing platforms
- Operate high-throughput SMB, NFS, and S3 services
- Support Lustre-based HPC and scientific computing environments
- Integrate NVMe and high-speed networking
- Automate infrastructure through APIs
- Standardize operations across core, edge, cloud-adjacent, and distributed locations
- Reduce dependence on proprietary infrastructure stacks
- Preserve hardware choice as infrastructure requirements evolve

StratiSYSTEM provides the common operational layer across these environments.

<img width="3075" height="1722" alt="StratiSYSTEM Architecture" src="https://github.com/user-attachments/assets/9c06ae6a-0624-41ae-bfbe-71e9666ec771" />

---

# Platform Architecture

StratiSYSTEM separates the **software platform** from the **physical deployment model**.

An organization can use the same StratiSYSTEM foundation to build:

- A dedicated storage cluster
- A dedicated virtualization cluster
- Hyper-converged infrastructure
- A Kubernetes platform
- A private cloud
- A GPU compute environment
- An AI infrastructure platform
- A Lustre-based HPC environment
- A high-performance NAS platform
- An S3-compatible object platform
- A multi-protocol data services platform
- An edge infrastructure footprint
- A geographically distributed infrastructure architecture

This allows infrastructure to evolve without requiring the organization to continually replace its management model.

For example, StratiSERV can operate as a dedicated compute tier using external Fibre Channel, iSCSI, NVMe, or other enterprise storage systems.

The same StratiSERV software can also operate directly with StratiSTOR as part of HyperSERV HCI.

Likewise, StratiSTOR can operate independently as a dedicated storage platform or provide storage directly to StratiSERV, Kubernetes, physical systems, applications, AI environments, and external clients.

The components change location.

The software model remains consistent.

---

# Platform Components

## StratiSTOR

**StratiSTOR** is SteelDome’s software-defined storage platform.

It provides distributed, scalable storage services for enterprise applications, virtualization, containers, analytics, AI, media, research, backup, archive, and general-purpose data infrastructure.

StratiSTOR supports:

- Block storage
- File storage
- Object storage
- SMB services
- NFS services
- S3-compatible object services
- High-throughput NAS workloads
- Distributed storage
- Scale-out storage architectures
- High-capacity storage environments
- NVMe-based performance architectures
- Multi-protocol data access
- Snapshot-based workflows
- Replication and resilience
- Storage for virtual machines
- Storage for Kubernetes
- Storage for physical applications
- Storage for AI and analytics
- Storage for media workflows
- Storage for backup and archive
- Multi-site infrastructure designs

StratiSTOR can be deployed as a dedicated storage tier or integrated directly with StratiSERV through HyperSERV.

### Designed for scale

StratiSTOR is intended to scale across both capacity and performance dimensions.

Organizations can expand environments by adding:

- Storage devices
- NVMe resources
- Cache resources
- Network bandwidth
- Storage nodes
- Additional protocol endpoints

This allows systems to grow without requiring a forklift replacement of the entire storage architecture.

### Block storage

StratiSTOR block services can provide storage for:

- StratiSERV virtual machines
- Databases
- Physical servers
- Container environments
- Application platforms
- External systems

Gateway services can also be used to expose StratiSTOR-backed block storage through enterprise connectivity models such as **Fibre Channel**, including multipath architectures.

### File storage

StratiSTOR supports scalable file services for both conventional enterprise workloads and high-throughput environments.

Supported use cases include:

- General enterprise file services
- Media and entertainment
- Rendering
- Post-production
- AI datasets
- Scientific datasets
- Backup repositories
- Application data
- User shares
- Collaborative environments
- Large sequential workloads
- High-concurrency workloads

### Object storage

S3-compatible object services allow StratiSTOR to participate in modern application, backup, analytics, and cloud-oriented workflows.

Object storage can be used alongside block and file services on the same infrastructure platform.

---

# StratiSERV

**StratiSERV** is SteelDome’s software-defined compute, virtualization, and workload infrastructure platform.

It provides the virtual machine layer used throughout StratiSYSTEM environments.

StratiSERV supports enterprise virtualization capabilities including:

- Virtual machine creation and lifecycle management
- VM start, stop, restart, suspend, and administrative operations
- Live migration
- High availability
- Automated recovery
- VM snapshots
- Virtual disk management
- Virtual disk expansion
- VM cloning
- Backup and restore
- Restore to alternate virtual machines
- File-level restore workflows
- Virtual networking
- Virtual bridges
- VLAN-aware networking
- UEFI virtual machines
- Secure Boot capable VM configurations
- Virtual TPM support
- Modern virtual hardware platforms
- GPU-enabled virtual machines
- Hardware passthrough where applicable
- External enterprise storage
- StratiSTOR-backed virtual machine storage
- Role-based management
- API-driven management
- Centralized infrastructure administration

StratiSERV can use storage from:

- StratiSTOR
- Fibre Channel systems
- iSCSI storage
- NVMe storage architectures
- Other compatible enterprise storage platforms

This makes StratiSERV usable both as an independent virtualization platform and as part of a complete SteelDome infrastructure stack.

---

# HyperSERV HCI

**HyperSERV** is SteelDome’s **hyper-converged infrastructure (HCI)** architecture.

HyperSERV combines **StratiSTOR storage and StratiSERV compute on the same physical systems**, allowing storage, virtualization, containers, networking, and infrastructure services to operate from a unified node architecture.

HyperSERV is suited for organizations that want:

- Integrated compute and storage
- Reduced physical infrastructure footprint
- Simplified deployment
- Unified lifecycle management
- Scale-out infrastructure
- Private cloud platforms
- Virtualization modernization
- Edge infrastructure
- Kubernetes
- GPU environments
- AI workloads
- Enterprise application infrastructure
- Service-provider platforms

HyperSERV does not create a separate operational model.

It uses the same StratiSYSTEM services, StratiSTOR capabilities, and StratiSERV functionality available in tiered deployments.

This allows organizations to mix dedicated and HCI architectures while maintaining a common operational framework.

---

# Storage and Data Services

StratiSYSTEM is designed to support multiple data access models without requiring a separate infrastructure platform for each protocol.

Depending on the architecture, StratiSTOR can deliver:

| Capability | Typical Workloads |
|---|---|
| Block | VMs, databases, application servers |
| SMB | Enterprise file services, media, Windows environments |
| NFS | Linux, Unix, application, AI, and research workloads |
| S3 | Object, backup, cloud-native applications, analytics |
| Lustre | HPC, AI, simulation, scientific computing |
| Fibre Channel gateway | Enterprise SAN integration |
| High-performance local storage | Scratch, staging, cache, application data |

These services allow StratiSYSTEM infrastructure to support both traditional enterprise workloads and modern data-intensive applications.

---

# High-Performance SMB, NFS, and S3

StratiSYSTEM includes support for **high-speed SMB, NFS, and S3 data services** intended to take advantage of modern CPU, memory, NVMe, and high-speed Ethernet architectures.

The objective is not simply to expose a protocol.

The objective is to allow the data path to take advantage of the performance available from the underlying hardware.

High-performance file and object architectures can include:

- Multi-core processing
- Parallel request handling
- Large numbers of concurrent clients
- High-speed Ethernet
- NVMe-backed storage
- Large-memory servers
- Multiple protocol endpoints
- Scale-out storage backends
- Dedicated local storage
- StratiSTOR-backed storage

### SMB

SMB services are suitable for:

- Enterprise file access
- Windows clients
- Media workstations
- Editing environments
- Content creation
- Digital asset management
- High-concurrency user access

Architectures can also take advantage of **SMB multichannel** and multiple network paths when appropriate.

### NFS

High-performance NFS services support:

- Linux and Unix environments
- Application servers
- Kubernetes workloads
- AI pipelines
- Research systems
- Shared datasets
- HPC-adjacent workloads

### S3

S3-compatible services provide object access for:

- Cloud-native applications
- Backup platforms
- Analytics
- AI datasets
- Data repositories
- Application integration
- Long-term storage workflows

Multiple access methods can be used within the same broader StratiSYSTEM environment, allowing protocol selection to follow the application instead of forcing applications into a single storage model.

---

# Lustre and HPC Storage

StratiSYSTEM supports **Lustre** for environments that require a parallel filesystem optimized for large-scale HPC, AI, scientific computing, and data-intensive workflows.

Lustre can be incorporated into StratiSYSTEM architectures alongside StratiSTOR, StratiSERV, GPU compute, and high-speed networking.

Typical Lustre workloads include:

- HPC clusters
- AI training environments
- Scientific computing
- Simulation
- Modeling
- Genomics
- Bioinformatics
- Computational research
- Large-scale analytics
- Rendering
- Parallel application workloads

This allows an organization to use the storage architecture best suited to each workload while continuing to operate within the broader StratiSYSTEM infrastructure model.

A deployment may therefore use:

- StratiSTOR for enterprise storage and general data services
- Lustre for parallel HPC data access
- Local NVMe for scratch or staging
- SDCache for acceleration
- StratiSERV for virtualized workloads
- Kubernetes for containerized applications
- GPU nodes for accelerated computing

All can participate in the same larger infrastructure architecture.

---

# Virtualization

Virtualization is integrated directly into StratiSYSTEM through **StratiSERV**.

The platform is intended to provide a modern alternative for organizations seeking to consolidate or replace traditional virtualization stacks without requiring proprietary server hardware.

Capabilities include:

- VM lifecycle management
- Live migration
- Cluster-aware VM placement
- High availability
- Automatic restart following host failure
- Snapshot operations
- Virtual disk expansion
- VM cloning
- VM backup
- Full VM restore
- Alternate-VM restore
- File-level recovery
- UEFI
- Secure Boot
- Virtual TPM
- GPU-enabled virtual machines
- Hardware passthrough
- VLAN-aware networking
- External storage integration
- StratiSTOR integration
- Centralized dashboards
- Role-based access
- REST API management

StratiSERV allows virtualization infrastructure to remain independent from storage architecture.

Organizations can therefore deploy:

**StratiSERV + third-party storage**

or

**StratiSERV + StratiSTOR**

or

**HyperSERV HCI**

without changing the fundamental compute management model.

---

# Containers and Kubernetes

StratiSYSTEM supports Kubernetes as part of the overall infrastructure platform, allowing virtual machines, containers, storage, and infrastructure services to coexist within the same environment.

Capabilities include:

- Kubernetes cluster deployment
- Kubernetes control-plane infrastructure
- Container runtime integration
- Multi-node Kubernetes architectures
- Persistent storage integration
- StratiSTOR-backed persistent data
- High availability
- Virtual machine and container coexistence
- Infrastructure monitoring
- Centralized networking
- API-driven automation

This gives organizations flexibility in how applications are deployed.

A workload does not have to be converted from a VM to a container simply because the infrastructure platform changes.

Virtual machines and Kubernetes applications can coexist and evolve independently.

---

# GPU and Accelerated Computing

StratiSYSTEM supports GPU-enabled infrastructure for AI, machine learning, analytics, rendering, scientific computing, and other accelerated workloads.

GPU capabilities can be incorporated into:

- StratiSERV virtualization environments
- Kubernetes environments
- HyperSERV HCI
- Dedicated GPU nodes
- AI infrastructure
- HPC systems
- Hybrid compute environments

The platform can provide operational visibility into GPU resources and support their use as part of managed infrastructure.

GPU infrastructure capabilities include:

- GPU discovery
- GPU inventory
- GPU resource visibility
- GPU workload assignment
- GPU-backed virtual machines
- Containerized GPU workloads
- Accelerator-aware infrastructure
- GPU utilization monitoring
- GPU health monitoring
- Temperature monitoring
- Integration with AI and HPC storage architectures

This allows accelerators to become manageable infrastructure resources rather than isolated hardware devices.

---

# GPU Thermal Management

High-density accelerator platforms introduce infrastructure requirements that do not exist in conventional virtualization environments.

StratiSYSTEM includes support for **GPU monitoring and thermal regulation**, allowing operators to maintain visibility into accelerator operating conditions as part of the infrastructure management model.

This includes awareness of:

- GPU temperature
- GPU operating state
- Accelerator health
- Thermal conditions
- Workload utilization
- Hardware environmental status

Thermal management is particularly important for:

- Dense GPU servers
- AI training environments
- Multi-GPU systems
- Rack-scale accelerated computing
- Sustained high-utilization workloads

By incorporating GPU health and thermal awareness into infrastructure operations, StratiSYSTEM can help operators maintain stable accelerator environments rather than treating GPU hardware as an unmanaged component.

---

# SDCache Acceleration

**SDCache** provides an additional acceleration layer for workloads where frequently accessed data benefits from faster media.

SDCache can use:

- System memory
- Dedicated high-speed storage
- NVMe devices

to provide acceleration in front of underlying storage resources.

Supported deployment concepts include:

- RAM-based acceleration
- Disk-based acceleration
- NVMe acceleration
- Cache activation
- Cache lifecycle management
- Cache device replacement
- Cache removal
- Integration with StratiSTOR
- Standalone acceleration configurations

This gives administrators another mechanism for matching storage behavior to workload requirements without redesigning the complete storage architecture.

---

# Networking

StratiSYSTEM provides the networking foundation required by storage, virtualization, containers, clustering, and management services.

Supported network architectures can include:

- Ethernet bonding
- LACP
- Multiple physical interfaces
- Network bridges
- VLANs
- Tagged networks
- Jumbo frames
- High-speed Ethernet
- Redundant management networks
- Redundant storage networks
- Dedicated VM networks
- Dedicated cluster networks
- Multiple data paths

Network architecture can be adapted for:

- Storage traffic
- VM traffic
- Kubernetes
- Cluster communication
- Management
- Migration traffic
- SMB
- NFS
- S3
- AI data pipelines
- HPC workloads

This allows infrastructure architects to maintain traffic separation where required while still managing the system as a unified platform.

---

# High Availability and Clustering

StratiSYSTEM is designed around clustered infrastructure rather than isolated servers.

Depending on the deployed services, high-availability capabilities include:

- Multi-node clustering
- Service monitoring
- Automatic service recovery
- VM high availability
- Storage resilience
- Node failure handling
- Redundant networking
- Distributed storage
- Quorum-based cluster operation
- Fencing
- Shared cluster resources
- Service relocation
- Live migration
- Storage replication
- Multiple protocol endpoints

The platform is designed so that failure of an individual component does not automatically become failure of the infrastructure service.

Architectures can be designed around failure domains at the:

- Device level
- Network level
- Node level
- Rack level
- Cluster level
- Site level

depending on the application and availability requirements.

---

# Data Protection and Recovery

Data protection is integrated into the broader infrastructure lifecycle.

StratiSYSTEM supports workflows including:

- VM snapshots
- VM backup
- Full virtual machine recovery
- Restore to alternate virtual machines
- File-level VM recovery
- Storage snapshots
- Replication
- Backup repositories
- Multi-site infrastructure
- Disaster recovery architectures
- Archive workloads

Recovery workflows are designed to operate with StratiSERV and StratiSTOR rather than requiring virtualization and storage protection to exist as completely independent operational silos.

---

# Infrastructure Automation and APIs

StratiSYSTEM is designed to be automation-ready.

The **StratiSYSTEM REST API** provides programmatic access to infrastructure services and allows external platforms to interact with the environment.

API-driven operations can include areas such as:

- Compute
- Virtual machines
- Storage
- Networking
- Cluster services
- Infrastructure state
- Service orchestration
- Hardware information
- Monitoring
- Automation workflows

This allows StratiSYSTEM to integrate into:

- Infrastructure-as-code workflows
- Internal automation systems
- Provisioning platforms
- Service-provider portals
- Cloud management systems
- CI/CD pipelines
- Monitoring platforms
- Custom operational tooling

The goal is to make functionality available through automation rather than limiting operations to manual UI workflows.

---

# Monitoring and Hardware Visibility

Operating infrastructure requires visibility beyond whether a service is simply running.

StratiSYSTEM incorporates system and hardware telemetry to provide operators with infrastructure-level insight.

Visibility can include:

- CPU utilization
- Memory utilization
- Network throughput
- Storage throughput
- Disk activity
- Filesystem utilization
- Device health
- Storage capacity
- Cluster state
- Node health
- Service state
- GPU utilization
- GPU temperature
- Hardware identity
- Server manufacturer
- Server model
- Server serial number
- Drive information
- Performance history

This data can assist with:

- Capacity planning
- Troubleshooting
- Performance analysis
- Hardware lifecycle management
- Failure investigation
- Cluster operations

---

# Security

StratiSYSTEM is designed for enterprise and multi-tenant infrastructure environments where access control and workload isolation are required.

Security capabilities include areas such as:

- Role-based access control
- Administrative separation
- Multi-tenant infrastructure models
- Secure management interfaces
- Secure VM boot options
- Virtual TPM support
- Network isolation
- VLAN-based segmentation
- Storage access controls
- Cluster authentication
- API access controls

Security architecture can then be combined with external enterprise identity, network, and security systems as required by the environment.

---

# Deployment Models

One of StratiSYSTEM’s primary architectural advantages is that the same platform can support multiple infrastructure models.

## Tiered

Compute and storage operate on separate systems.

Example:

```text
+------------------------+
|      StratiSERV        |
|   Compute / VMs / K8s  |
+-----------+------------+
            |
            |
+-----------+------------+
|      StratiSTOR        |
| Block / File / Object  |
+------------------------+
```

Tiered architectures are useful when organizations want to:

- Scale compute independently
- Scale storage independently
- Preserve storage/compute separation
- Build large storage clusters
- Build dedicated virtualization clusters
- Integrate external storage
- Isolate failure or performance domains

---

## HyperSERV HCI

Compute and storage run on the same nodes.

```text
+----------------------------------+
|          HyperSERV HCI           |
|                                  |
|  StratiSERV + StratiSTOR         |
|                                  |
|  VMs | Containers | Storage      |
|  Networking | HA | Management    |
+----------------------------------+
```

This model is useful for:

- Private cloud
- Virtualization modernization
- Edge
- Remote sites
- Compact production environments
- General enterprise infrastructure
- AI infrastructure
- Service providers

---

## Hybrid

Tiered and HCI systems can coexist.

For example:

```text
                StratiSYSTEM OS
                      |
        +-------------+-------------+
        |                           |
  HyperSERV HCI              Dedicated Tier
        |                           |
 Compute + Storage       StratiSERV + StratiSTOR
```

This allows architecture to follow workload requirements instead of forcing every workload into the same topology.

---

## Distributed and Multi-Site

StratiSYSTEM can also be used as a common infrastructure foundation across multiple physical locations.

Examples include:

- Primary data center + secondary data center
- Private cloud + sovereign infrastructure
- Core + edge
- Regional infrastructure
- Remote office infrastructure
- Disaster recovery locations
- Service-provider locations

The same infrastructure model can therefore extend beyond a single cluster.

---

# Hardware Flexibility

StratiSYSTEM is designed around industry-standard server hardware.

The platform can operate across modern **Intel and AMD x86 server platforms**, allowing infrastructure teams to select hardware based on:

- Core density
- Memory capacity
- PCIe capability
- GPU requirements
- NVMe density
- Storage capacity
- Network bandwidth
- Rack density
- Power requirements
- Cost
- Workload characteristics

Different processor platforms can also participate within a broader StratiSYSTEM estate, allowing organizations to select systems based on workload rather than tying the entire infrastructure strategy to a single CPU vendor.

StratiSYSTEM supports architectures incorporating:

- NVMe SSDs
- Enterprise SSDs
- Capacity storage
- High-memory servers
- Multi-socket systems
- GPU servers
- High-density storage systems
- High-speed network adapters
- Fibre Channel adapters
- Dedicated cache devices

This allows software capability to remain consistent while the underlying hardware evolves.

---

# Common Use Cases

## Virtualization Modernization

StratiSERV provides a virtualization platform for organizations looking to modernize or replace traditional virtualization infrastructure.

Existing applications can remain virtual machines while organizations independently introduce containers, Kubernetes, automation, or new storage architectures.

---

## Private Cloud

Combine:

- StratiSERV
- StratiSTOR
- Kubernetes
- APIs
- Networking
- Automation
- High availability

to create privately operated infrastructure without requiring applications to move to a public cloud operating model.

---

## Sovereign Infrastructure

StratiSYSTEM can operate as an independent infrastructure environment for organizations that want applications and data to remain under their control.

This can complement public cloud infrastructure rather than requiring an organization to replace it.

Applications can be distributed across cloud and StratiSYSTEM environments according to availability, sovereignty, cost, or operational requirements.

---

## Artificial Intelligence

AI infrastructure requires more than GPUs.

StratiSYSTEM can combine:

- GPU compute
- High-speed storage
- NVMe
- StratiSTOR
- Lustre
- Kubernetes
- High-speed networking
- GPU monitoring
- Thermal management
- Large-capacity datasets

to create an infrastructure foundation for:

- Model training
- Inference
- Retrieval workloads
- Data preparation
- AI analytics
- MLOps
- GPU virtualization
- Containerized AI applications

---

## HPC and Supercomputing

StratiSYSTEM can support HPC architectures combining:

- Lustre
- High-speed storage
- NVMe scratch
- GPU nodes
- CPU compute nodes
- High-speed networking
- Containers
- Virtualized supporting services
- StratiSTOR enterprise data services

This makes it possible to operate specialized HPC services within the same broader infrastructure framework used for enterprise workloads.

---

## Media and Entertainment

Media workflows frequently require both extremely high sequential throughput and large numbers of concurrent users.

StratiSYSTEM can support:

- Video editing
- Post-production
- Rendering
- Transcoding
- Digital asset management
- VFX
- Content collaboration
- AI-assisted media workflows
- Archive
- Content distribution

through high-performance SMB, NFS, StratiSTOR, NVMe, GPU compute, and high-speed networking.

---

## Scientific Research

Research environments can use StratiSYSTEM for:

- Genomics
- Bioinformatics
- Simulation
- Modeling
- Large datasets
- AI analysis
- Collaborative research
- HPC
- Lustre
- High-performance NAS
- GPU compute

while retaining enterprise storage and virtualization services within the same overall platform.

---

## Healthcare

Healthcare environments can use StratiSYSTEM for:

- EHR/EMR infrastructure
- PACS
- Medical imaging
- Virtual desktops
- Databases
- Backup
- Archive
- Secure remote applications
- AI-assisted imaging
- High-availability applications

---

## Managed Service Providers

Service providers can build infrastructure services around:

- Virtual machines
- Storage
- Kubernetes
- Backup
- Disaster recovery
- Hosted applications
- Multi-tenant environments
- Private cloud
- Infrastructure-as-a-Service

using the same software platform.

---

## Edge Infrastructure

The same StratiSYSTEM architecture can be deployed at smaller scale for:

- Branch locations
- Remote facilities
- Manufacturing
- Retail
- Telecom
- Industrial systems
- IoT
- Remote application infrastructure

and managed using the same concepts as larger data-center deployments.

---

# Getting Started

StratiSYSTEM is installed as an operating system on each participating server.

## High-Level Installation Flow

1. Boot the target system using the **StratiSYSTEM OS ISO**.
2. Mount the ISO locally or through the server’s out-of-band management controller.
3. Install StratiSYSTEM OS.
4. Configure networking and system prerequisites.
5. Add systems to the intended infrastructure architecture.
6. Deploy the required platform role:
   - StratiSTOR
   - StratiSERV
   - HyperSERV HCI
   - Kubernetes
   - High-performance data services
   - HPC/Lustre services
   - GPU infrastructure
7. Configure storage, compute, networking, and cluster services.
8. Use the StratiSYSTEM interface or REST API for ongoing infrastructure operations.

Common out-of-band management platforms include:

- Supermicro IPMI/BMC
- Dell iDRAC
- HPE iLO
- Other standards-based server management interfaces

For larger deployments, image-based and automated provisioning systems can also be incorporated into deployment workflows.

---

# Documentation

Official documentation is available through the SteelDome Technologies Wiki.

## Core Documentation

- **Wiki Home:** https://wiki.steeldome.com/
- **StratiSYSTEM OS Overview:** https://wiki.steeldome.com/en/stratisystem-os-overview
- **StratiSYSTEM Installation Guide:** https://wiki.steeldome.com/en/stratisystem-installation-guide
- **StratiSYSTEM API Guide:** https://wiki.steeldome.com/en/stratisystem-api-guide
- **Features and Specifications:** https://wiki.steeldome.com/en/features-and-specifications

## Product Overviews

- **Introduction to StratiSTOR:** https://wiki.steeldome.com/en/introduction-to-stratistor
- **Introduction to StratiSERV:** https://wiki.steeldome.com/en/introduction-to-stratiserv
- **Introduction to HyperSERV:** https://wiki.steeldome.com/en/introduction-to-hyperserv

## Use Cases

- **HPC and Supercomputing:** https://wiki.steeldome.com/en/use-case-hpc-sc
- **Artificial Intelligence:** https://wiki.steeldome.com/en/use-case-ai
- **Managed Service Providers:** https://wiki.steeldome.com/en/use-case-msp
- **Healthcare:** https://wiki.steeldome.com/en/use-case-healthcare
- **Scientific Research:** https://wiki.steeldome.com/en/use-case-research
- **Media and Entertainment:** https://wiki.steeldome.com/en/use-case-media
- **Legal:** https://wiki.steeldome.com/en/use-case-legal

---

# Who It’s For

StratiSYSTEM is designed for technical organizations that need infrastructure to remain flexible as workloads evolve.

Typical users include:

- Enterprise infrastructure teams
- Platform engineering teams
- Virtualization administrators
- Storage administrators
- Kubernetes teams
- Private cloud architects
- AI infrastructure teams
- HPC architects
- Research computing teams
- Media infrastructure teams
- Managed service providers
- Hosting providers
- Healthcare organizations
- Edge infrastructure operators
- Data-intensive application teams
- Organizations seeking alternatives to proprietary virtualization or infrastructure stacks

---

# Why StratiSYSTEM

Infrastructure requirements continue to change.

A system purchased today for virtualization may be expected to support containers tomorrow.

A storage system built for enterprise applications may later need to serve AI datasets.

An AI environment may need Lustre, S3, NFS, SMB, Kubernetes, virtualization, local NVMe, and large distributed storage at the same time.

Traditional infrastructure often addresses each requirement with another independent platform.

StratiSYSTEM takes a different approach.

It provides a common infrastructure operating system across:

**Storage.  
Virtualization.  
HCI.  
Containers.  
Kubernetes.  
Networking.  
AI.  
GPU infrastructure.  
HPC.  
Lustre.  
SMB.  
NFS.  
S3.  
Block storage.  
NVMe.  
Caching.  
Automation.  
Monitoring.  
High availability.**

The physical architecture can change.

The workload can change.

The hardware can change.

The operational foundation remains consistent.

---

# Support

For product documentation, deployment guidance, technical architecture information, and platform overviews, visit:

**https://wiki.steeldome.com/**

For videos, demonstrations, platform walkthroughs, and technical discussions:

**https://www.youtube.com/@SteelDomeTechnologies**

---

## **StratiSYSTEM™ OS**

### **One operating system. Infinite possibilities.**
