---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Incoming thesis master's student, Computer Science, University of Toronto, 2027 (expected)
  * Supervisor: Prof. Xujie Si
  * Research direction: agentic kernel generation and optimization, machine learning for code verification, and deep learning interpretability.
* B.Sc. in Mathematics and Computer Science, McGill University, 2021–2027
  * GPA: 3.78/4.00

Industry experience
======
* May 2025 – August 2026: Machine Learning System Engineer Intern
  * Qualcomm, Toronto, Canada
  * Maintained machine learning infrastructure and automated testing pipelines supporting model deployment.
  * Applied graph optimization and ONNX model compilation to computer vision workloads on Snapdragon hardware.

Research experience
======
* 2025–2026: Research Collaborations, Prof. Xujie Si's Lab (ICLR / NeurIPS 2026 projects)
  * LogicXGNN: contributed to the design and testing of graph-hashing-based predicate construction; evaluated predicate extraction and hyperparameter choices with fidelity comparisons against GLGExplainer and GraphTrail.
  * Neural Proposals, Symbolic Guarantees: tested molecular tile decomposition, ran small-scale experiments, and contributed to proof writing for a framework combining neural proposals with SMT-based graph assembly.
* May 2023 – August 2023: Undergraduate Research Assistant, McGill University
  * SAT-DIFF: developed a MaxSAT-based framework for computing minimal edit scripts between ordered trees; proposed two solver optimizations and evaluated SAT-DIFF against GumTree.
* May 2022 – May 2023: Student Researcher, Mila – Quebec AI Institute
  * Language models for type-error diagnosis: continued pre-training and fine-tuning of BERT models for type-error localization in OCaml programs; structural probes for syntactic structure.
  * Neural network verification and robustness: proposed a metric to estimate expansion of the verifiable input space under reduced neural specifications; evaluated zero-bias networks on computer vision benchmarks.

Selected project
======
* June 2026: Team Lead, Assistive Cyber Eyes — 2025 Snapdragon AI Innovation Challenge (China)
  * Led the team and developed an AI navigation-assistance prototype for blind users on Qualcomm SM8850 hardware.
  * Won Merit Award as one of 27 finalist teams from 1,000+ registered teams.

Skills
======
* Languages: Python, C++, C, Java, OCaml, SQL, R
* ML tools: PyTorch, ONNX, NumPy, pandas, TensorFlow
* Research methods: SAT/MaxSAT encodings, graph algorithms, predicate extraction, neural network verification, experimental evaluation

Honors and awards
======
* SPLASH Student Research Competition – Second Place (2023)
* McGill Undergraduate Student Research Award (2023)
* ENG WEEK Hackathon – First Place (2022)

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
