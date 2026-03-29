##how to use venv to create a virtual environment to run python

###create local venv
```bash
python -m venv .venv
```

Example visual output
```bash
/CODE/COOP_vincent_group_project_1/.venv/Scripts/python
(.venv)
```

###Install the same dependancies on this project
```bash
pip install -r requirements.txt
```

###activate:
###macOS
```bash
source .venv/Scripts/activate
```

###Windows
```bash
.venv/Scripts/activate
```

###deactivate:
```bash
deactivate
```

###shows what version you are using
```bash
which python
```