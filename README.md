# crypto-pulse

<div align="left">
  <img src="https://img.shields.io/badge/Status-Alpha-orange?style=flat-square" alt="Project Status">
  <img src="https://img.shields.io/badge/License-Apache%202.0-blue?style=flat-square" alt="License">
  <img src="https://img.shields.io/badge/Compliance-DCO-green?style=flat-square" alt="DCO Compliant">
  <img src="https://img.shields.io/badge/Go-1.22%2B-00ADD8?style=flat-square&logo=go" alt="Go Version">
  <img src="https://img.shields.io/badge/SBOM-CycloneDX%201.5-cb0e0e?style=flat-square" alt="CycloneDX 1.5">
</div>

---

**Crypto-Pulse** is an enterprise-grade, air-gapped cryptographic discovery engine designed to audit codebase lineages for post-quantum readiness. By analyzing Abstract Syntax Trees (AST) natively and completely offline, the engine surfaces cryptographic assets, quantifies risk against post-quantum encryption standards, and generates a comprehensive **Cryptographic Bill of Materials (CBOM)** compliant with the CycloneDX 1.5+ specification.

Built specifically for high-compliance environments, financial infrastructure networks, and open-source ecosystems, Crypto-Pulse operates with **zero external network dependencies**—ensuring sensitive enterprise IP never leaves your secure execution perimeter.

## Key Capabilities

* **Air-Gapped AST Analysis:** Deep static analysis of codebase syntax trees without relying on external SaaS connections or cloud-based tokenizers.
* **Post-Quantum Cryptography (PQC) Readiness Mapping:** Evaluates existing cryptographic implementations against newly finalized standards such as **FIPS 203** (ML-KEM) and **FIPS 204** (ML-DSA).
* **Automated CBOM Engineering:** Assembles discrete cryptographic inventories spanning algorithms, key lengths, curves, and implementation scopes into rigorous CycloneDX v1.5 JSON/YAML schemas.
* **Zero-Trust CI/CD Gates:** Easily drops into standard DevSecOps pipelines as a definitive policy enforcement checkpoint to block the introduction of legacy or broken algorithms.

---

## Architectural Overview

Crypto-Pulse decouples dependency ingestion from vulnerability evaluation to maintain strict offline containment:
