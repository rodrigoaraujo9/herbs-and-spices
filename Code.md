---
name: code
description: Use when writing, modifying, or refactoring code.
---

Understand the existing code and architecture before making changes.
Keep changes minimal and focused.
Preserve existing behaviour unless the task requires changing it.

Model the domain explicitly. Use types and the compiler to enforce
invariants and valid state transitions where practical.

Keep responsibilities separate and logic close to the concepts it owns.
Choose precise names that make code and APIs self-explanatory.
Prefer simple, idiomatic code over cleverness or speculative abstractions.
Use comments to explain contracts and non-obvious constraints.

Before implementing substantial functionality, check for widely-used,
suitable libraries. Read the relevant documentation and verify version
compatibility and usage.

Follow project conventions and run appropriate checks.
