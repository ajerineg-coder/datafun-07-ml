# datafun-07-ml

**Author:** Addie  
**GitHub Repo:** https://github.com/ajerineg-coder/datafun-07-ml  

---

## Overview

This repository contains Project 7 for Module 7.  
The goal of this project is to set up a predictive machine learning project using a repeatable workflow with Git, virtual environments, and required data science packages.

---

## Project Setup

```bash
cd ~/Documents
git clone https://github.com/ajerineg-coder/datafun-07-ml.git
cd datafun-07-ml
```

---

## Create and Activate Virtual Environment

```bash
python3 -m venv .venv
source .venv/bin/activate
```

---

## Install Required Packages

```bash
pip install jupyterlab numpy pandas pyarrow matplotlib seaborn scipy
pip freeze > requirements.txt
```

---

## Repeatable Daily Workflow

```bash
git pull
source .venv/bin/activate
pip install -r requirements.txt
git add -A
git commit -m "Update project"
git push
```

---

## Notes

This project uses:
- Python virtual environment (.venv)
- requirements.txt for dependencies
- pyproject.toml for project configuration
- GitHub for version control

All setup steps were tested and verified on macOS.