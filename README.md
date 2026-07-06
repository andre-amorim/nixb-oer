# nixB OER Codelab

> **Live at: [oer.nixb.org](https://oer.nixb.org)**

A Didactic Laboratory for Software Reproducibility — an interactive Google Codelab that teaches *why* Nix was built, through a real-world case study.

## 🎯 What is this?

This is the Open Educational Resource (OER) component of the [nixB project](https://nixb.org), part of TM470 (The Open University). It uses a **problem-first, story-driven** pedagogical approach, starting with a real build failure and guiding learners through the reasoning that led to Nix's design.

## 🏗️ Building from Source

The codelab is authored in Google Codelab markdown format and compiled using `claat`.

```bash
# From the source repository (ou_tm470/oer):
nix develop
claat export nixb-codelab.md
```

The output is a self-contained static HTML folder that can be served from any static host.

## 📄 License

This work is licensed as an Open Educational Resource (OER) under The Open University guidelines.

---
*Andre Amorim — TM470 Capstone Project — The Open University*
