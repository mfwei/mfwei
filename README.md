## 👋 About Me

I build file systems and operating systems for emerging storage devices (e.g., zoned namespace SSDs), with a focus on bridging research and production systems.

My research is driven by production issues observed in large-scale Btrfs deployments, particularly how metadata and space management interact with performance isolation, space efficiency, and emerging storage devices. I translate these system-level insights into practical storage-system designs.

---

## 📚 Selected Publications

### ARDA: I/O Scheduler for Heterogeneous Workloads Co-located on Ultra-low-latency SSDs
**Ming-Feng Wei**, Tzu-Chieh Huang, Chieh-Lin Tsai, Yun-Chih Chen, Tei-Wei Kuo, and Yuan-Hao Chang  
*RTCSA 2026*

- Designed an I/O scheduler for heterogeneous workloads on ultra-low-latency SSDs
- Improved workload isolation and reduced interference under co-located storage workloads

*(Paper and artifacts will be released after publication)*

---

### Zone-aware metadata placement in B-tree filesystem
**Ming-Feng Wei**, Yun-Chih Chen, Yuan-Hao Chang, and Tei-Wei Kuo  
*ASP-DAC 2026*

- Identified metadata-space-management interference in Btrfs on ZNS SSDs
- Proposed dynamic metadata placement and zone-aware reclamation strategies
- Achieved **22% average** and up to **65%** improvement in sustained-write throughput

📄 [Paper](https://ieeexplore.ieee.org/abstract/document/11420423/)  
📊 [Slides](https://www.aspdac.com/aspdac2026/archive/pdf/9A-5.pdf)

*(Extended journal version in progress; code will be released upon publication)*

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
