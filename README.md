# repocookier-template
A cookiecutter repository for building repositories with customized template

PYTHON

# Usage

## Install cookiecutter locally

```
pip install cookiecutter
```

## Generate repository with template

```
cd ..
cookiecutter https://github.com/mullenlucas/repocookier-template.git
```

O si no encuentra en el PATH:

```
cd ..
python -m cookiecutter https://github.com/mullenlucas/repocookier-template.git
```

O en conjunto:
```
cd new-repo
git init
git remote add origin https://github.com/mullenlucas/new_repo.git
git push -u origin master
```