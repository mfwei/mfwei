## 👋 About Me

**PhD Candidate in Computer Science @ National Taiwan University**

Building QoS-aware storage systems and file systems for emerging storage devices, with a focus on bridging research prototypes and production systems.

**Email:** d11922014 at ntu dot edu dot tw.

---

## 📚 Selected Publications

### Zone-aware metadata placement in B-tree filesystem
**Ming-Feng Wei**, Yun-Chih Chen, Yuan-Hao Chang, and Tei-Wei Kuo  
*[ASP-DAC 2026](https://www.aspdac.com/aspdac2026/)*

- Identified metadata-space-management interference in Btrfs on ZNS SSDs
- Proposed dynamic metadata placement and zone-aware reclamation strategies
- Achieved **22% average** and up to **65%** improvement in sustained-write throughput

📄 [Paper](https://ieeexplore.ieee.org/abstract/document/11420423/) | 📊 [Slides](https://www.aspdac.com/aspdac2026/archive/pdf/9A-5.pdf)

*(Extended journal version in progress; code will be released upon publication)*

### ARDA: I/O Scheduler for Heterogeneous Workloads Co-located on Ultra-low-latency SSDs
**Ming-Feng Wei**, Tzu-Chieh Huang, Chieh-Lin Tsai, Yun-Chih Chen, Tei-Wei Kuo, and Yuan-Hao Chang  
*[RTCSA 2026](https://rtcsa2026.github.io/)*

- Proposed ARDA, a QoS-aware I/O scheduler for ultra-low-latency SSDs
- Dynamically adapts request dispatching to balance latency targets and device utilization
- Reduced average latency by **23–43%** and tail latency by **36–45%** over Kyber under mixed workloads

*(Paper and artifacts will be released after publication)*

---

## 🏢 Industry Experience

**Synology (2016–2022), Filesystem R&D**

- Developed and extended Btrfs with production features (e.g., Snapshot Replication), improving data protection and reliability in enterprise NAS systems
- Contributed to a petabyte-scale Btrfs-based storage system:
  defined system specifications, coordinated 15+ R&D teams, and designed validation strategies for extreme workloads
- Served as the primary RD interface for multiple technical support teams, driving cross-layer debugging (filesystem, storage, block layer) and resolving 78% of filesystem-related production issues in 2021

---

## 🎯 Research Focus

- Metadata management in file systems
- File systems & storage systems
- Emerging storage technologies
- Performance interference and space efficiency

---
