# Awesome-High-Availability-Application-Recovery-Failover

# Awesome-High-Availability-Application-Recovery-Failover 🛡️ 🔄



<p align="center">

  <img src="assets/banner.svg" alt="Awesome High Availability Application Recovery Failover Banner" width="100%">

</p>



<p align="center">

  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>

  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>

  <a href="https://github.com/ishandutta2007/Awesome-High-Availability-Application-Recovery-Failover"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-High-Availability-Application-Recovery-Failover?style=social" alt="GitHub_Stars"/></a>

  <a href="https://github.com/ishandutta2007/Awesome-High-Availability-Application-Recovery-Failover/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-High-Availability-Application-Recovery-Failover?style=social" alt="GitHub Forks"/></a>

  <a href="https://github.com/ishandutta2007/Awesome-High-Availability-Application-Recovery-Failover/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-High-Availability-Application-Recovery-Failover?color=blue" alt="License"/></a>

  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>

</p>



---



## 🌟 Top High-Availability Application Recovery & Failover Ecosystem



**Curated List of Commercial Failover Platforms & Open-Source HA Frameworks**  

*Focused on Global Server Load Balancing, DNS Failover, Multi-Region Recovery, Health Checking, Anycast Routing & Self-Hosted High-Availability*



**Last updated: October 2026** 📅



---



### 📌 Overview & SEO Summary

Welcome to the ultimate curated directory of **high-availability application recovery and failover platforms**, **open-source HA frameworks**, and **global server load balancing tools**. Whether you are looking for enterprise-grade commercial solutions (such as *AWS Route 53 ARC*, *Cloudflare Load Balancing*, and *Azure Traffic Manager*), or self-hostable open-source alternatives (like *Keepalived*, *HAProxy*, and *BIRD*), this list covers category leaders, DNS failover, and privacy-respecting high-availability infrastructure.



**Key Market Context:**

- **AWS Route 53 Application Recovery Controller (ARC)** provides **routing controls, readiness checks, and safety rules** for **multi-region failover orchestration** — the most sophisticated managed failover service available.

- **Keepalived** is the **most widely deployed open-source HA solution**, with **VRRP-based failover** for Linux servers and **LVS/IPVS health checking**.

- **Cloudflare Load Balancing** provides **global anycast failover** with **active-active and active-passive** configurations, **health checks**, and **geo-steering**.



---



## 📑 Table of Contents

- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)

- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)

- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)

- [📊 Star History](#-star-history)

- [🤝 Support & Sponsorship](#-support--sponsorship)

- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)



---



## 🏢 SaaS / Commercial Platforms

> [!NOTE]
> **Market Size & Structure:** The global High-Availability (HA), Global Server Load Balancing (GSLB), and Disaster Recovery Orchestration market is estimated at **~$15.8 Billion (2026)** and is projected to reach **~$34.2 Billion by 2030** (CAGR ~16.7%). The market is **moderately fragmented**, led by hyperscalers (AWS, Microsoft Azure, Google Cloud) and specialized edge/CDN networks (Cloudflare, Akamai, IBM/NS1), alongside enterprise Application Delivery Controller (ADC) leaders (Broadcom/VMware, F5 Networks).

| SaaS / Commercial Platform | Company / Owner | Valuation / Market Cap | Standard Edition Starting Price | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Azure Traffic Manager](https://azure.microsoft.com/en-us/products/traffic-manager/)** 🔷 | Microsoft | **~$3.90 Trillion** | **$0.54 per million DNS queries** (+ $0.75/month per endpoint health check) | **AWS/Azure Free Account**: $200 credit for 30 days + 1 Million free DNS queries/month for 12 months | **Azure-native DNS failover** — Priority, weighted, performance, and geographic routing with automated endpoint health monitoring. |
| **[AWS Route 53 ARC](https://aws.amazon.com/route53/arc/)** ☁️ | Amazon | **~$2.0 Trillion** | **$2.50/month per routing control** (+ $0.50/month per health check) | **AWS Free Tier**: 50 VPS Hosted Zones + 10,000 DNS queries free for 12 months (ARC controls billed at usage) | **AWS-native failover orchestration** — Multi-region routing controls, readiness checks, and safety rules for zero-downtime recovery. |
| **[Avi Vantage (VMware NSX ALB)](https://avinetworks.com/)** 🟡 | Broadcom (VMware) | **~$60 Billion** | **$1,500/year per Service Engine instance** (subscription tier) | **30-day free trial** with full enterprise license evaluation | **Software-defined load balancing** — Predictive autoscaling, health monitoring, and active-active HA across hybrid multi-cloud environments. |
| **[Cloudflare Load Balancing](https://www.cloudflare.com/load-balancing/)** 🟠 | Cloudflare Inc. | **~$30 Billion** | **$5.00/month** (includes 2 origin servers & 60-sec health checks) | **Free Forever Plan**: Includes basic CDN/DNS; Load Balancing available as $5/mo add-on with 30-day money-back guarantee | **Global server load balancing (GSLB)** — Active-active & active-passive Anycast routing, health checks, session affinity, and geo-steering. |
| **[NS1 Global Server Load Balancing](https://ns1.com/)** 🟢 | IBM (NS1) | **~$200 Billion** | **$113.85/month** (NS1 Essentials DNS & GSLB package) | **30-day free developer trial** (up to 500k queries & 10 health monitor feeds) | **DNS-based dynamic failover** — Advanced filter chains, Pulsar RUM-based traffic steering, and high-frequency health monitors. |
| **[Akamai Global Traffic Management](https://www.akamai.com/)** 🔴 | Akamai Technologies | **~$15 Billion** | **$2,500/month** (GTM Enterprise Minimum Commit) | **30-day free trial** for Akamai Connected Cloud services | **Global traffic management** — Anycast routing across 4,100+ edge locations in 135+ countries with sub-second failover. |
| **[F5 BIG-IP DNS Cloud](https://www.f5.com/)** 🔵 | F5 Networks | **~$10 Billion** | **$1,245/month** (BIG-IP VE DNS Edition 1Gbps Subscription) | **30-day free trial** (F5 BIG-IP Virtual Edition free evaluation license) | **Enterprise GSLB & ADC** — Global traffic management with deep L4-L7 application health checks and AWAF integration. |
| **[Kemp LoadMaster Cloud](https://kemptechnologies.com/)** ⚙️ | Progress Software | **~$1.5 Billion** | **$1,995/year** (Virtual LoadMaster VLM-5000 License) | **Free LoadMaster Edition**: Free forever with 20 Mbps bandwidth limit & basic HA failover | **ADC with HA failover** — L4/L7 load balancing, active-passive & active-active HA clustering, and integrated WAF. |
| **[Radware Cloud Load Balancing](https://www.radware.com/)** 🟠 | Radware | **~$1 Billion** | **$850/month** (Cloud ADC & GSLB Starter Pack) | **30-day free trial** with demo environment access | **Cloud load balancing** — Global server load balancing with automated health failover, DDoS protection, and WAF integration. |
| **[Constellix Failover](https://constellix.com/)** 🟣 | Tiggee LLC | **Private ($50M+ est.)** | **$10.00/month** (Base plan + $0.60 per million DNS queries) | **30-day free trial** (Includes 1 Million queries & 10 check endpoints) | **Advanced DNS traffic management** — Real-time Sonar infrastructure monitoring with automated GeoDNS and failover routing. |

---

## 🔓 Open-Source GitHub Projects

*Sorted by GitHub_Stars_Count (Descending)* 🌟

- **[Caddy](https://github.com/caddyserver/caddy)** [![Stars](https://img.shields.io/github/stars/caddyserver/caddy?style=social&color=white)](https://github.com/caddyserver/caddy/stargazers)  
  **Fast, multi-platform web server with automatic HTTPS and active health checks**, Apache-2.0 licensed. **Active and passive upstream health monitoring** with automatic failover and load balancing. ⚡

- **[Traefik](https://github.com/traefik/traefik)** [![Stars](https://img.shields.io/github/stars/traefik/traefik?style=social&color=white)](https://github.com/traefik/traefik/stargazers)  
  **The Cloud Native Application Proxy**, MIT licensed. **Automated service discovery, circuit breaking, and load balancing failover** for microservices and Kubernetes. 🚦

- **[etcd](https://github.com/etcd-io/etcd)** [![Stars](https://img.shields.io/github/stars/etcd-io/etcd?style=social&color=white)](https://github.com/etcd-io/etcd/stargazers)  
  **Distributed reliable key-value store**, Apache-2.0 licensed. **The foundational coordination service for Kubernetes** — stores all cluster state with **Raft consensus algorithm for high-availability leader election**. 🔑

- **[Nginx](https://github.com/nginx/nginx)** [![Stars](https://img.shields.io/github/stars/nginx/nginx?style=social&color=white)](https://github.com/nginx/nginx/stargazers)  
  **High-performance HTTP server and reverse proxy**, BSD-2-Clause licensed. **Upstream server health checks, backup server directives, and passive failover**. 🌐

- **[Consul](https://github.com/hashicorp/consul)** [![Stars](https://img.shields.io/github/stars/hashicorp/consul?style=social&color=white)](https://github.com/hashicorp/consul/stargazers)  
  **Service discovery and service mesh with active health checking**, BUSL-1.1 licensed. **Dynamic service discovery and automatic health check failover** across multi-datacenter environments. 🔐

- **[Envoy](https://github.com/envoyproxy/envoy)** [![Stars](https://img.shields.io/github/stars/envoyproxy/envoy?style=social&color=white)](https://github.com/envoyproxy/envoy/stargazers)  
  **Cloud-native high-performance edge/service proxy**, Apache-2.0 licensed. **Advanced health checking, outlier detection, zone-aware routing, and panic thresholds** for resilient HA service communication. 🚀

- **[CoreDNS](https://github.com/coredns/coredns)** [![Stars](https://img.shields.io/github/stars/coredns/coredns?style=social&color=white)](https://github.com/coredns/coredns/stargazers)  
  **Flexible, extensible DNS server written in Go**, Apache-2.0 licensed. **Kubernetes default DNS with plugin-based health check failover and multi-backend redundancy**. 🔌

- **[Patroni](https://github.com/zalando/patroni)** [![Stars](https://img.shields.io/github/stars/zalando/patroni?style=social&color=white)](https://github.com/zalando/patroni/stargazers)  
  **PostgreSQL HA template with DCS sync**, MIT licensed. **The industry standard for PostgreSQL high availability** — automated failover, leader election, and DCS integration (etcd, Consul). 🐘

- **[MetalLB](https://github.com/metallb/metallb)** [![Stars](https://img.shields.io/github/stars/metallb/metallb?style=social&color=white)](https://github.com/metallb/metallb/stargazers)  
  **Bare-metal load balancer implementation for Kubernetes**, Apache-2.0 licensed. **L2 (ARP/NDP) and BGP-based load balancing with automatic failover** for bare-metal Kubernetes clusters. 🛠️

- **[HAProxy](https://github.com/haproxy/haproxy)** [![Stars](https://img.shields.io/github/stars/haproxy/haproxy?style=social&color=white)](https://github.com/haproxy/haproxy/stargazers)  
  **The world's fastest open-source software load balancer**, GPL-2.0 licensed. **Active-passive and active-active HA with health checking**, seamless connection draining, and sub-second failover. 🏆

- **[Orchestrator](https://github.com/github/orchestrator)** [![Stars](https://img.shields.io/github/stars/github/orchestrator?style=social&color=white)](https://github.com/github/orchestrator/stargazers)  
  **MySQL high-availability and replication management tool**, Apache-2.0 licensed. **Refactor and failover MySQL topology discovery, health analysis, and automated master recovery**. 🐬

- **[Keepalived](https://github.com/acassen/keepalived)** [![Stars](https://img.shields.io/github/stars/acassen/keepalived?style=social&color=white)](https://github.com/acassen/keepalived/stargazers)  
  **VRRP and LVS health checking daemon**, GPL-2.0 licensed. **The definitive open-source virtual IP failover engine** — sub-second heartbeat detection and LVS/IPVS load balance health monitoring. 🛡️

- **[FRRouting (FRR)](https://github.com/FRRouting/frr)** [![Stars](https://img.shields.io/github/stars/FRRouting/frr?style=social&color=white)](https://github.com/FRRouting/frr/stargazers)  
  **IP routing protocol suite for Linux and Unix platforms**, GPL-2.0 licensed. **De facto standard open-source BGP/OSPF stack used for Anycast VIP failover** and high-availability network routing. 🛣️

- **[kube-vip](https://github.com/kube-vip/kube-vip)** [![Stars](https://img.shields.io/github/stars/kube-vip/kube-vip?style=social&color=white)](https://github.com/kube-vip/kube-vip/stargazers)  
  **Kubernetes Virtual IP and Load Balancer**, Apache-2.0 licensed. **Provides control plane and service High Availability using ARP (L2) or BGP Anycast**. ☸️

- **[Corosync](https://github.com/corosync/corosync)** [![Stars](https://img.shields.io/github/stars/corosync/corosync?style=social&color=white)](https://github.com/corosync/corosync/stargazers)  
  **Cluster Engine for high-availability cluster messaging**, BSD-3-Clause licensed. **Reliable group communication and membership management** powering Linux HA cluster stacks. 🔗

- **[Pacemaker](https://github.com/ClusterLabs/pacemaker)** [![Stars](https://img.shields.io/github/stars/ClusterLabs/pacemaker?style=social&color=white)](https://github.com/ClusterLabs/pacemaker/stargazers)  
  **Scalable High-Availability cluster resource manager**, GPL-2.0 licensed. **Orchestrates recovery and failover of cluster services** across multi-node Linux infrastructure. 🏗️

- **[BIRD](https://github.com/CZ-NIC/bird)** [![Stars](https://img.shields.io/github/stars/CZ-NIC/bird?style=social&color=white)](https://github.com/CZ-NIC/bird/stargazers)  
  **The BIRD Internet Routing Daemon**, GPL-2.0 licensed. **Lightweight, high-performance BGP daemon frequently deployed for Anycast IP failover** and dynamic route propagation. 🐦



---



## 🛠️ How to Contribute



Contributions are welcome! Follow these steps to submit new failover platforms or open-source HA software:



1. 🍴 **Fork** the repository.

2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.

3. 🔗 Include project title, official website/GitHub link, exact Stars_Count, license, and brief description.

4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.



---



## 🤝 Support & Sponsorship 💖

Thank you for exploring and using this High-Availability Application Recovery & Failover directory! If this repository has helped you in your SRE, DevOps, or system design work, please consider supporting the project:

- ⭐ **Star** this repository to increase visibility and help others discover it! 🌟
- 🔀 **Fork** and share with fellow engineers, platform teams, and high-availability advocates! 🚀
- ☕ **Buy Me a Coffee / Sponsor**: Support ongoing maintenance and curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007). 💖

---

## 📊 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-High-Availability-Application-Recovery-Failover&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-High-Availability-Application-Recovery-Failover&type=date&legend=top-left)



---



## ⚠️ Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement. ℹ️

- **AWS Route 53 ARC is the most sophisticated managed failover service** — **$2.50/month per routing control** plus health checks . **Cloudflare Load Balancing starts at $5/month per origin** . **Azure Traffic Manager charges $0.54/million DNS queries** .

- **Keepalived is the most widely deployed open-source HA solution** — **VRRP-based failover** with **sub-second detection** . **Pacemaker and Corosync** provide **full HA cluster orchestration** .

- **Open-source HA tools are not turnkey** — they require **deployment, network configuration, and ongoing maintenance** . **Keepalived requires VRRP configuration** . **Pacemaker requires cluster resource agents** . **Always validate failover timing and recovery procedures with a proof-of-concept** before production deployment . 🛡️



---



<p align="center">

  <b>Made with ❤️ for SREs, platform engineers, and open-source high-availability advocates.</b>

</p>
