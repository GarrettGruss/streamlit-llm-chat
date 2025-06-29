# Streamlit LLM Chat

This is a Streamlit application for LLM chat.

## Installation

This project uses `uv` for dependency management. If you don't have `uv` installed, you can install it via `pipx`:

```bash
pipx install uv
```

To set up the project dependencies, navigate to the project root and run:

```bash
uv sync
```

## Running the Application

To run the Streamlit application, execute the following command in your terminal from the project root:

```bash
uv run streamlit run app.py
```

This will open the application in your default web browser.

## Linting and Type Checking

This project uses `ruff` for linting and `mypy` for type checking.

To run `ruff`:

```bash
uv run ruff check
uv run ruff format
```

To run `mypy`:

```bash
uv run mypy
```