# ml-projects


This repo is a hands-on guide to learning the fundamentals of Machine Learning.

##  Setup

### Option 1: Local Python Environment

```bash
python -m venv venv
source venv/bin/activate   # or venv\Scripts\activate on Windows
pip install -r requirements.txt
jupyter notebook
```
### Option 2: Docker
```bash
docker build -t ml-env .
docker run -p 8888:8888 -v $(pwd):/workspace ml-env
```

### Option 3: VS Code Dev Container
Ideal for GitHub Codespaces or working locally in Visual Studio Code.

Install the "Dev Containers" extension in VS Code

Open this repo in VS Code

Press F1 → Select "Reopen in Container"

VS Code will set up the environment automatically
