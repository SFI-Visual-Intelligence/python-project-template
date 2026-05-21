> [!IMPORTANT]
> This document is written both as a guide and example. Explanation parts are in Notes blockquotes and can simply be removed while building the repository.

# Project Title

> [!NOTE]
> One short paragraph describing the purpose of the project.

## Installation

> [!NOTE]
> Whether your project is built around pip, conda, uv or another tool, provide here the necessary information for a full setup. Inform in the README about the basic setup needs (coding language and last version it is updated for, prefered OS, hardware and processing units).
>
> To facilitate it for other users, preferably prepare an install that is usable on the various system softwares and common computer hardwares. If that isn't possible, try to document the installation required to make it work with different computers and systems, and if any isn't supported. You can also mention if the project has only been tested with a specific OS or processors, or for example if it works with different ones but is faster on a prefered one.
>
> We recommend using [`uv`](https://docs.astral.sh/uv/) as it is a fast and easy tool, enables building the code into its own package and gathers all dependencies into a single file for an easier install. Use the `pyproject.toml` file to declare the dependencies.
>
> Here's how it can be presented:

This project uses [`uv`](https://docs.astral.sh/uv/) for dependency management.

*Here add more detail information about the install, as explained above*

Install dependencies in a local venv with:
```bash
uv sync
```
Dependencies are listed in `pyproject.toml`.

Use `uv add ...` to add packages, and view [`uv`](https://docs.astral.sh/uv/) docs for more info.

### Quickstart
Run the main file with:

```bash
uv run python src/main.py
```

> If using the code as a package with internal relative dependencies, run `uv build` from project root to build the package and then run main with:

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
