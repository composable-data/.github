# composable-data (.github repo)

[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/license/MIT)
[![Check Links](https://github.com/toy-gpt/.github/actions/workflows/links.yml/badge.svg)](https://github.com/toy-gpt/.github/actions/workflows/links.yml)
[![Dependabot](https://img.shields.io/badge/Dependabot-enabled-brightgreen.svg)](https://github.com/toy-gpt/.github/security)

<img
src="https://raw.githubusercontent.com/composable-data/.github/main/docs/images/profile.png"
alt="profile logo"
width="110">

> Organization defaults and profile for the **composable-data** GitHub organization.

This is the organization's special `.github` repository.
It contains the public organization profile and community-health files GitHub
can apply across repositories that do not provide their own.

## Repository Contents

- `profile/README.md` - public landing page shown at `github.com/composable-data`
- `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, `SECURITY-POLICY.md` - org-wide community health defaults
- `CONTRIBUTING.md` - organization-wide contribution guidance
- `SECURITY-POLICY.md` - shared security reporting guidance
- `.github/dependabot.yml` - org default Dependabot configuration
- `docs/images/profile.png` - organization profile image
- shared repository configuration used by this repository

## Organization Scope

**composable-data** develops small, typed vocabularies and protocols for
expressing analytical meaning, decisions, rationale, evidence, and conclusions.

The organization does not provide a general analytics framework.

Its packages are intended to remain:

- small
- composable
- inspectable
- dependency-light
- interoperable
- based on established analytical language

The primary project is:

- [composable-data-core](https://github.com/composable-data/composable-data-core) -
  a small typed decision grammar for analytical work
  
## Related Organizations

- [analytics-toolworks](https://github.com/analytics-toolworks) -
  reusable open-source tools for analytical work
- [applied-models](https://github.com/applied-models) -
  reproducible machine-learning experiments on accessible datasets

## Maintenance

Validate repository content before committing:

```shell
npx markdownlint-cli2 --fix

git add -A
git commit -m "update"
git push -u origin main
```

## Annotations

[.annotations/annotations.md](./.annotations/annotations.md)

## License

[MIT](./LICENSE)
