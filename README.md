# Awesome-Quantum-Computing-Platform

## Top Quantum Computing Platforms Ecosystem
**Curated List of SaaS/Cloud Products & Open-Source GitHub Projects**
*Focused on Quantum Hardware Access, SDKs, Simulators, Hybrid Algorithms & Quantum Software Development*
**Last updated: September 2026**

This repository tracks notable **cloud/SaaS platforms** and **open-source projects** for **Quantum Computing**. These systems provide access to quantum processing units (QPUs), high-performance simulators, circuit development tools, hybrid classical-quantum workflows, and algorithm libraries across superconducting, trapped-ion, neutral-atom, annealing, and other modalities.

**Examples** include IBM Quantum, Azure Quantum, Amazon Braket, D-Wave Leap, Classiq, Quantum Inspire, Pasqal Cloud, IQM Resonance, Q-CTRL Fire Opal, and Rigetti QCS (the category leaders).

**Open-source emphasis**: Quantum computing has one of the strongest open-source ecosystems in emerging technology. **Qiskit**, **Cirq**, **PennyLane**, **Ocean SDK**, and related projects are the primary tools used by researchers and developers worldwide. This section is heavily expanded with these frameworks.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform | Description | Pricing | Free Tier Limits |
| :--- | :--- | :--- | :--- |
| **[IBM Quantum](https://www.ibm.com/quantum)** | Leading quantum cloud platform offering access to utility-scale superconducting processors and the Qiskit ecosystem. | Starts at $1.60/second ($96/minute) on Pay-As-You-Go Plan; Flex Plan starts at $72/minute (min 400 min/yr); Premium Plan starts at $48/minute (min 5,200 min/yr) | Open Plan: 10 minutes of quantum computer runtime per month forever; free access to simulators & learning resources |
| **[Azure Quantum](https://azure.microsoft.com/en-us/products/quantum)** | Microsoft's quantum cloud service providing multi-provider hardware access (IonQ, Quantinuum, Rigetti, Pasqal) and QDK integration. | Pay-as-you-go per provider: Rigetti from $0.02/10ms execution; IonQ from $0.00022/1q-gate-shot + $0.000975/2q-gate-shot ($12.42–$97.50 min/exec); Pasqal from €3,000/QPU-hr | $500 free Azure Quantum credit for each participating provider (valid across first-time workspace usage) + free full local/web simulators & Resource Estimator; Azure account free trial grants $200 credits for 30 days |
| **[Amazon Braket](https://aws.amazon.com/braket/)** | AWS quantum computing service with access to multi-provider QPUs (IonQ, IQM, QuEra, Rigetti) and managed Jupyter environments. | Pay-as-you-go: $0.30 per task + per-shot fees (Rigetti Cepheus: $0.000425/shot, IQM Garnet: $0.00145/shot, QuEra Aquila: $0.01/shot, IonQ Forte: $0.08/shot); SV1/DM1 simulators at $0.075/minute | AWS Free Tier: 1 hour (60 minutes) of on-demand simulation time (SV1, DM1, TN1) per month for the first 12 months; local SDK simulator is completely free forever |
| **[D-Wave Leap](https://www.dwavesys.com/learn/leap/)** | Cloud platform focused on quantum annealing and hybrid solvers for optimization problems with real-time hardware access. | Starts at $109/month for Developer Plan (includes 15 minutes of hybrid solver time or 10 seconds of QPU time per month); Enterprise subscriptions available | Free permanent Developer access with 1 minute (60 seconds) of QPU time or hybrid solver compute per month upon connecting a verified GitHub account (otherwise 1 month free trial with 1 minute of QPU time) |
| **[Classiq](https://www.classiq.io/)** | Quantum software platform emphasizing high-level algorithm design, automated circuit synthesis, and hardware-agnostic optimization. | Team / Enterprise tier starting from ~$1,500/month or custom annual contracts depending on synthesized circuit complexity and seats | Community Edition: Free forever with unlimited high-level model creation, circuit synthesis up to 50 qubits, and execution on cloud simulators |
| **[Quantum Inspire](https://www.quantum-inspire.com/)** | European quantum computing platform from QuTech offering access to spin-qubit and superconducting hardware alongside simulators. | Commercial / partner custom reservations start from €500–€2,500/hour for dedicated hardware access slots | Free forever account: access to hardware backends (Spin-2+, Starmon-5) with a maximum of 3 queued jobs at a time; unlimited access to QI cloud simulators (up to 31 qubits) |
| **[Pasqal Cloud](https://www.pasqal.com/)** | Neutral-atom quantum computing cloud platform for analog and digital quantum simulation and optimization workloads. | On-demand access starts at €3,000 per QPU-hour; €15 per emulator-hour (EMU-MPS / EMU-SV) via cloud integrations (Azure / Pasqal Cloud) | 30-day free sandbox access on Pasqal Cloud emulator with 20 free emulator-hours for testing neutral-atom Pulser programs |
| **[IQM Resonance](https://www.meetiqm.com/)** | Quantum cloud service from IQM delivering direct access to on-premise superconducting QPUs (Garnet, Emerald) and simulators. | Pay-per-second / reservation starting at ~€2,000–€3,000/hour (~$0.30/task + $0.00145/shot via public cloud marketplaces) | 14-day free trial on Resonance cloud simulator and demo QPUs with up to 1 hour of simulated runtime credit |
| **[Q-CTRL Fire Opal](https://q-ctrl.com/fire-opal)** | Quantum infrastructure software providing automated error suppression and performance enhancement across hardware backends. | Fire Opal Pro starting at $500/month; native pay-as-you-go add-on on IBM Quantum Platform starting at $1.60/runtime-minute | Free tier available forever: execute circuits up to 20 qubits with basic automated error suppression on public hardware backends |
| **[Rigetti QCS](https://www.rigetti.com/)** | Rigetti's Quantum Cloud Services platform providing low-latency access to superconducting quantum processors and Forest SDK. | Starts at $0.02 per 10-millisecond increment of job execution time (~$1.20/minute of pure QPU time); reservations from $4,100/hour | Free forever Quantum Virtual Machine (QVM) simulation via pyQuil and Forest SDK; initial free test credit granted for new QCS accounts (or through Azure $500 Rigetti credits) |

## Open-Source GitHub Projects
- **[Qiskit](https://github.com/Qiskit/qiskit)**  
  The most widely used open-source quantum SDK (IBM) for circuit design, simulation, optimization, and execution on IBM Quantum and other backends.

- **[Cirq](https://github.com/quantumlib/Cirq)**  
  Google’s open-source Python framework for creating, editing, and running NISQ circuits, with strong hardware-aware features and noise modeling.

- **[PennyLane](https://github.com/PennyLaneAI/pennylane)**  
  Open-source quantum software platform focused on quantum machine learning, differentiable programming, and quantum chemistry (Xanadu).

- **[Ocean SDK (D-Wave)](https://github.com/dwavesystems)**  
  Open-source tools for quantum annealing, hybrid solvers, and optimization on D-Wave systems.

- **[PyQuil / Forest SDK](https://github.com/rigetti)**  
  Rigetti’s open-source tools for programming and running quantum programs on their hardware and simulators.

- **[Q# and Quantum Development Kit components](https://github.com/microsoft/qsharp)**  
  Microsoft’s open-source quantum programming language and related libraries for algorithm development.

- **[CUDA-Q](https://github.com/NVIDIA/cuda-quantum)**  
  NVIDIA’s open-source platform for hybrid quantum-classical computing with strong GPU-accelerated simulation.

- **[TKET](https://github.com/CQCL/tket)**  
  Open-source quantum compiler and toolkit (Quantinuum/Cambridge Quantum) for circuit optimization and retargeting.

- **[ProjectQ, OpenQASM, and other circuit frameworks](https://github.com/)**  
  Additional open-source quantum programming and intermediate representation projects used in research and education.

- **[Quantum simulators (Qiskit Aer, qsim, Stim, etc.)](https://github.com/)**  
  High-performance open-source simulators for statevector, density matrix, stabilizer, and noisy circuit simulation.

### Additional Strong Open-Source Options
- Starting with **Qiskit** for the largest community, tutorials, and free IBM Quantum access.
- Choosing **Cirq** when working closely with Google hardware or needing fine-grained NISQ control.
- Using **PennyLane** for quantum machine learning and differentiable quantum circuits.
- Combining open SDKs with cloud backends (Braket, Azure Quantum, IBM) for hybrid development.
- Accepting that actual QPU time, enterprise support, error-mitigation services, and multi-provider orchestration still rely on commercial cloud platforms.

**Frameworks for building custom systems**: Develop circuits and algorithms with Qiskit, Cirq, or PennyLane → simulate locally or on GPU-accelerated open simulators → execute on cloud QPUs via IBM Quantum, Amazon Braket, Azure Quantum, or other providers → apply open error-mitigation and optimization techniques. This workflow is the standard open path for quantum research and early application development. Commercial platforms (IBM Quantum, Azure Quantum, Amazon Braket, D-Wave Leap, Classiq, etc.) provide the hardware access, managed environments, and advanced services that complement the open software stack.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Quantum computing is an emerging field. Hardware performance, qubit counts, error rates, and availability change rapidly. Open-source software and cloud platforms should be evaluated against current documentation and research needs. Access to real quantum hardware often involves usage limits, queues, or paid plans. This list is not scientific, investment, or technology-selection advice.

---
**Made for quantum researchers, developers, and organizations exploring practical quantum computing.**
Let's keep quantum software open, interoperable, and advancing together.
