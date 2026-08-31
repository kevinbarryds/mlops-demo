# ML Deployment Portfolio Project — MLOps Zoomcamp

Hands-on MLOps build project using the NYC Taxi trip duration dataset as the running example.

## Course

- Dataset: NYC Taxi trip duration data, used consistently across all modules

## Environment

**Chosen: GitHub Codespaces**

Considered three options:

| Option | Notes |
|---|---|
| AWS EC2 | (SSH, Anaconda, Docker, VS Code remote, Jupyter tunnel). More AWS-relevant, but adds setup overhead and a cost/shutdown risk. |
| **GitHub Codespaces** ✅ | Zero setup friction, free tier covers usage, gets straight to setup rather than infra fiddling. |
| Local / GCP / Azure | |

Rationale: the immediate goal is MLOps concepts and tooling (Docker, MLflow, orchestration), not AWS infrastructure administration — Codespaces gets there fastest. AWS setup may be revisited later as a deliberate refresh of lapsed AWS certifications (Cloud Practitioner, ML Specialty), particularly once the course reaches deployment/monitoring modules where AWS is used more directly.

## Progress

- [x] Module 1 — Intro, environment setup (Codespaces), MLOps maturity model, NYC Taxi dataset loaded
- [ ] Module 2 — Experiment tracking (MLflow) — scheduled 9/1
- [ ] Module 6 — CI/CD — scheduled 9/3
- [ ] Module 5 — Monitoring — scheduled 9/5

## Notes

- Setup snags and environment decisions logged here as the project progresses.
