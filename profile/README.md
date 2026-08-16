# composable-data

<img
src="https://raw.githubusercontent.com/composable-data/.github/main/docs/images/profile.png"
alt="composable-data logo"
width="110">

> Small, composable vocabularies and protocols for
> expressing analytical meaning, decisions, rationale, evidence, and conclusions.

**composable-data** provides a lightweight, typed grammar for analytical work.

The goal is to make important analytical structure explicit and interoperable
without replacing the libraries that perform the analysis.

## Purpose

`composable-data` provides small shared vocabularies for expressing things such as:

- what one observation represents
- what kind of analytical problem is being addressed
- which features were selected and why
- how an experiment is split and why
- which model was chosen and why
- what evaluation evidence resulted
- what conclusion the evidence supports
- how a data-quality problem was resolved and why

It facilitates standard interactions with analytical tools that:

- load and transform data
- train models
- generate predictions
- calculate metrics
- create visualizations
- execute queries

## Projects

| Project                                                                         | Purpose                                           |
| ------------------------------------------------------------------------------- | ------------------------------------------------- |
| [composable-data-core](https://github.com/composable-data/composable-data-core) | Small, typed decision grammar for analytical work |

Any additional packages should remain independently useful and composable.

## Design Boundary

The ecosystem follows this central rule:

> Add a concept only when necessary to express a declaration that cannot
> otherwise be expressed correctly.

The shared vocabulary is intentionally small; it is not an analytics framework.

## Principles

- Derive what can be known.
- Record what happened.
- Require rationale where alternatives require analyst judgment.
- Keep analytical computation in established libraries.
- Keep domain- and dataset-specific semantics outside the core grammar.
- Use established analytical language for public names.
- Keep packages small, inspectable, typed, and dependency-light.

## Related Organizations

- [analytics-toolworks](https://github.com/analytics-toolworks) -
  reusable open-source tools for analytical work
- [applied-models](https://github.com/applied-models) -
  reproducible model experiments on accessible real-world datasets

Together, these projects support a connected analytical workflow
that enables analysts to work at a higher level:

```text
composable-data
    shared analytical meaning and decision grammar
        ↓
analytics-toolworks
    reusable tools to inspect and communicate the work
        ↓
applied-models
    reproducible experiments on real data
```

## License

Individual repositories specify their own licenses.
