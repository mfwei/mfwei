## 👋 About Me

I build file systems and operating systems for emerging storage devices (e.g., zoned namespace SSDs), with a focus on bridging research and production systems.

My work is motivated by real-world challenges observed in production Btrfs systems, where background space management can introduce significant performance interference. Through these experiences, I became particularly interested in how metadata management shapes system behavior, often acting as a hidden source of performance degradation and space inefficiency.

I translate these system-level insights into research problems and design practical solutions to improve performance and space efficiency in modern storage systems.

Ph.D. candidate in Computer Science at National Taiwan University.  
My recent work on optimizing Btrfs for ZNS SSDs was accepted at ASP-DAC 2026.

---

## 🚀 Selected Work

### Btrfs Optimization for ZNS SSD  
*Zone-aware metadata placement in B-tree filesystem*

- Motivated by production observations on metadata and space management in Btrfs, discovered that proactive zone reclamation exacerbates performance interference in ZNS SSDs
- Proposed a space management design with:
  metadata marking, space reclamation metric, and dynamic metadata placement
- Achieved **22% average** and up to **65%** improvement in sustained-write performance
- Published at [ASP-DAC 2026](https://www.aspdac.com/aspdac2026/)

📄 [Paper](https://ieeexplore.ieee.org/abstract/document/11420423/) | 📊 [Slides](https://www.aspdac.com/aspdac2026/archive/pdf/9A-5.pdf)

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
- Emerging storage technologies (ZNS SSD, SMR)
- Performance interference and space efficiency
