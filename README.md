# Cookiecutter Poetry Starter

> cookiecutter https://github.com/mic1on/cookiecutter-poetry-starter.git


## Quickstart

install `cookiecutter` and directly pass the URL to this Github repository to the cookiecutter command:

```bash
pip install cookiecutter

cookiecutter https://github.com/mic1on/cookiecutter-poetry-starter.git
```


## Developing

```text
make install             # Run `poetry install`
make lint                # Runs bandit and black in check mode
make format              # Formats you code with Black
make test                # run pytest with coverage
make publish             # run `poetry publish --build` to build source and wheel package and publish to pypi
```