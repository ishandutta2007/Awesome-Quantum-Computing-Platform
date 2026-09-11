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
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[IBM Quantum](https://www.ibm.com/quantum)**  
  Leading quantum cloud platform offering access to superconducting processors, extensive free tier, and the Qiskit ecosystem for circuit development and execution.

- **[Azure Quantum](https://azure.microsoft.com/en-us/products/quantum)**  
  Microsoft’s quantum cloud service providing multi-provider hardware access, Q# and QDK tools, and enterprise integration.

- **[Amazon Braket](https://aws.amazon.com/braket/)**  
  AWS quantum computing service with access to multiple hardware providers (superconducting, trapped-ion, neutral-atom, annealing) and managed Jupyter environments.

- **[D-Wave Leap](https://www.dwavesys.com/learn/leap/)**  
  Cloud platform focused on quantum annealing and hybrid solvers for optimization problems, with real-time access to D-Wave systems.

- **[Classiq](https://www.classiq.io/)**  
  Quantum software platform emphasizing high-level algorithm design, circuit synthesis, and hardware-agnostic development.

- **[Quantum Inspire](https://www.quantum-inspire.com/)**  
  European quantum computing platform offering access to spin-qubit and other hardware along with educational and research tools.

- **[Pasqal Cloud](https://www.pasqal.com/)**  
  Neutral-atom quantum computing cloud platform for analog and digital quantum workloads.

- **[IQM Resonance](https://www.meetiqm.com/)**  
  Quantum cloud access platform from IQM focused on superconducting quantum computers and research/enterprise use cases.

- **[Q-CTRL Fire Opal](https://q-ctrl.com/fire-opal)**  
  Quantum infrastructure software that improves performance and error suppression on existing quantum hardware backends.

- **[Rigetti QCS](https://www.rigetti.com/)**  
  Rigetti’s Quantum Cloud Services platform providing access to their superconducting quantum processors and Forest SDK tools.

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
