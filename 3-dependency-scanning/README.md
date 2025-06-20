# Module 4 - Run dependency scanning

**Goal**: Run pip-audit against requirements.txt to check for vulnerabilities.

## Steps

```shell
python -m venv venv
source venv/bin/activate
```

1. Install bandit: `pip install pip-audit`
2. Run pip-audit on requirements.txt: `pip-audit -r requirements.txt`
