# Engineering Growth Lab

A focused code portfolio for documenting my programming projects and algorithm implementations.

## About This Repository

This repository is used to organize and showcase my completed programming projects and algorithm practice.

The goal is to build a clean and maintainable code portfolio that demonstrates my progress in software engineering, algorithms, and AI-oriented project development.

To keep the repository practical and sustainable, algorithm solutions are stored as code files with brief comments, while complete projects are organized with their own README files, source code, tests, and running instructions.

## Repository Structure

```text
engineering-growth-lab/
├── algorithms/
│   ├── python/
│   │   ├── arrays/
│   │   ├── strings/
│   │   ├── hash-table/
│   │   ├── stack-queue/
│   │   ├── linked-list/
│   │   ├── binary-search/
│   │   ├── graph/
│   │   └── dynamic-programming/
│   └── cpp/
├── projects/
│   ├── todo-cli/
│   └── mini-search-engine/
└── README.md
```

## Directory Guide

### `algorithms/`

This directory stores algorithm problem solutions, including LeetCode-style problems and classic data structure implementations.

To keep the structure lightweight, each solution is stored as a single code file.

Example:

```text
algorithms/python/arrays/
├── 0001_two_sum.py
├── 0121_best_time_to_buy_and_sell_stock.py
└── 0238_product_of_array_except_self.py
```

Each solution file should include brief comments about:

- Problem name
- Category
- Main idea
- Time complexity
- Space complexity

Example:

```python
# LeetCode 1. Two Sum
# Category: Array / Hash Table
# Idea: Use a hash map to store visited numbers and find complements.
# Time: O(n)
# Space: O(n)
```

### `projects/`

This directory stores complete programming projects.

Each project should have its own folder and may include:

```text
projects/
└── project-name/
    ├── README.md
    ├── main.py
    ├── src/
    ├── tests/
    └── requirements.txt
```

Project README files should explain:

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

- Keep the repository clean and focused
- Store algorithm solutions in a lightweight format
- Maintain clear structure for complete projects
- Use meaningful file names and commit messages
- Add tests for important project modules when appropriate
- Avoid uploading code that I do not understand
- Use AI tools for assistance, but independently understand, verify, and explain the final code

## Commit Message Style

Recommended commit prefixes:

```text
feat:      add a new feature or algorithm solution
fix:       fix a bug
docs:      update documentation
test:      add or update tests
refactor:  improve code structure without changing behavior
chore:     update project structure or configuration
```

Examples:

```bash
git commit -m "feat: solve two sum with hash map"
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