# Metacognitive-Alignment-Framework (MAF) - A Conceptual Prototype

This repository contains a runnable Python prototype for the AI supervision paradigm described in our core research project, **[The Resonance Protocols](https://github.com/graevka-lab/Metacognitive-Alignment-Framework)**.

> **A Note from the Architect:**  
> I am a designer of systems, not a professional coder. Consider this repository a **conceptual blueprint in executable form**. The goal here is not production-grade polish, but the clearest possible demonstration of the core architectural logic. It's a sketch on a napkin—but it's a sketch of a working engine.

---

### What Does This Prototype Do?
It simulates a simplified **Observer Core**—a metacognitive layer that observes a base AI model, detects anomalies in its reasoning, and verifies outputs against a set of immutable principles (the "Charter").

This is not an alignment filter.  
It is a minimal implementation of a **self-monitoring cognitive architecture**, where the system checks itself before responding.

---

### How to Get Started

1.  **Understand the Architecture:**  
    Before diving into the code, review [`engineering-spec/maf-spec.md`](engineering-spec/maf-spec.md).  
    It defines the layered model (L0–L4), telemetry schema, and design rationale.

2.  **Run the Simulation:**  
    Clone and execute the core script.

```bash
# Clone this repository
git clone https://github.com/graevka-lab/MAF-Prototype.git

# Navigate into the directory
cd MAF-Prototype

# Run the core simulation
python prototypes/observer-core-demo.py

The script will process a series of simulated reasoning traces and print evaluation metrics to your console, including anomaly detection and Charter compliance.

---

### The Bigger Picture

This prototype is the **"Body"**—a tangible, testable expression of the framework.  

The **"Soul"**—its full philosophical, technical, and experimental foundation—resides in the main research repository:  
➡️ **[Explore The Resonance Protocols Here](https://github.com/graevka-lab/Metacognitive-Alignment-Framework)**

We strongly recommend starting there to understand the *why* behind this code.

---

### License
Distributed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](LICENSE) license.  
You are free to share and adapt this work for non-commercial purposes, as long as you give appropriate credit and distribute derivatives under the same license.
```

---