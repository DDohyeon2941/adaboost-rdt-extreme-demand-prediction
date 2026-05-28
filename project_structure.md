# Project Structure

## models/

Model implementations for:
- AdaBoost.RDT
- comparison boosting methods
- noise-robust variants

---

## experiments/

Training entry points.

Main responsibilities:
- dataset split
- training
- prediction generation
- comparison experiments

Example:
- [TRAIN]Daejeon_exp_comparison_methods_boost_0311_weekends.py
  - comparison experiment on Daejeon weekend demand prediction

---

## analysis/original/

Raw prediction analysis scripts.

Includes:
- prediction visualization
- MAPE analysis
- comparison metrics
- demand pattern analysis

---

## analysis/bootstrapped/

Bootstrap evaluation pipeline.

Used for:
- robustness evaluation
- extreme-demand performance comparison
- latex table generation for papers

---

## preprocessing/

Dataset preprocessing pipeline.

Responsibilities:
- daily demand generation
- extreme demand extraction
- dataset merging
- train/test preparation
