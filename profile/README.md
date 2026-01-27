# Contributing Guidelines

Thank you for your interest in contributing. This document outlines how to participate effectively across our organisation.

---

## 1. Getting Started
- Ensure you have access to the relevant repositories.
- Review the README and any project‑specific documentation.
- Follow our coding standards and architectural guidelines.

---

## 2. Conventions

This organisation follows a set of development conventions to keep the codebase consistent, predictable, and easy to maintain.

### Commit Message Format - Conventional Commits

All commits should follow the **Conventional Commits** specification.  
This helps maintain readable history, enables automated tooling, and clarifies intent.

Common prefixes include:

- `feat:` - new features  
- `fix:` - bug fixes
- `refactor:` - code restructuring without behavior changes  
- `chore:` - maintenance tasks  
- `test:` - adding or updating tests  

More details: [https://www.conventionalcommits.org/](https://www.conventionalcommits.org/en/v1.0.0/#summary)

### Branching & Commit Discipline

To keep the repository clean and reviewable:

- Each **branch** should focus on a single feature, fix, or task.  
- Each **commit** should represent one logical change.  
- Avoid mixing unrelated changes in the same commit or branch.  
- Use descriptive branch names such as:
  - `main` - stable, production-ready
  - `develop` - integration branch  
  - `feature/<short-description>` - new work  
  - `fix/<short-description>` - bug fixes  
  - `chore/<short-description>` - maintenance tasks
  - `refactor/<short-description>` - large code changes
