# 🐱⚡ KITTY × TWEAK LABS

> **Independent research in artificial intelligence, language models, operating systems, distributed computing, cybersecurity, agents, infrastructure, and experimental software engineering.**

**KITTY × TWEAK LABS** is a collaborative research and engineering initiative created by **Kitty × Tweak**.

The goal is simple:

> **Build systems from first principles, measure them properly, understand why they work, improve them, and document everything we learn.**

This repository acts as the central research hub for our shared experiments, technical plans, architecture proposals, benchmarks, infrastructure designs, and future collaborative projects.

---

## 🧠 What is KITTY × TWEAK LABS?

KITTY × TWEAK LABS combines two independent technical ecosystems into one shared research environment.

### 💜 Kitty

Research and development areas include:

- **KittyLM**
- artificial intelligence and machine learning
- language-model architecture
- Python development
- cybersecurity
- Linux and Debian infrastructure
- home-lab engineering
- Docker and container systems
- observability
- AI agents
- automation
- distributed systems
- networking
- developer tooling
- model training and evaluation

### ❤️ Tweak

Research and development areas include:

- **TweakTron**
- experimental language-model architectures
- GDN / GDN2 research
- FlashQLA
- Mixture-of-Memory
- tokenizer development
- dense and sparse model research
- inference optimisation
- model architecture conversion
- low-level ML experimentation
- Linux and systems development

Together, these projects become the foundation of a larger shared research ecosystem.

---

# 🔬 Research Areas

KITTY × TWEAK LABS currently focuses on:

### Artificial Intelligence

- language-model architecture
- decoder-only Transformers
- recurrent architectures
- GDN / GDN2
- sparse computation
- Mixture-of-Experts
- Mixture-of-Memory
- long-context models
- adaptive computation
- model compression
- inference optimisation
- reasoning systems

### Tokenizers & Data

- BPE tokenizers
- vocabulary-size experiments
- code tokenization
- multilingual tokenization
- dataset collection
- dataset filtering
- deduplication
- provenance
- dataset versioning
- contamination analysis

### AI Agents

- autonomous agents
- tool calling
- MCP
- agent memory
- planning
- permission systems
- sandboxing
- agent evaluation
- multi-agent systems

### Systems Engineering

- Linux
- Debian
- operating-system research
- Docker
- Kubernetes
- distributed systems
- networking
- storage
- monitoring
- observability
- CI/CD

### Cybersecurity

- defensive cybersecurity
- secure software design
- Linux hardening
- container security
- dependency security
- supply-chain security
- agent security
- MCP security
- incident-response labs
- security automation

---

# 🧬 Core Projects

## KittyLM

Kitty's independent language-model research platform.

KittyLM is used to explore:

- model architecture
- training pipelines
- tokenizers
- datasets
- evaluation
- reasoning
- inference
- future sparse and recurrent architectures

---

## TweakTron

Tweak's experimental language-model platform.

Research includes:

- custom architecture work
- GDN / GDN2
- FlashQLA
- Mixture-of-Memory
- custom tokenizers
- dense and sparse architectures
- model conversion
- inference experiments

---

## KittyTron

**Proposed shared experimental model.**

KittyTron will eventually combine successful discoveries from both KittyLM and TweakTron.

It is intended to become a true research synthesis project rather than simply merging existing checkpoints.

---

## DualForge

Shared training and experimentation framework.

Planned capabilities:

- training configuration
- experiment execution
- checkpoint management
- benchmarking
- evaluation
- profiling
- model comparison
- hyperparameter experiments

---

## DataForge

Shared dataset research and processing platform.

Planned features:

- ingestion
- normalization
- licensing records
- provenance
- filtering
- deduplication
- dataset manifests
- hashing
- version control

---

## ReasonKit

Model reasoning and evaluation framework.

Evaluation areas include:

- coding
- logic
- mathematics
- structured output
- cybersecurity
- system administration
- tool use
- long-context retrieval

---

## CrossSilicon

Hardware and ML backend research.

Primary comparison:

```text
AMD / ROCm
    vs
NVIDIA / CUDA
```

Research includes:

- inference performance
- training throughput
- VRAM usage
- power efficiency
- framework compatibility
- kernel behaviour
- hardware portability

---

## AgentVerse

Experimental AI-agent runtime.

Planned components:

- tool permissions
- task execution
- agent memory
- MCP
- event logging
- sandboxing
- multi-agent orchestration
- agent benchmarking

---

## KERNEL//KITTY

Infrastructure and observability platform for Kitty's home lab.

Areas monitored include:

- servers
- containers
- storage
- networking
- security
- AI workloads
- experiments
- GPU telemetry
- services
- backups

---

# 🖥️ Research Infrastructure

KITTY × TWEAK LABS is being built around accessible local hardware rather than depending entirely on cloud infrastructure.

Current research environments include:

### Kitty Compute Environment

- AMD Ryzen workstation
- AMD Radeon GPU
- ROCm experimentation
- Windows development environment
- Linux virtualisation
- Docker
- local AI workloads
- cybersecurity labs

### Tweak Compute Environment

- AMD Ryzen platform
- NVIDIA RTX laptop GPU
- CUDA experimentation
- Debian/Linux development environment
- local AI research

### KERNEL//KITTY Server

Debian-based infrastructure supporting:

- containers
- reverse proxy
- monitoring
- databases
- storage
- dashboards
- automation
- Git services
- agent services
- research infrastructure

---

# 🌐 Future Compute Fabric

Long-term, the lab is intended to evolve into a heterogeneous distributed research environment.

```text
                  KITTY × TWEAK LABS

                         │
                 Research Control Plane
                         │
        ┌────────────────┼────────────────┐
        │                │                │
        ▼                ▼                ▼

 Kitty Workstation   Tweak Compute    GPU Nodes
 AMD / ROCm          NVIDIA / CUDA     Future GPUs

        │                │                │
        └────────────────┼────────────────┘
                         │
                  Shared Infrastructure
                         │
              ┌──────────┼──────────┐
              │          │          │
              ▼          ▼          ▼

             NAS      Kubernetes   Edge Nodes
                                   Raspberry Pi
```

---

# 📚 Research Documentation

KITTY × TWEAK LABS uses structured research documents.

Planned document types:

```text
KTL-RFC     Research proposals
KTL-ADR     Architecture decisions
KTL-EXP     Experiments
KTL-BENCH   Benchmarks
KTL-REPORT  Engineering reports
KTL-PAPER   Formal research papers
```

Example:

```text
KTL-EXP-0001
Tokenizer Vocabulary Scaling

KTL-BENCH-0001
ROCm vs CUDA Inference Performance

KTL-RFC-0001
KittyTron Architecture Proposal
```

---

# 🧪 Research Methodology

Experiments should aim to be reproducible.

A complete experiment should include:

```text
Code
+
Configuration
+
Dataset
+
Tokenizer
+
Random Seed
+
Hardware
+
Software Environment
+
Checkpoint
+
Evaluation
=
Reproducible Experiment
```

Whenever possible we record:

- Git commit
- configuration
- model parameters
- dataset version
- tokenizer version
- hardware
- software versions
- training settings
- benchmark results
- logs
- conclusions
- known limitations

---

# 🧾 Evidence Standard

We distinguish clearly between:

- **VERIFIED** — directly tested or evidenced
- **REPORTED** — reported by a project member
- **INFERRED** — strongly supported but not directly verified
- **PROPOSED** — planned or suggested
- **UNKNOWN** — insufficient evidence

Research conclusions should be supported by measurements rather than assumptions.

---

# 🛠️ Development Philosophy

KITTY × TWEAK LABS follows several principles.

### Build before scale

Small experiments that answer meaningful questions come before unnecessarily large models.

### Measure before claiming

Benchmarks and evidence matter more than impressive-looking numbers.

### Understand before abstracting

Whenever practical, we aim to understand the underlying system rather than treating frameworks as magic.

### Reproduce before optimise

Experiments should be repeatable before attempting increasingly complex optimisation.

### Hardware follows research

We do not buy hardware simply to increase specifications.

Every major hardware purchase should answer:

> **What new experiment does this make possible?**

---

# 🚀 Planned Research Projects

Some future collaborative projects include:

- **KittyTron**
- **DualForge**
- **DataForge**
- **ReasonKit**
- **CrossSilicon**
- **AgentVerse**
- **TinyKitty / TinyTron**
- **KittyCoder**
- **KittyCyberLM**
- **MCP Security Lab**
- **PageMind**
- **Synthetic Factory**
- **ApexSim**
- **KTL Observatory**
- **HomeScale**
- **KTL Bench**
- **KTL Compute Fabric**

---

# 🗺️ Current Research Roadmap

## Phase 1 — Foundations

- shared repository structure
- research-document standards
- experiment identifiers
- architecture documentation
- reproducibility standards

## Phase 2 — Benchmarks

- tokenizer benchmarks
- architecture benchmarks
- CrossSilicon benchmarks
- reasoning evaluations

## Phase 3 — Shared Tooling

- DataForge
- ReasonKit
- DualForge
- experiment registry

## Phase 4 — Infrastructure

- shared storage
- GPU nodes
- distributed workloads
- observability
- Kubernetes / k3s
- edge devices

## Phase 5 — Advanced Architecture Research

- GDN
- GDN2
- FlashQLA
- sparse architectures
- Mixture-of-Experts
- Mixture-of-Memory
- recurrence
- long-context systems

## Phase 6 — KittyTron

Use findings from both model families to design the first genuinely joint Kitty × Tweak experimental model.

---

# 🎯 Long-Term Vision

The long-term goal is to evolve from:

```text
Two Developers
      ↓
Two Independent Research Ecosystems
      ↓
Shared Experiments
      ↓
Shared Benchmarks
      ↓
Shared Infrastructure
      ↓
Original Models
      ↓
Original Architectures
      ↓
Published Research
      ↓
KITTY × TWEAK LABS
```

The aim is not simply to build increasingly large systems.

It is to become increasingly capable of **understanding, designing, testing, and improving complex systems ourselves.**

---

# 💜❤️ Why KITTY × TWEAK?

KITTY × TWEAK LABS exists because both researchers bring different strengths, ideas, hardware environments, and ways of thinking.

That difference is useful.

Two independent model families allow us to compare approaches.

Two different hardware ecosystems allow us to test portability.

Two perspectives allow ideas to be challenged rather than simply accepted.

The lab is therefore built around:

> **collaboration without losing independent experimentation.**

---

# 📜 Status

**Research Master Plan:** `v1.0`

**Status:** Active Development & Research

This repository is expected to evolve continuously as experiments are completed, new projects are created, and research directions change.

---

# 🐱⚡ KITTY × TWEAK LABS

> **Build it.  
> Measure it.  
> Break it.  
> Understand it.  
> Improve it.  
> Document it.  
> Build the next one.**

**Models // Systems // Kernels // Agents // Security // Infrastructure**
