## 👋 About Me

I build file systems and operating systems for emerging storage devices (e.g., zoned namespace SSDs), with a focus on bridging research and production systems.

Ph.D. candidate in Computer Science at National Taiwan University.  
My recent work on optimizing Btrfs for ZNS SSDs was accepted at ASP-DAC 2026.

---

## 🚀 Selected Work

### Btrfs Optimization for ZNS SSD

- Discovered that Btrfs exacerbates performance interference in ZNS SSDs due to proactive zone reclamation
- Proposed a new space management design to mitigate interference:
  - Metadata marking for near-term deletion prediction  
  - Urgency-aware reclamation policy  
  - Dynamic metadata placement
- Achieved **22% average** and up to **65%** improvement in sustained-write performance
- Published at ASP-DAC 2026  

📄 [Zone-aware metadata placement in B-tree filesystem](https://ieeexplore.ieee.org/abstract/document/11420423/)

---

## 🏢 Industry Experience

**Synology (2016–2022), Filesystem R&D**

- Developed and extended Btrfs with production features (e.g., Snapshot Replication), improving data protection and reliability in enterprise NAS systems

- Contributed to the design and development of a petabyte-scale Btrfs-based storage system for high-density deployments:
  - Defined system specifications and coordinated development across 15+ R&D teams
  - Designed system-level validation strategies to identify bottlenecks under extreme workloads (e.g., memory pressure, long-running I/O)
  - Ensured performance, scalability, and consistency across the storage stack

- Acted as the primary engineering interface between technical support and R&D teams to diagnose and resolve complex production issues
  - Debugged issues across filesystem, storage, and block layers in production environments
  - Resolved 78% of filesystem-related cases in 2021, improving system reliability and issue turnaround

---

## 🎯 Research Focus

- File systems & storage systems
- Operating systems
- Emerging storage technologies (ZNS SSD, SMR)
- Performance, reliability, and system design trade-offs
