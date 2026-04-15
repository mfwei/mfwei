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

- Developed Btrfs-based applications (e.g., Snapshot Replication) used in enterprise NAS deployments
- Designed a petabyte-scale file system for high-density storage systems
- Built and maintained production storage systems with strong guarantees in reliability and scalability

---

## 🎯 Research Focus

- File systems & storage systems
- Operating systems
- Emerging storage technologies (ZNS SSD, SMR)
- Performance, reliability, and system design trade-offs
