# {{ cookiecutter.package_name }}

<a href="https://github.com/{{ cookiecutter.github_user }}/{{ cookiecutter.package_name }}/actions/workflows/test.yml?query=event%3Apush+branch%3Amain" target="_blank">
    <img src="https://github.com/{{ cookiecutter.github_user }}/{{ cookiecutter.package_name }}/workflows/test%20suite/badge.svg?branch=main&event=push" alt="Test">
</a>
<a href="https://pypi.org/project/{{ cookiecutter.package_name }}" target="_blank">
    <img src="https://img.shields.io/pypi/v/{{ cookiecutter.package_name }}.svg" alt="Package version">
</a>

<a href="https://pypi.org/project/{{ cookiecutter.package_name }}" target="_blank">
    <img src="https://img.shields.io/pypi/pyversions/{{ cookiecutter.package_name }}.svg" alt="Supported Python versions">
</a>

{{ cookiecutter.description }}


## Developing

```text
make install             # Run `poetry install`
make lint                # Runs bandit and black in check mode
make format              # Formats you code with Black
make test                # run pytest with coverage
make publish             # run `poetry publish --build` to build source and wheel package and publish to pypi
```