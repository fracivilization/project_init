# About:
Scripts for python project initialization
# Usage
## Change project name in pyproject.toml
```
...
[tool.poetry]
name = "python" # Please Change Here
...
```
## Change paths in launch.json
```
"python.autoComplete.extraPaths": [
".venv/lib/python3.8/site-packages" # Adapt into your python version
],
"python.analysis.extraPaths": [
".venv/lib/python3.8/site-packages" # Adapt into your python version
],
```
