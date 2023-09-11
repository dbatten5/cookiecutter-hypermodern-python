# cookiecutter-hypermodern-python

<!-- badges-begin -->

[![CalVer][calver badge]][calver]
[![License][license badge]][license]
[![pre-commit enabled][pre-commit badge]][pre-commit project]
[![Black codestyle][black badge]][black project]
[![Contributor Covenant][contributor covenant badge]][code of conduct]
[![pdm-managed][pdm badge]][pdm]
[![Ruff][ruff badge]][ruff]

[black badge]: https://img.shields.io/badge/code%20style-black-000000.svg
[black project]: https://github.com/psf/black
[calver badge]: https://img.shields.io/badge/calver-YYYY.MM.DD-22bfda.svg
[calver]: http://calver.org/
[code of conduct]: https://github.com/dmcc/cookiecutter-hypermodern-python/blob/main/CODE_OF_CONDUCT.md
[contributor covenant badge]: https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg
[license badge]: https://img.shields.io/github/license/dmcc/cookiecutter-hypermodern-python
[license]: https://opensource.org/licenses/MIT
[pdm badge]: https://img.shields.io/badge/pdm-managed-blueviolet
[pre-commit badge]: https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white
[pre-commit project]: https://pre-commit.com/
[ruff badge]: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json

<!-- badges-end -->

<p align="center"><img alt="logo" src="docs/_static/logo.png" width="50%" /></p>

[Cookiecutter] template for a Python package based on the
[Hypermodern Python] article series. Original version at [here](https://github.com/cjolowicz/cookiecutter-hypermodern-python).

**About this fork:** This is my first venture into [Cookiecutter], so tread carefully -- many parts are untested. While incomplete and under-documented, this may be useful for the experienced cookiecutter-er (ahem). This fork aims to integrate some different tooling choices over [Hypermodern Python] and be reasonably opinionated:

- [pdm] instead of [Poetry]
- [ruff] instead of various linters which ruff has since absorbed (This work was primarily done by [dbatten5]. Thank you!).

Also note that while [Hypermodern Python] is geared towards [Click] apps, my original focus is libraries. I also assume vscode integration which is automatically configured for new projects.

[cookiecutter]: https://github.com/audreyr/cookiecutter
[hypermodern python]: https://medium.com/@cjolowicz/hypermodern-python-d44485d9d769
[dbatten5]: https://github.com/dbatten5/cookiecutter-hypermodern-python/tree/main

## Usage

```console
cookiecutter gh:dmcc/cookiecutter-hypermodern-python
```

## Features

(note: may be outdated -- [ruff] reimplements some of these tools)

<!-- features-begin -->

- Packaging and dependency management with [pdm]
- Test automation with [Nox]
- Linting with [pre-commit] and [ruff]
- Continuous integration with [GitHub Actions]
- Documentation with [Sphinx], [MyST], and [Read the Docs] using the [furo] theme
- Automated uploads to [PyPI] and [TestPyPI]
- Automated release notes with [Release Drafter]
- Automated dependency updates with [Dependabot]
- Code formatting with [Black] and [Prettier]
- Testing with [pytest]
- Code coverage with [Coverage.py]
- Coverage reporting with [Codecov]
- Command-line interface with [Click]
- Static type-checking with [mypy]
- Runtime type-checking with [Typeguard]
- Automated Python syntax upgrades with [pyupgrade]
- Security audit with [Bandit] and [Safety]
- Check documentation examples with [xdoctest]
- Generate API documentation with [autodoc] and [napoleon]
- Generate command-line reference with [sphinx-click]
- Manage project labels with [GitHub Labeler]

The template supports Python 3.10.

[autodoc]: https://www.sphinx-doc.org/en/master/usage/extensions/autodoc.html
[bandit]: https://github.com/PyCQA/bandit
[black]: https://github.com/psf/black
[click]: https://click.palletsprojects.com/
[codecov]: https://codecov.io/
[coverage.py]: https://coverage.readthedocs.io/
[dependabot]: https://github.com/dependabot/dependabot-core
[ruff]: https://beta.ruff.rs/docs/
[furo]: https://pradyunsg.me/furo/
[github actions]: https://github.com/features/actions
[github labeler]: https://github.com/marketplace/actions/github-labeler
[isort]: https://pycqa.github.io/isort/
[mypy]: http://mypy-lang.org/
[myst]: https://myst-parser.readthedocs.io/
[napoleon]: https://www.sphinx-doc.org/en/master/usage/extensions/napoleon.html
[nox]: https://nox.thea.codes/
[pdm]: https://pdm.fming.dev/latest/
[poetry]: https://python-poetry.org/
[pre-commit]: https://pre-commit.com/
[prettier]: https://prettier.io/
[pypi]: https://pypi.org/
[pytest]: https://docs.pytest.org/en/latest/
[pyupgrade]: https://github.com/asottile/pyupgrade
[read the docs]: https://readthedocs.org/
[release drafter]: https://github.com/release-drafter/release-drafter
[ruff]: https://github.com/astral-sh/ruff
[safety]: https://github.com/pyupio/safety
[sphinx]: http://www.sphinx-doc.org/
[sphinx-click]: https://sphinx-click.readthedocs.io/
[testpypi]: https://test.pypi.org/
[typeguard]: https://github.com/agronholm/typeguard
[vscode]: https://code.visualstudio.com/
[xdoctest]: https://github.com/Erotemic/xdoctest

<!-- features-end -->
