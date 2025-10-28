---
title: "Quantum Ground State Estimation using VQE"
date: 2025-07-29
tags: ["quantum computing", "VQE", "SU(2) gauge theory", "NISQ", "quantum algorithms"]
description: "Quantum Ground State Estimation of SU(2) Gauge Theory using Variational Quantum Eigensolver on superconducting quantum devices at MCQST."
summary: "Implemented VQE algorithm for finding ground states of SU(2) Yang-Mills theory, addressing fundamental challenges in quantum physics using hybrid quantum-classical methods."
---

## Overview

**Project Title:** Quantum Ground State Estimation of SU(2) Gauge Theory using Variational Quantum Eigensolver  
**Institution:** Munich Center for Quantum Science and Technology (MCQST) / Walther-Meißner-Institut (WMI)  
**Duration:** July 29 - August 29, 2025  
**Research Team:** K. Liegener, M. Knudsen, M. Singh, M. Werninghaus, F. Roy, Prof. S. Filipp  

This research project tackled one of the fundamental challenges in quantum physics: finding the ground state of interacting Lattice Gauge Theories (LGT), which becomes computationally intractable on classical computers due to entanglement over spaced lattice sites at certain scales.

## Scientific Background

### Lattice Gauge Theory Challenge
Classical numerical simulations of SU(2) Yang-Mills theory break down at certain scales due to exponential growth of entanglement, despite the theory's fundamental importance in describing the weak force in particle physics. Quantum computers offer a natural advantage by inherently handling entangled quantum states, making this problem particularly suitable for near-term quantum devices with limited qubit counts.

### Variational Quantum Eigensolver (VQE)
VQE is a hybrid algorithm that combines quantum state preparation with classical optimization to systematically search for minimum energy eigenstates. Designed specifically for noisy, intermediate-scale quantum devices, it leverages the quantum variational principle for energy minimization while remaining compatible with current quantum hardware limitations.

## Technical Implementation

### Quantum System Design
The implementation uses a 4-qubit architecture with 3 physical qubits encoding quantum states of the SU(2) system and 1 ancilla qubit controlling circuit dynamics and enforcing symmetry constraints. The Hilbert space is truncated with maximum angular momentum j_max = 1/2 for computational tractability, focusing on the θ-graph ground state sector. The SU(2) Yang-Mills Hamiltonian is decomposed with kinetic energy terms expressed as Pauli string operators and interaction terms translated into quantum gate sequences.

A problem-specific ansatz with 6 tunable parameters was optimized for the SU(2) gauge theory structure, incorporating excitation gates for exploring physically relevant state transitions and swap gates for efficient symmetric state space exploration. The state preparation strategy encodes three angular momentum quantum numbers (j₁, j₂, j₃) while preserving gauge symmetry and minimizing gate depth for NISQ device compatibility.

The analysis employs realistic quantum measurement simulation using finite shot counts to characterize noise impact and optimize the balance between measurement accuracy and computational cost. Post-selection techniques enforce symmetry by projecting measurement outcomes into valid physical Hilbert space, ensuring gauge invariance and reducing measurement errors while confirming all results correspond to physically meaningful states.

## Research Contributions

### Algorithmic Innovations
The research validated truncation strategies by demonstrating the accuracy of low-energy cutoff approximations and showing how truncation enables practical quantum simulation while capturing essential physics. Ground state symmetries were leveraged to enhance VQA performance, achieve quantum computational advantage, and reduce quantum noise impact by incorporating fundamental physics constraints to guide quantum computation.

The VQE optimization successfully identified ground state energy within theoretical predictions, demonstrating reliable convergence and algorithm robustness to quantum device noise. Scaling analysis quantified the relationship between measurement shots and accuracy, characterizing how the energy landscape smooths with increased sampling and determining the optimal balance between accuracy and computational cost for future larger-scale implementations.

## Technical Challenges and Solutions

### NISQ Device Limitations
Quantum noise and decoherence were addressed through error mitigation techniques and noise-aware algorithm design, implementing post-selection and symmetry-based error correction to maintain physical accuracy despite device limitations. The limited qubit count challenge was solved through efficient Hilbert space truncation and problem-specific encoding, creating a 4-qubit architecture that captures essential physics within hardware constraints.

### Quantum-Classical Interface
Parameter optimization in noisy environments was achieved using robust optimization algorithms adapted for quantum objective functions, implementing gradient-free optimization with noise-aware convergence criteria for reliable results despite quantum measurement noise. State validation ensured quantum states correspond to valid physical configurations through symmetry-based validation and post-selection techniques, with automated checking of gauge invariance and physical constraints guaranteeing physical validity of all simulation results.

## Publications and Presentations

Results were presented at the MCQST Symposium and communicated to diverse audiences through student research showcases.

## Poster

Results were presented at the MCQST Symposium and communicated to diverse audiences through student research showcases.

<div style="text-align: center; margin: 20px 0;">
  <embed src="MCQST_Poster.pdf" type="application/pdf" width="100%" height="600px" />
</div>

*Note: If the PDF doesn't display above, you can [download it directly](MCQST_Poster.pdf).*

