# {{ cookiecutter.project_name }}

{{ cookiecutter.description }}

## Requirements

[!\[Python Version\](https://img.shields.io/badge/python-{{ cookiecutter.python_version }}-blue.svg)]()
* Python {{ cookiecutter.python_version }} or higher

## Table of Contents

* [Set up from Cookiecutter](#setup)
* [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing)
* [License](#license)

## Setup

> From cookiecutter

```
cd {{ cookiecutter.project_name }}
```

```
git init
git remote add origin https://github.com/{{ cookiecutter.username }}/{{ cookiecutter.project_name }}.git
git push -u origin main
```

## Installation

Install `virtualenv` if you haven't already:

```bash
pip install virtualenv
```

### Create a Virtual Environment

```bash
python -m venv {{ cookiecutter.venv_dir }}
```

### Activate the Virtual Environment

**Windows:**

```bash
.\\{{ cookiecutter.venv_dir }}\\Scripts\\activate
```

**macOS/Linux:**

```bash
source {{ cookiecutter.venv_dir }}/bin/activate
```

**Git Bash (Windows):**

```bash
. {{ cookiecutter.venv_dir }}/Scripts/activate
```

Ensure you're using the correct interpreter:

```bash
which python       # macOS/Linux
where python       # Windows
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Save Dependencies to `requirements.txt`

```bash
pip freeze > requirements.txt
```

### Optional: Deactivate the Virtual Environment

```bash
deactivate
```

## Usage

Run the entry point (adjust if necessary):

```bash
python src/main.py
```

Or if it's a module:

```bash
python -m {{ cookiecutter.module_name }}
```

## Contributing

Contributions are welcome! Please fork the repository, create a new branch for your changes, and submit a pull request.

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
