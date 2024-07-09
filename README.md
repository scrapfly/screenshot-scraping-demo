# llm-scraping-demo

Demo notebooks for screenshot scraping with Scrapfly Screenshot API. Used in the intro video:

[![Watch the video](https://img.youtube.com/vi/1Y-XvvWlyzk/hqdefault.jpg)](https://www.youtube.com/watch?v=1Y-XvvWlyzk)

## Setup

To use this notebook you'll need:

- [Jupyter notebook server](https://jupyter.org/)
- `httpx`

All of which can be installed using the provided `pyproject.toml` using [poetry](https://python-poetry.org/) (or any other moder python package manager):

```
$ poetry install
$ poetry run jupyter notebook

[I 2024-07-09 21:54:57.134 ServerApp] Serving notebooks from local directory: /home/scrapfly/llm-scraping-demo
[I 2024-07-09 21:54:57.134 ServerApp] Jupyter Server 2.14.1 is running at:
[I 2024-07-09 21:54:57.134 ServerApp] http://localhost:8888/tree?token=7a960bcb9
[I 2024-07-09 21:54:57.134 ServerApp]     http://127.0.0.1:8888/tree?token=7a960b
#                                         ^^^^^^^^^^ open this in your browser.
```
