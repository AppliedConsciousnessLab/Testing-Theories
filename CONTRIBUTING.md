# Contributing Guidelines

Thank you for your interest in contributing to the **Testing-Theories** research repository.

This repository functions as a structured research laboratory for empirically testing theoretical frameworks developed within the Applied Consciousness Lab.

The goal is to maintain clear, reproducible, and transparent research practices.

---

# Research Principles

All contributions should follow these core principles.

## 1. Transparency

All experiments must clearly document:

- hypothesis
- datasets used
- methods
- results
- interpretation

Anyone should be able to reproduce the experiment using the provided documentation.

---

## 2. Evidence Before Conclusion

Experiments should allow results to emerge from the data rather than attempting to confirm predetermined conclusions.

Unexpected results are valuable and should be documented honestly.

---

## 3. Reproducibility

Where possible, experiments should include:

- source datasets
- analysis scripts
- visualizations
- methodological notes

Reproducibility strengthens scientific credibility.

---

## 4. Versioned Experimentation

Experiments are logged sequentially in the experiment registry.

Example format:

Experiment 001  
Experiment 002  
Experiment 003  

Each experiment should reference its registry entry.

---

# Repository Structure

```
Testing-Theories/
│
├── GSS/
│   └── (tests related to Global Safety Standard)
│
├── EP/
│   └── (tests related to Emotional Physics)
│
├── SEI/
│   ├── experiments/
│   │   └── experiment_registry.md
│   │
│   ├── datasets/
│   │   └── (external datasets used in experiments)
│   │
│   ├── analysis/
│   │   └── (python / r / notebook analysis scripts)
│   │
│   └── results/
│       └── (charts, tables, experiment outputs)
│
└── Holistic/
    └── (experiments combining multiple frameworks)
```

---

# Experiment Workflow

When contributing an experiment, follow this process.

## Step 1 — Register the Experiment

Add a new entry to:

```
SEI/experiments/experiment_registry.md
```

Include:

- experiment number
- title
- hypothesis
- status (planned / in progress / completed)

---

## Step 2 — Create Experiment File

Create a documentation file in:

```
SEI/experiments/
```

Example:

```
SEI/experiments/inequality_vs_institutional_trust.md
```

This file should include:

- hypothesis
- research question
- variables
- datasets
- method
- expected outcome

---

## Step 3 — Add Datasets

If datasets are included, place them in:

```
SEI/datasets/
```

Include source citations and licensing information.

---

## Step 4 — Analysis

Analysis scripts or notebooks should be placed in:

```
SEI/analysis/
```

Examples include:

- Python scripts
- R scripts
- Jupyter notebooks
- statistical models

---

## Step 5 — Results

Document results in:

```
SEI/results/
```

Include:

- charts
- tables
- summary interpretation

---

# Citation Standards

When using external datasets or research, always include proper citation.

Preferred sources include:

- World Bank
- OECD
- Pew Research Center
- Gallup World Poll
- United Nations datasets
- World Values Survey

---

# Research Ethics

All work in this repository should follow responsible research practices.

Contributors should:

- respect data licensing agreements
- avoid misrepresentation of results
- clearly separate interpretation from evidence

The purpose of this repository is scientific exploration, not advocacy.

---

# Contribution Scope

This repository currently supports research across four primary domains:

- GSS (Global Safety Standard)
- EP (Emotional Physics)
- SEI (Societal Entropy Index)
- Holistic testing across frameworks

Contributions that improve measurement, methodology, or empirical testing are encouraged.

---

# Final Note

Complex systems research benefits from collaborative investigation and open data.

The purpose of this repository is to explore whether measurable patterns exist that improve understanding of societal stability and systemic risk.

All contributions that support transparent, evidence-based research are welcome.

---

© 2026 Applied Consciousness Lab

Licensed under Creative Commons Attribution 4.0 (CC BY 4.0)
