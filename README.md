# Cedar Worker

Worker em memoria com retry e dead-letter, no dominio **platform / SRE**. Nao conecta em fila externa nem dispara rede.

```bash
python -m venv .venv
.venv/Scripts/activate
pip install -e ".[dev]"
python -m worker.cli
pytest -q
```
