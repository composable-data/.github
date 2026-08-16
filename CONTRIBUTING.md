# Contributing

Thank you for your interest in contributing to **composable-data**.

This organization develops small, typed vocabularies and protocols for
expressing analytical meaning, decisions, rationale, evidence, and conclusions.

## Contribution Principle

The ecosystem is intentionally small.

Before proposing a new public concept, ask:

> Which existing analytical declaration cannot be expressed correctly
> without this concept?

If there is no concrete answer, the concept probably does not belong in
`composable-data`.

Useful functionality alone is not sufficient reason to expand the grammar.

## Scope

Good contributions may include:

- corrections to existing analytical vocabulary
- improved typing or validation of declarations
- clearer documentation and examples
- additional established vocabulary required by an existing declaration
- interoperability improvements that preserve the dependency-light design

Out of scope for the core grammar are:

- data processing
- model training
- prediction
- metric computation
- visualization
- reporting
- database execution
- framework-specific analytical implementations
- domain- or dataset-specific behavior

Those capabilities belong in established libraries, client projects, or
separate tooling.

## Public Vocabulary

Public names should use established analytical terminology whenever possible.

New terminology should not be invented when the discipline already provides
a clear and widely understood term.

## Dependencies

Keep dependencies minimal.

Grammar packages should not depend on analytical execution libraries unless a
specific package explicitly exists to provide an integration.

## Participating

- Follow the project Code of Conduct.
- Keep contributions focused and inspectable.
- Open an issue before introducing a new public grammar concept.
- Keep implementation concerns separate from analytical semantics.

Repository-specific contribution requirements take precedence when provided.
