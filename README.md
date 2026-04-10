# KAMAL-POP

**Author**: Someyo Kamal  
**Version**: 1.0 (April 2026)

Population-Level Causal Disentanglement Framework for Cross-Domain Time Series Anomaly Detection.

## Features
- Population-level (group) anomaly detection
- Causal disentanglement + domain-invariant representations
- Synthetic group anomaly injection during training
- GPU-ready (RTX 3060 optimized)
- Easy to extend to SWaT, WADI, Exathlon

## Quick Start

```powershell
python scripts/preprocess.py
python scripts/train.py
python scripts/evaluate.py
python scripts/inference.py