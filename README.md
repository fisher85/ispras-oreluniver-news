# ispras-oreluniver-news

News website for the joint laboratory of ISP RAS and Orel State University.

This repository contains the MkDocs project used to build and publish the website.

## Local development

```bash
pip install mkdocs mkdocs-material
mkdocs serve
```

Then open `http://127.0.0.1:8000`.

## Build

```bash
mkdocs build
```

The generated static site will be available in the `site/` directory.

## Deployment

Deployment is performed via GitHub Actions after changes are merged into the `main` branch.

## Repository description

News from the joint laboratory of the ISP RAS and Orel State University.