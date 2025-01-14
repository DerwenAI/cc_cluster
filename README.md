Building an environment for Python 3.11:

```bash
python3 -m venv venv
source venv/bin/activate
python3 -m pip install -U pip wheel
python3 -m pip install -r requirements.txt
```

Running the notebooks:

```bash
./venv/bin/jupyter-lab
```
