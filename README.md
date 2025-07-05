# ChatGptCodexRepo1

This repository contains a minimal Python project using [uv](https://github.com/astral-sh/uv) as the package manager.

## Getting Started

1. Install `uv` if it is not already installed:

```bash
pip install uv
```

2. Create a virtual environment and install dependencies:

```bash
uv venv
uv pip install -r requirements.txt
```

3. Run the example module:

```bash
uv pip install -e .
python -m my_project
```

This project provides a simple `hello_world` function located in `src/my_project/__init__.py`.
