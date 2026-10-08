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



The high-availability application recovery and failover market spans **hyperscaler-native failover services** (AWS Route 53 ARC, Azure Traffic Manager, Google Cloud Load Balancing) that provide **managed multi-region failover with health checks**, **specialized DNS and GSLB platforms** (Cloudflare, NS1, Akamai) that offer **global traffic management with anycast**, and **enterprise ADC platforms** (F5, Kemp, Avi) that provide **advanced health monitoring and failover orchestration**. **AWS Route 53 ARC** charges **$2.50/month per routing control** plus **health check costs** . **Cloudflare Load Balancing** starts at **$5/month per origin** . **Azure Traffic Manager** charges **$0.54/million DNS queries** . **NS1 GSLB** starts at **$113.85/month** .



| SaaS / Commercial Platform | Company / Owner | Valuation / Market Cap | Standard Edition Starting Price | Free Tier / Free Trial Limits | Description |

| :--- | :--- | :--- | :--- | :--- | :--- |

| **[AWS Route 53 ARC](https://aws.amazon.com/route53/arc/)** ☁️ | Amazon | ~$2.0 Trillion | **$2.50/month per routing control** + health checks  | **Free tier: limited** | **AWS-native failover orchestration** — **Routing controls** for DNS failover. **Readiness checks** for validating recovery readiness. **Safety rules** for preventing conflicting failover actions. **The most sophisticated managed failover service** . |

| **[Cloudflare Load Balancing](https://www.cloudflare.com/load-balancing/)** 🟠 | Cloudflare Inc. | ~$30 Billion | **$5/month per origin** (starting) | **Free tier: limited** | **Global server load balancing** — **Active-active and active-passive** configurations. **Health checks** with geographic failover. **Anycast-based** global traffic distribution. **Session affinity** and **geo-steering** . |

| **[Azure Traffic Manager](https://azure.microsoft.com/en-us/products/traffic-manager/)** 🔷 | Microsoft | ~$3.90 Trillion | **$0.54/million DNS queries**  | **Free tier: limited** | **Azure-native DNS failover** — **Priority, weighted, performance, and geographic** routing. **Endpoint health monitoring** . **Nested profiles** for complex failover hierarchies . |

| **[NS1 Global Server Load Balancing](https://ns1.com/)** 🟢 | IBM (NS1) | ~$200 Billion (IBM) | **$113.85/month** (Essentials)  | **Trial available** | **DNS-based failover** — **Advanced filter chains** for health checks and failover. **Pulsar for RUM-based steering** . **Dedicated DNS for custom nameservers** . |

| **[F5 BIG-IP DNS Cloud](https://www.f5.com/)** 🔵 | F5 Networks | ~$10 Billion | **Custom enterprise pricing**  | **Demo available** | **Enterprise GSLB** — **Global traffic management with health monitoring** . **Smart failover based on application health** . **Deep integration with F5 AWAF and APM** . |

| **[Akamai Global Traffic Management](https://www.akamai.com/)** 🔴 | Akamai Technologies | ~$15 Billion | **Custom enterprise pricing**  | **No free tier**; demo available | **Global traffic management** — **4,100+ edge locations** in **135+ countries** . **Health-based failover and load balancing** . **The most mature global failover network** . |

| **[Constellix Failover](https://constellix.com/)** 🟣 | Tiggee LLC | Private | **Usage-based pricing**  | **Free trial available** | **Advanced DNS traffic management** — **Real-time failover** with **GeoDNS, failover, and load balancing** . **Infrastructure monitoring** integrated . |

| **[Kemp LoadMaster Cloud](https://kemptechnologies.com/)** ⚙️ | Progress Software | ~$1.5 Billion | **Virtual: ~$13,450**; **Hardware: ~$27,480**  | **Free trial available** | **ADC with HA failover** — **L4/L7 load balancing with health checks** . **Active-passive and active-active HA** . **WAF and edge security** . |

| **[Avi Vantage (VMware NSX ALB)](https://avinetworks.com/)** 🟡 | Broadcom (VMware) | ~$60 Billion | **Custom enterprise pricing**  | **Demo available** | **Software-defined load balancing** — **Predictive autoscaling and health monitoring** . **Multi-cloud and on-premises** . **Active-active HA across regions** . |

| **[Radware Cloud Load Balancing](https://www.radware.com/)** 🟠 | Radware | ~$1 Billion | **Custom enterprise pricing**  | **Demo available** | **Cloud load balancing** — **Global server load balancing with health checks** . **DDoS mitigation and WAF** . |



---



## 🔓 Open-Source GitHub Projects



*Sorted by GitHub_Stars_Count (Descending)* 🌟



- **[Keepalived](https://github.com/acassen/keepalived)** [![Stars](https://img.shields.io/github/stars/acassen/keepalived?style=social&color=white)](https://github.com/acassen/keepalived/stargazers)  

  **VRRP and LVS health checking**, GPL-2.0 licensed. **The most widely deployed open-source HA solution** — **VRRP-based failover** for Linux servers . **LVS/IPVS health checking** for load balancer failover . **Virtual IP failover** with **sub-second detection** . **The definitive open-source high-availability platform** . 🛡️



- **[HAProxy](https://github.com/haproxy/haproxy)** [![Stars](https://img.shields.io/github/stars/haproxy/haproxy?style=social&color=white)](https://github.com/haproxy/haproxy/stargazers)  

  **The world's fastest and most widely used software load balancer**, GPL-2.0 licensed. **Active-passive and active-active HA** with **health checks** . **Connection draining and seamless failover** . **The foundation for high-availability load balancing** . 🏆



- **[BIRD](https://github.com/BIRD/bird)** [![Stars](https://img.shields.io/github/stars/BIRD/bird?style=social&color=white)](https://github.com/BIRD/bird/stargazers)  

  **The BIRD Internet Routing Daemon**, GPL-2.0 licensed. **The most widely used open-source BGP daemon** — **used for anycast failover** . **Supports BGP, OSPF, RIP, and Babel** . **The standard for anycast-based high availability** . 🐦



- **[FRRouting (FRR)](https://github.com/FRRouting/frr)** [![Stars](https://img.shields.io/github/stars/FRRouting/frr?style=social&color=white)](https://github.com/FRRouting/frr/stargazers)  

  **The most widely deployed open-source routing stack**, GPL-2.0 licensed. **The de facto standard for open-source BGP** — **used for anycast failover** . **Supports BGP, OSPF, IS-IS, RIP, EIGRP, and PIM** . 🛣️



- **[Pacemaker](https://github.com/ClusterLabs/pacemaker)** [![Stars](https://img.shields.io/github/stars/ClusterLabs/pacemaker?style=social&color=white)](https://github.com/ClusterLabs/pacemaker/stargazers)  

  **The most widely used open-source HA cluster resource manager**, GPL-2.0 licensed. **High-availability clustering with failover orchestration** . **Resource monitoring and recovery** . **The standard for Linux HA clustering** . 🏗️



- **[Corosync](https://github.com/corosync/corosync)** [![Stars](https://img.shields.io/github/stars/corosync/corosync?style=social&color=white)](https://github.com/corosync/corosync/stargazers)  

  **The cluster messaging layer for HA clusters**, BSD-2-Clause licensed. **Provides reliable messaging and membership** for Pacemaker . **The foundation for Linux HA clustering** . 🔗



- **[Patroni](https://github.com/zalando/patroni)** [![Stars](https://img.shields.io/github/stars/zalando/patroni?style=social&color=white)](https://github.com/zalando/patroni/stargazers)  

  **PostgreSQL HA template**, Apache-2.0 licensed. **The most widely used PostgreSQL HA solution** — **automatic failover and leader election** . **The foundation for CloudNativePG and StackGres** . 🐘



- **[kube-vip](https://github.com/kube-vip/kube-vip)** [![Stars](https://img.shields.io/github/stars/kube-vip/kube-vip?style=social&color=white)](https://github.com/kube-vip/kube-vip/stargazers)  

  **Virtual IP and load balancer for Kubernetes**, Apache-2.0 licensed. **Provides L2 and BGP-based VIP management** for control plane and services . **Anycast VIP for Kubernetes clusters** . ☸️



- **[MetalLB](https://github.com/metallb/metallb)** [![Stars](https://img.shields.io/github/stars/metallb/metallb?style=social&color=white)](https://github.com/metallb/metallb/stargazers)  

  **Load balancer for bare-metal Kubernetes**, Apache-2.0 licensed. **Provides L4 load balancing via ARP/NDP (L2) or BGP (BGP)** . **Failover for services of type LoadBalancer** . 🛠️



- **[kube-vip](https://github.com/kube-vip/kube-vip)** [![Stars](https://img.shields.io/github/stars/kube-vip/kube-vip?style=social&color=white)](https://github.com/kube-vip/kube-vip/stargazers)  

  **Virtual IP and load balancer for Kubernetes**, Apache-2.0 licensed. **Anycast VIP for control plane and services** . **The standard for Kubernetes HA** . ☸️



- **[Consul](https://github.com/hashicorp/consul)** [![Stars](https://img.shields.io/github/stars/hashicorp/consul?style=social&color=white)](https://github.com/hashicorp/consul/stargazers)  

  **Service discovery and mesh with health checking**, MPL-2.0 licensed. **Health checking for failover** . **Multi-runtime support** . **The standard for service-level failover** . 🔐



- **[etcd](https://github.com/etcd-io/etcd)** [![Stars](https://img.shields.io/github/stars/etcd-io/etcd?style=social&color=white)](https://github.com/etcd-io/etcd/stargazers)  

  **Distributed reliable key-value store**, Apache-2.0 licensed. **The foundational coordination service for Kubernetes** — **stores all cluster state** . **Raft consensus for high availability** . 🔑



---



## 🛠️ How to Contribute



Contributions are welcome! Follow these steps to submit new failover platforms or open-source HA software:



1. 🍴 **Fork** the repository.

2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.

3. 🔗 Include project title, official website/GitHub link, exact Stars_Count, license, and brief description.

4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.



---



## 📊 Star History



[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-High-Availability-Application-Recovery-Failover&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-High-Availability-Application-Recovery-Failover&type=date&legend=top-left)



---



## 🤝 Support & Sponsorship



If you find this high-availability application recovery repository useful, please consider supporting the project:



- ⭐ **Star** this repository to increase visibility!

- 🔀 **Fork** and share with fellow SREs, platform engineers, and open-source advocates.

- ☕ **Sponsor & Buy Me a Coffee**: Support ongoing open-source curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).



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
