
# cikit — Python CI Toolkit

**cikit** is a lightweight Python toolkit for building reusable local
development and continuous integration workflows. It replaces large
shell scripts and provider-specific pipeline logic with composable
Python commands and helpers.

> [!IMPORTANT]
> **The project is developed and maintained on GitLab.**
> This GitHub repository is a reference page for discovery, not a
> source code mirror. For the latest source code, releases, issues,
> and contributions, visit the official GitLab repository.

**[Source code and project on GitLab](https://gitlab.com/svesch/cikit)**

**[Documentation](https://cikit-a4de14.gitlab.io/)**

## Features

- Reusable CI commands with support for installed providers and
  project-local overrides
- Consistent execution locally, in GitLab CI, and in Azure DevOps
- Helpers for Ruff, Pylint, pytest, coverage, CMake, CTest,
  PlatformIO, and Sphinx
- Structured build and test metrics, reports, and artifact management
- Historical metrics and configurable SVG timeline charts
- Sphinx integration for metrics, charts, logs, and artifact metadata

## Installation

Requires Python 3.12 or newer.

```bash
pip install cikit
```

See the [official documentation](https://cikit-a4de14.gitlab.io/)
for setup, examples, and usage.

## Project Links

- **Source code:** [GitLab repository](https://gitlab.com/svesch/cikit)
- **Documentation:** [Online documentation](https://cikit-a4de14.gitlab.io/)
- **Issues and contributions:** [GitLab](https://gitlab.com/svesch/cikit)

## License

GPL-3.0-or-later.

See the official GitLab repository for the project license and source files.
