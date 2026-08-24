# Awesome-Telecom-OSS

Markdown
Copy
# Top Telecom OSS Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Operations Support Systems — Inventory, Order Management, Fulfillment, Assurance, Orchestration, Service & Resource Management*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Telecom OSS** (Operations Support Systems). These systems manage the operational lifecycle of telecom networks and services — including inventory, order fulfillment, service orchestration, fault/performance management, and resource activation — often in multi-vendor, multi-technology environments.

**Examples** include Netcracker, Amdocs, Nokia FlowOne, Oracle Communications, Openet, Etiya, Hansen Technologies, Optiva, CSG, and Enghouse Networks (the category leaders).

**Open-source emphasis**: Full commercial-grade OSS suites are uncommon in pure open source, but strong building blocks exist. **ONAP**, **OpenNMS**, **NetBox**, and related projects form the core of many operator and private-network open stacks. This section is heavily expanded with practical open alternatives.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Netcracker](https://www.netcracker.com/)**  
  Comprehensive OSS/BSS platform widely used by large carriers for service orchestration, inventory, fulfillment, and digital transformation programs.

- **[Amdocs](https://www.amdocs.com/)**  
  Major OSS/BSS suite provider offering modular solutions for catalog, order management, inventory, fulfillment, and related operational processes.

- **[Nokia FlowOne / Nokia OSS](https://www.nokia.com/)**  
  Network-centric OSS and service orchestration capabilities from Nokia, supporting multi-domain automation and assurance.

- **[Oracle Communications](https://www.oracle.com/industries/communications/)**  
  Broad portfolio of OSS/BSS and network automation solutions used by communications service providers.

- **[Openet](https://www.openet.com/)**  
  Specialist in charging, policy, and related real-time OSS/BSS components, often deployed in digital and 5G environments.

- **[Etiya](https://www.etiya.com/)**  
  Customer and product-centric BSS/OSS platform with catalog, order, and experience management capabilities.

- **[Hansen Technologies](https://www.hansencx.com/)**  
  Billing, customer care, and operational systems serving utilities and communications providers.

- **[Optiva](https://www.optiva.com/)**  
  Cloud-native BSS platform focused on charging, billing, and monetization for digital telcos and MVNOs (with OSS-adjacent capabilities).

- **[CSG](https://www.csgi.com/)**  
  Long-standing provider of BSS and operational systems for communications service providers, with strong North American presence.

- **[Enghouse Networks](https://www.enghouse.com/)**  
  Network and service management solutions covering OSS functions for operators and service providers.

## Open-Source GitHub Projects
- **[ONAP (Open Network Automation Platform)](https://github.com/onap)**  
  The leading open-source platform for designing, orchestrating, and managing VNFs, SDNs, and higher-level services — a cornerstone of open telecom automation and OSS-style orchestration.

- **[OpenNMS](https://github.com/OpenNMS/opennms)**  
  Enterprise-grade open-source network management platform providing fault, performance, and traffic monitoring that serves as a foundational OSS assurance component.

- **[NetBox](https://github.com/netbox-community/netbox)**  
  Popular open-source source-of-truth for network inventory, IPAM, and DCIM — frequently used as the inventory foundation in modern OSS stacks.

- **[Boda Telecom Suite (BTS-CE)](https://github.com/bodastage/bts-ce)**  
  Open-source, vendor- and technology-agnostic telecommunication network management platform with topology, CM browsing, RAN audit, and reporting features.

- **[OSM (Open Source MANO)](https://osm.etsi.org/)**  
  ETSI-aligned open-source Management and Orchestration platform for NFV, widely used in operator and research environments.

- **[LibreNMS](https://github.com/librenms/librenms)**  
  Open-source network monitoring system providing discovery, performance data, and alerting that feeds OSS assurance processes.

- **[free5GC / Open5GS and related cores](https://github.com/)**  
  Open 5G/4G core network projects whose management and monitoring components integrate into broader OSS-style operational stacks.

- **[Nephio](https://github.com/nephio-project/nephio)**  
  Kubernetes-based automation project focused on intent-driven orchestration for cloud-native telecom infrastructure.

- **[Ostelco and cloud-native BSS/OSS experiments](https://github.com/ostelco/ostelco-core)**  
  Open projects exploring cloud-native OCS/BSS patterns that can complement OSS fulfillment and charging flows.

- **[Telecom inventory parsers and CM tools](https://github.com/)**  
  Community tools for ingesting vendor configuration data, building topology, and supporting configuration management use cases.

### Additional Strong Open-Source Options
- Prometheus + Grafana + Alertmanager for metrics and basic closed-loop signals.
- Apache Kafka / Flink pipelines for event-driven order and inventory flows.
- TM Forum Open API inspired open implementations and reference code.
- Ansible / Terraform / Crossplane for infrastructure and service activation.
- Custom service catalog and order management prototypes built on open workflow engines (Camunda, Temporal, etc.).

**Frameworks for building custom systems**: Combine **NetBox** (inventory) + **ONAP** or **OSM** (orchestration) + **OpenNMS**/LibreNMS (assurance) + open workflow and messaging layers. For private or smaller networks, lighter stacks using NetBox, Prometheus, and automation tools often suffice. These approaches give full control and avoid proprietary lock-in, but require significant integration effort and lack the pre-built multi-vendor adapters, carrier-grade support, and end-to-end process maturity of commercial OSS suites.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Telecom OSS systems sit at the heart of network and service operations. Open-source components offer transparency and flexibility but still demand careful architecture, testing, multi-vendor integration, and operational processes to meet carrier reliability and scale expectations.
- Always validate orchestration and activation logic thoroughly before impacting production networks.

---
**Made for network operators, OSS architects, and private-network teams seeking open operational foundations.**
Let's make telecom operations more modular, interoperable, and community-driven.
