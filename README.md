# LLM Screenplay D1 Benchmark

This repository contains anonymized materials supporting the paper:

> Exploratory Evaluation of Large Language Models for Three-Act Structure and Pacing Assessment in Student Screenplays

## Contents

- `screenplays_redacted/`: twelve anonymized and redacted student screenplays.
- `data/`: anonymized scoring metadata and aggregated LLM results.
- `excerpts/`: selected excerpts and structural annotations for the highest- and lowest-rated screenplays.
- `analysis/`: Python script used to reproduce the reported D1 evaluation metrics.
- `figures/`: figures reported in the paper.

## Ethical and Data-Protection Notice

All direct identifiers and identifiable metadata have been removed. Screenplays are represented only by anonymized identifiers (S01–S12). The materials are shared for research transparency, replication, and educational purposes only. Users must not attempt to identify, contact, profile, or re-identify the student authors.

## Reproducibility

Run:

```bash
pip install -r analysis/requirements.txt
python analysis/analisis_revisi_D1.py
