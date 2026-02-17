# Customer Churn Prediction Platform 
## Overview
A production-style machine learning system for predicting customer churn.

## System Capabilities
- Reproducible training pipeline
- Experiment tracking and model versioning (MLflow)
- Model quality gates before promotion
- CI checks for automated testing and code quality
- API-based model serving
- Containerization for consistent runtime (Docker)
- Monitoring for drift and performance degradation
- Champion/Challenger evaluation (A/B-style model comparison)

## Tech Stack
- Python, pandas, numpy
- scikit-learn
- MLflow
- FastAPI + Uvicorn
- GitHub Actions (CI)
- Evidently (monitoring)

## Repository Structure
- `src/` – core ML/application code
- `api/` – inference service (FastAPI)
- `tests/` – automated tests
- `.github/workflows/` – CI pipeline
- `requirements.txt` – dependencies
