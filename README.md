# Travel App — Documentation

The docs live in [`docs/`](docs/index.md) as plain Markdown and are shown as a website with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/).

## Edit

Change any `.md` file in `docs/`, commit, push. The site rebuilds itself.
New page? Add the file to `docs/` and one line under `nav:` in `mkdocs.yml`.

## Preview on your laptop

```sh
pip install -r requirements.txt
mkdocs serve
```

Then open http://127.0.0.1:8000.
