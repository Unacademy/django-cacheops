# django-cacheops

> A slick ORM cache with automatic granular event-driven invalidation.

---

## Table of Contents

1. [Overview](#overview)
2. [Tech Stack](#tech-stack)
3. [Repository Structure](#repository-structure)
4. [Key Components](#key-components)
5. [Setup & Installation](#setup--installation)
6. [Running the Application](#running-the-application)
7. [Infrastructure & CI/CD](#infrastructure--cicd)
8. [Contributing](#contributing)

---

## Overview

**django-cacheops** is part of the [Unacademy](https://github.com/unacademy) engineering ecosystem.

A slick ORM cache with automatic granular event-driven invalidation.

**Topics / Tags:** `approvers-1`

---

## Tech Stack

| Attribute | Value |
|-----------|-------|
| **Primary Language** | Python |
| **Framework / Platform** | Python |
| **Package Manager** | pip |

### Dependencies

No dependency files detected (check source files manually).


---

## Repository Structure

```
django-cacheops/
├── .gitignore
├── .travis.yml
├── CHANGELOG
├── LICENSE
├── MANIFEST.in
├── README.rst
├── bench.py
├── cacheops/
│   ├── __init__.py
│   ├── conf.py
│   ├── cross.py
│   ├── invalidation.py
│   ├── jinja2.py
├── manage.py
├── requirements-test.txt
├── run_tests.py
├── setup.cfg
├── setup.py
├── tests/
│   ├── __init__.py
│   ├── bench.py
│   ├── fixtures
│   ├── models.py
│   ├── settings.py
├── tox.ini
```

---

## Key Components

Below is an analysis of the key files and modules:

| File / Directory | Purpose |
|-----------------|---------|
| `CHANGELOG` | Source file |
| `LICENSE` | Source file |
| `MANIFEST.in` | Source file |
| `README.rst` | Source file |
| `bench.py` | Source file |
| `cacheops/__init__.py` | Source file |
| `cacheops/conf.py` | Source file |
| `cacheops/cross.py` | Source file |
| `cacheops/invalidation.py` | Source file |
| `cacheops/jinja2.py` | Source file |
| `cacheops/lua/cache_thing.lua` | Source file |
| `cacheops/lua/invalidate.lua` | Source file |
| `cacheops/management/__init__.py` | Source file |
| `cacheops/management/commands/__init__.py` | Source file |
| `cacheops/management/commands/cleanfilecache.py` | Source file |
| `cacheops/management/commands/invalidate.py` | Source file |
| `cacheops/query.py` | Source file |
| `cacheops/redis.py` | Source file |

> **Note:** Only the first 20 non-trivial files are listed. See the repository tree above for the complete structure.

---

## Setup & Installation

### Prerequisites

- Git (`git --version`)
- Python runtime installed



### Steps

```bash
git clone git@github.com:unacademy/django-cacheops.git
cd django-cacheops

python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```


---

## Running the Application

```bash
python3 main.py   # or uvicorn/gunicorn for web services
```

---

## Infrastructure & CI/CD

- Test suite present — run tests before submitting PRs

---

## Contributing

1. Create a feature branch: `git checkout -b feat/your-feature`
2. Commit your changes: `git commit -m "feat: describe your change"`
3. Push and open a PR targeting `master`
4. Ensure all CI checks pass before requesting review

---

---

*This README was auto-generated on 2026-09-14 by the Unacademy repo-summarizer tool.*
*For corrections or additions, edit this file directly or open an issue.*
