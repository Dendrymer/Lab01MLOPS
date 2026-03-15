
# MLOps course

Topics:
1. [MLOps introduction](lab01) - dependency management, code quality, Git, FastAPI, Docker
2. [Databases & file formats](lab02) - PostgreSQL, DuckDB, Parquet
3. [Data processing](lab03) - Polars
4. [Vector databases](lab04) - pgvectorscale, SQLAlchemy, Milvus
5. [Versioning](lab05) - DVC, MLFlow
6. [ML testing & data-centric AI](lab06) - CleanLab, Giskard, Captum, SHAP
7. [Model optimization for inference](lab07) - PyTorch optimization, ONNX, ONNX Runtime
8. [Monitoring & drift detection](lab08) - Evidently, NannyML
9. [Introduction to cloud computing](lab09) - AWS services
10. [Infrastructure as Code (IaC)](lab10) - Terraform
11. [Deployment & CI/CD](lab11) - GitHub Actions
12. [ML pipelines](lab12) - Apache Airflow
13. [LLMOps](lab13) - vLLM, Model Context Protocol (MCP), guardrails
14. [ML system design](lab14)
=======
# Lab 1 - MLOps introduction

This lab introduces you to basic MLOps tools and local model serving. We will
go over modern Python and DevOps tools and their usage in MLOps. This will cover
setting up an entire application from scratch to get a fully functional and
containerized model running locally.

**Learning plan**
1. Python development tools
   - dependency management, `uv`
   - code versioning, `git` and GitHub
   - pre-commit hooks
   - testing, `pytest`
   - serving models with FastAPI
2. DevOps tools
   - environment variables management, `.env` files
   - secrets management, `sops`
   - containers, Docker, Docker Compose

**Necessary software**
- [Docker and Docker Compose](https://docs.docker.com/engine/install/), 
  also [see those post-installation notes](https://docs.docker.com/engine/install/linux-postinstall/)
- [uv](https://docs.astral.sh/uv/getting-started/installation/)
- [sops](https://github.com/getsops/sops)

Note that you should also activate `uv` project and install dependencies with `uv sync`.

**Lab**

See [lab instruction](LAB_INSTRUCTION.md). Laboratory is worth 5 points.

**Homework**

See [homework instruction](HOMEWORK.md). Homework is worth 10 points.

