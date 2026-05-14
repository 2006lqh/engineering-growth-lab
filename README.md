# Engineering Growth Lab

A structured repository for documenting my completed programming projects and algorithm implementations.

## About This Repository

This repository is used to organize and showcase my programming practice, completed mini projects, and algorithm problem solutions.

The main goal is to build stronger software engineering skills through writing readable, maintainable, and testable code.  
Instead of only recording learning notes, this repository focuses on concrete code implementations that can demonstrate my growth in computer science fundamentals and engineering ability.

## Focus Areas

- Algorithm implementation
- LeetCode-style problem solving
- Python programming practice
- C++ programming practice
- Mini software engineering projects
- AI-oriented engineering projects
- Clean code structure
- Reproducible project organization

## Repository Structure

```text
engineering-growth-lab/
├── algorithms/
│   ├── arrays/
│   ├── strings/
│   ├── hash-table/
│   ├── stack-queue/
│   ├── linked-list/
│   ├── binary-search/
│   ├── graph/
│   └── dynamic-programming/
├── projects/
│   ├── todo-cli/
│   └── mini-search-engine/
├── python-practice/
├── cpp-practice/
└── README.md
```

## Directory Guide

### `algorithms/`

This directory stores algorithm problem solutions, including LeetCode-style problems and classic data structure implementations.

Each problem folder may include:

```text
solution.py
solution.cpp
README.md
test_solution.py
```

Recommended structure:

```text
algorithms/
├── arrays/
│   └── two-sum/
│       ├── solution.py
│       └── README.md
├── binary-search/
│   └── search-in-rotated-sorted-array/
│       ├── solution.py
│       └── README.md
└── graph/
    └── number-of-islands/
        ├── solution.py
        └── README.md
```

### `projects/`

This directory stores complete mini projects.

Planned projects include:

```text
projects/
├── todo-cli/
└── mini-search-engine/
```

Each project should include its own:

```text
README.md
src/
tests/
requirements.txt
```

### `python-practice/`

This directory stores small Python programming exercises that are not large enough to become independent projects.

### `cpp-practice/`

This directory stores small C++ programming exercises, STL practice, and compilation examples.

## Current Project Plan

### 1. Todo CLI

A command-line task management tool for practicing basic Python project structure.

Planned features:

- Add tasks
- List tasks
- Mark tasks as completed
- Delete tasks
- Store data locally in JSON format

### 2. Mini Search Engine

A small local search engine project for practicing data structures, text processing, ranking, and engineering organization.

Planned features:

- Text preprocessing
- Tokenization
- Inverted index
- Keyword search
- Top-K ranking
- Unit tests
- Command-line interface
- Possible RAG-oriented extension

## Coding Principles

- Write code that is readable and explainable
- Keep each project organized and reproducible
- Use meaningful commit messages
- Add README files for important projects
- Add tests when appropriate
- Avoid uploading code that I do not understand
- Use AI tools for assistance, but independently understand and verify the final code

## Commit Message Style

Recommended commit prefixes:

```text
feat:      add a new feature
fix:       fix a bug
docs:      update documentation
test:      add or update tests
refactor:  improve code structure without changing behavior
chore:     update project structure or configuration
```

Examples:

```bash
git commit -m "feat: implement basic tokenizer"
git commit -m "test: add tokenizer unit tests"
git commit -m "docs: update mini search engine README"
git commit -m "chore: reorganize repository structure"
```

## Long-Term Goal

To build a clean and meaningful code portfolio that demonstrates my progress in algorithms, software engineering, and AI-oriented project development.
