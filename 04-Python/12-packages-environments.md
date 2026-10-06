# Python Packages and Virtual Environments

Python projects often use code written by other developers. Packages are reusable collections of Python code.

## Installing a package

A common package manager is pip.

For example:

```bash
python -m pip install requests
```

Do not install a package just because a tutorial uses it. Understand what it does and use trusted sources.

## Virtual environments

A virtual environment keeps a project's installed packages separate from other Python projects.

Create one:

```bash
python -m venv .venv
```

Activate it using the command appropriate for your operating system.

Then install project dependencies inside it.

## Why this matters

Imagine Project A needs one version of a library while Project B needs another. A virtual environment prevents their dependencies from interfering with each other.

## requirements.txt

A project can record dependencies:

```text
requests
```

Then another developer can install them with:

```bash
python -m pip install -r requirements.txt
```

## Practice

Create a virtual environment for a practice project and explain why it is separate from your system Python.

## Challenge

Create a small project that uses one trusted third-party package. Document how another learner can install its dependencies.
