# aoc-2024-python
Trying some Python for AOC
(Also trying uv for Python project management)

Some setup for Jupyter integration (from [here](https://docs.astral.sh/uv/guides/integration/jupyter/#using-jupyter-with-a-non-project-environment)):
 - `uv add --dev ipykernel`

To use vscode...
```
Once the project directory is open in VS Code, you can create a new Jupyter notebook by selecting "Create: New Jupyter Notebook" from the command palette. When prompted to select a kernel, choose "Python Environments" and select the virtual environment you created earlier (e.g., .venv/bin/python)
```

Some commands to use:
 - Add a project dependency within a notebook; e.g. add pydantic: `!uv add pydantic`
 - Check syntax/style: `uv run ruff check`
