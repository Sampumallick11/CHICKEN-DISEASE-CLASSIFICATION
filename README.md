# Chicken Disease Classification Project

## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update entity
4. Update configuration manager
5. Update components
6. Update pipeline
7. Update main.py
8. Update dvc.yaml

---

## Setup Instructions

### Step 1: Create environment

```bash
conda create -n chicken_env python=3.10 -y
conda activate chicken_env
```

### Step 2: Install dependencies

```bash
pip install -r requirements.txt
pip install -e .
```

---

## Run Project

```bash
python main.py
```

---

## DVC Commands

```bash
dvc init
dvc repro
dvc dag
```

---

## Deployment (Overview Only)

* Docker build & push
* AWS EC2 + ECR deployment
* Azure deployment

