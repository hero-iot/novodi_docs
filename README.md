# This is the Documentation of [novodi.app](https://novodi.app/)

Visit the current public release here.

## Run the docs locally for development

1. Clone the repository
2. Navigate to the repository and activate or initalise the virtual environment

```bash
pipenv shell
pipenv update
```

3. Build the documentation locally

```bash
cd novodi_docs
mkdocs serve
```

4. Open the default link in your browser
[http://127.0.0.1:8000](http://127.0.0.1:8000)

## Developing with mkdocs

Visit the [documentation of mkdocs](https://www.mkdocs.org/user-guide)

## Deploying to GitHub Pages
```bash
cd novodi_docs
mkdocs gh-deploy
```
