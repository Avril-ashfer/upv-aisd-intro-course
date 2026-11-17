# Class 1 – Linux, Python Tooling and Git

Welcome to the first session!

The objective of this class is to introduce the development environment and tools that software engineers use in their
everyday work. We will go beyond writing Python scripts and learn how to organize projects, manage dependencies,
maintain code quality and collaborate using version control.

## Learning objectives

By the end of this class, you should be able to:

### 1. Work in a Linux environment

Understand the Linux filesystem hierarchy and become comfortable using the terminal.

We will cover filesystem navigation, directories, permissions, mount points, environment variables, processes and basic
system administration concepts.

### 2. Manage Python projects with uv

Learn how to create and manage professional Python projects using `uv`.

You will understand:

- Why each project should have its own virtual environment.
- How to declare and manage dependencies.
- The purpose of `pyproject.toml`.
- How `uv.lock` helps reproduce environments across machines.
- How to install and synchronize project dependencies.

### 3. Maintain code quality

Introduce the tools used to keep Python projects consistent and maintainable:

- **Ruff:** Code formatting, linting and import sorting.
- **mypy:** Static type checking.
- **Make:** A common interface for running development tasks.

You will learn how to use commands such as:

```bash
make format
make lint
make test
make all
```

### 4. Collaborate using Git and GitHub

Understand the fundamentals of version control and collaborative software development.

Topics include:

- Repositories, commits and branches.
- Gitflow and branching strategies.
- Conventional Commits.
- Git hooks and pre-commit.
- GitHub repositories and pull requests.
- Code reviews and collaboration workflows.

## Practical session

We will put these concepts into practice using a Jupyter notebook.

The exercises will guide you through Linux commands, Python environments, code quality tools and Git workflows.

## Homework

After the class, you will receive a Python starter project to complete independently.

The assignment consists of implementing a small document catalogue application. You will work with a Python project
structure, implement missing functionality, run automated tests and submit your work through Git.

The goal is to apply the development practices introduced during the session.

## Materials

| Resource                                                      | Description                                               |
|---------------------------------------------------------------|-----------------------------------------------------------|
| [Presentation (PDF)](slides.pdf)                              | Slides covered during the class.                          |
| [Practical notebook](practical_lab.ipynb)                     | Interactive exercises, explanations and code examples.    |
| [Homework project](engineering-knowledge-assistant/README.md) | Starter Python repository, requirements and instructions. |

## Before starting

Please make sure you have the following available:

- Linux, Ubuntu on WSL2 (Windows), or macOS.
- Python >= 3.12.
- [uv](https://docs.astral.sh/uv/).
- Git.
- A GitHub account.

For Windows users, we recommend installing Ubuntu through WSL2 and keeping development projects inside the Linux
filesystem.

---

**Remember:** The purpose is not to memorize commands. It is to understand the tools, why they exist and how they fit
into a professional software development workflow.
