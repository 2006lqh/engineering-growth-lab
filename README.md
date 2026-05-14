# Engineering Growth Lab

A focused code portfolio for documenting my completed programming projects and algorithm implementations.

## About This Repository

This repository is used to organize and showcase my programming projects and algorithm problem solutions.

The goal is to build a clean and meaningful code portfolio that demonstrates my progress in software engineering, algorithms, and AI-oriented project development.

Instead of storing scattered notes or temporary practice files, this repository focuses on concrete code implementations that are readable, maintainable, and explainable.

## Repository Structure

```text
engineering-growth-lab/
├── algorithms/
├── projects/
└── README.md
```

## Directory Guide

### `algorithms/`

This directory stores algorithm problem solutions, including LeetCode-style problems and classic data structure implementations.

Each problem should preferably have its own folder.

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

For each problem, the code should be clear enough to explain the main idea, edge cases, and time complexity.

### `projects/`

This directory stores complete programming projects.

Each project should have its own independent folder and include a clear project structure.

Recommended structure for each project:

```text
projects/
└── project-name/
    ├── README.md
    ├── src/
    ├── tests/
    ├── requirements.txt
    └── main.py
```

Each project README should include:

- Project overview
- Main features
- How to run
- Project structure
- Key implementation details
- Future improvements

## Current Planned Projects

### 1. Todo CLI

A command-line task management tool for practicing basic Python project structure and file-based data storage.

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
- Use AI tools for assistance, but independently understand, verify, and explain the final code

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

To build a focused and meaningful code portfolio that clearly shows:

- What projects I have completed
- What algorithm problems I have solved
- Whether my code is clear and organized
- Whether I have consistent engineering practice
- Whether I can independently understand and explain my implementations