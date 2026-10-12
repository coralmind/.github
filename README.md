# CoralMind organization defaults

This repository is the public `.github` repo for the [CoralMind](https://github.com/coralmind) organization. GitHub uses a fixed set of files here as the default community health files for every CoralMind repository that does not carry its own copy.

The [organization profile](profile/README.md) is separate. It is the page shown at [github.com/coralmind](https://github.com/coralmind).

## What GitHub inherits from here

These files apply automatically to other CoralMind repositories. A copy committed in a project repository replaces the default for that repository only.

| File | What it does |
|---|---|
| [CONTRIBUTING.md](CONTRIBUTING.md) | Shown when someone opens an issue or pull request |
| [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) | Linked from the repository's community profile |
| [SECURITY.md](SECURITY.md) | Enables the security policy and private reporting guidance |
| [SUPPORT.md](SUPPORT.md) | Shown from the community profile |
| [.github/ISSUE_TEMPLATE/](.github/ISSUE_TEMPLATE/) | The new-issue forms |
| [.github/PULL_REQUEST_TEMPLATE.md](.github/PULL_REQUEST_TEMPLATE.md) | The pull request description template |

Inheritance is virtual. The files are not copied into other repositories, and they do not appear in clones or forks. A change on the default branch of this repository takes effect across the organization immediately.

`profile/README.md` and this readme are not community health files. GitHub uses `profile/README.md` only as the organization profile, and this readme only describes this repository.

## Licenses for the projects

Code is released under the Apache License 2.0. Content, including JSON and YAML files that carry that content, is released under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).

GitHub does not inherit a license from this repository. `knowledge-library`, `toolkit`, and any other project need their own `LICENSE` and, where they contain content, their own `CONTENT_LICENSE.md`. Without those files, GitHub shows no license on the project and a clone ships with no license.
