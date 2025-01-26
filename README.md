## Label GPT

라벨 자동 생성 by GPT

## Prerequisites

- [python 3.11](https://www.python.org/downloads/release/python-3119/)
- [uv](https://docs.astral.sh/uv/getting-started/installation/)

## Create and Run Virtual Environment

```bash
uv venv
source .venv/bin/activate
```

## Install Dependencies

```bash
uv pip install -r pyproject.toml
```

## Run Streamlit Dev Server

```bash
streamlit run App.py
```

## Quit Virtual Environment

```bash
deactive
```

## Environment Variables

```bash
# .env and .streamlit/secrets.toml
OPENAI_API_KEY=sk-1234123412341234
```
