# Personal API – Stage 1 DevOps (FastAPI)

A minimal FastAPI service deployed on a VPS behind Nginx.

## How to run locally

```bash
pip install -r requirements.txt
uvicorn main:app --reload --port 3000