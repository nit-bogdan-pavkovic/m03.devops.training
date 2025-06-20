# Module 4 - Run SAST testing

**Goal**: Run Bandit SAST detection tool

## Steps

```shell
python -m venv venv
source venv/bin/activate
```

1. Install bandit: `pip install bandit`
2. Run bandit on supplied script: `bandit -r vulnerable_script.py`
