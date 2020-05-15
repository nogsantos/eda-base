# {{ cookiecutter.project_base_name }} for {{ cookiecutter.project_name }}

{% if cookiecutter.license != "Not open source" %}
License {{ cookiecutter.license }}
{% endif %}

## {{ cookiecutter.description_base }}

{{ cookiecutter.description }}

Python version: {{ cookiecutter.python_version }}

## Setup

1. Create virtual env
2. Enable virtual env
3. Install dev dependencies

```console
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```
