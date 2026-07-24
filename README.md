# RISCBench: RISC-V Orchestration & Throughput Benchmarking

**RISCBench** is an open-source benchmarking framework and methodology focused on orchestration efficiency in RISC-V and heterogeneous compute systems. While conventional metrics (like FLOPs and TOPS/W) measure raw arithmetic capability, RISCBench evaluates the control plane—where synchronization, memory residency transitions, and orchestration determine sustained throughput.

Originally introduced at **RISC-V Summit North America 2025**, RISCBench was formally presented at the **[Proceedings of the 2026 ACM/SIGDA International Symposium on Field Programmable Gate Arrays (ISFPGA 2026)](https://dl.acm.org/doi/epdf/10.1145/3748173.3779569)**, introducing the **Sustained Instantaneous Throughput (SIT)** metric.

---

## 🚀 Key Features & Components
- **SIT Engine:** Core pipeline for computing the Sustained Instantaneous Throughput metric.
- **Trace & Classification:** Trace ingestion API, schema, and residency/throughput window classifiers.
- **Simulation Sensitivity Module:** Latency, bandwidth, and synchronization sweep tools.
- **Adapters & Suites:** Kernel suites and vendor/simulator adapters (Spike, QEMU, Renode, Olympia).

---

## 📄 Publications & Presentations
- **ISFPGA 2026:** *[RISCBench: Benchmarking RISC-V Orchestration Efficiency in FPGA and FPGA-Like Computing Engines](https://dl.acm.org/doi/epdf/10.1145/3748173.3779569)*
- **RISC-V Summit North America 2025:** Initial framework presentation.

---

## 🤝 Contributing
RISCBench is an evolving research framework. We welcome contributions from industry, academia, and government across chip architecture, EDA research, systems design, and heterogeneous computing. 


