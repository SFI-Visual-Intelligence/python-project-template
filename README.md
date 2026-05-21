# Project Title

One short paragraph describing the purpose of the project.

## Installation

This project uses [`uv`](https://docs.astral.sh/uv/) for dependency management.

Install dependencies in a local venv with:

```bash
uv sync
```

Dependencies are listed in `pyproject.toml`. Use `uv add ...` to add packages and view [`uv`](https://docs.astral.sh/uv/) docs for more info.

## Quick start
Run the main file with:

```bash
uv run python src/main.py
```

If using the code as a package with internal relative dependencies, run `uv build` from project root to build the package and then run main with:

```bash
uv run python -m python_project_template.main
```

## Repository structure
Explain structure:

```
.
├── LICENSE
├── pyproject.toml
├── README.md
└── src
    └── python_project_template
        └── main.py
```

## Data
Where data comes from, where it should live, and what is not committed.

## Experiments
How to run one minimal experiment.

## Reproducibility
Python version, uv.lock, seeds, hardware assumptions.

## Citation and LICENCE
Explain how people can cite your work by filling in `CITATION.cff` with your info.

## License
MIT license by default. Update your name and the year in `LICENCE`.

## Contact / maintainers
If you are a member of SFI Visual Intelligence and want to make changes, go ahead, it's open.
