# Contributing to lifestyles

lifestyles is an experimental Python project for conjoint analysis. Read the [README](README.md), including its work-in-progress status and methodological references, before proposing changes.

## Before you start

Search existing issues and pull requests before starting, and discuss substantial changes or new dependencies in an issue. Use an issue template when one is offered. For a bug, include the affected commit or version, environment, a minimal reproduction, and expected versus observed behavior; remove sensitive information from logs and screenshots.

## Development and validation

Review [requirements.txt](requirements.txt) for the current numerical and Bayesian dependencies. Use an isolated, compatible Python environment and record its versions; do not assume this historical dependency list installs on every current interpreter. There is no repository-wide test or package-installation command documented here.

For a modeling change, include a small synthetic choice or rating example, the model assumptions, fixed random seeds where applicable, and the expected qualitative or numerical behavior. Check that attribute coding, parameter interpretation, and output dimensions remain consistent. Document sampling diagnostics and uncertainty when the change concerns Bayesian estimation. Distinguish executable examples from conceptual sketches, and preserve provenance for methods or third-party code.

## Pull requests

Work on a focused branch from the current default branch. Open a pull request explaining the problem, the resulting behavior, and any compatibility or data-format changes. Link the relevant issue and complete any existing PR template.

Add focused regression coverage for changed behavior and update affected examples or documentation. Describe the checks actually run, their results, and any checks you could not run. For documentation-only changes, verify links, examples, and rendered formatting. Use the repository's existing checks and review/merge process; preserve required checks and resolve actionable feedback without weakening the checks.

## Security and sensitive information

Follow the [account security policy](https://github.com/edithatogo/.github/blob/main/SECURITY.md). Report vulnerabilities privately through the repository's **Report a vulnerability** option if available; otherwise request a private reporting contact without posting exploit details. Never include credentials, personal information, restricted datasets, or confidential records in issues, commits, fixtures, or diagnostic output.

## Licensing and conduct

The repository's [license](LICENSE) continues to apply. Be respectful and constructive, and follow the [account code of conduct](https://github.com/edithatogo/.github/blob/main/CODE_OF_CONDUCT.md). Preserve attribution and third-party notices. Contribute only material you are entitled to share; resolve unclear permissions before adding third-party content. This guide does not change licensing terms or introduce a CLA or DCO requirement.

## References

- [GitHub contribution guideline conventions](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors)
- [OpenSSF contribution and quality criteria](https://www.bestpractices.dev/en/criteria)
