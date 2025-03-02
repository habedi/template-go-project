## Go Project Template

<div align="center">
  <picture>
    <img alt="Template Go Project Logo" src="assets/logo-v1.svg" height="35%" width="35%">
  </picture>
</div>
<br>

[![Tests](https://img.shields.io/github/actions/workflow/status/habedi/template-go-project/tests.yml?label=tests&style=flat&labelColor=282c34&color=4caf50&logo=github)](https://github.com/habedi/template-go-project/actions/workflows/tests.yml)
[![Lints](https://img.shields.io/github/actions/workflow/status/habedi/template-go-project/lints.yml?label=lints&style=flat&labelColor=282c34&color=4caf50&logo=github)](https://github.com/habedi/template-go-project/actions/workflows/lints.yml)
[![Linux Build](https://img.shields.io/github/actions/workflow/status/habedi/template-go-project/build_linux.yml?label=linux%20build&style=flat&labelColor=282c34&color=4caf50&logo=linux)](https://github.com/habedi/template-go-project/actions/workflows/build_linux.yml)
[![Windows Build](https://img.shields.io/github/actions/workflow/status/habedi/template-go-project/build_windows.yml?label=windows%20build&style=flat&labelColor=282c34&color=4caf50&logo=github)](https://github.com/habedi/template-go-project/actions/workflows/build_windows.yml)
[![MacOS Build](https://img.shields.io/github/actions/workflow/status/habedi/template-go-project/build_macos.yml?label=macos%20build&style=flat&labelColor=282c34&color=4caf50&logo=apple)](https://github.com/habedi/template-go-project/actions/workflows/build_macos.yml)
<br>
[![Go Version](https://img.shields.io/github/go-mod/go-version/habedi/template-go-project?label=min%20go%20version&style=flat&labelColor=282c34&color=007ec6&logo=go)](go.mod)
[![Go Report Card](https://img.shields.io/badge/Go%20Report-Check-007ec6?label=go%20report%20card&style=flat&labelColor=282c34&logo=go)](https://goreportcard.com/report/github.com/habedi/template-go-project)
[![Go Reference](https://img.shields.io/badge/Go%20Reference-Docs-007ec6?label=go%20reference&style=flat&labelColor=282c34&logo=go)](https://pkg.go.dev/github.com/habedi/template-go-project)
[![Release](https://img.shields.io/github/release/habedi/template-go-project.svg?label=release&style=flat&labelColor=282c34&color=f46623&logo=github)](https://github.com/habedi/template-go-project/releases/latest)
[![Total Downloads](https://img.shields.io/github/downloads/habedi/template-go-project/total.svg?label=downloads&style=flat&labelColor=282c34&color=8caf50&logo=github)](https://github.com/habedi/template-go-project/releases)
<br>
[![Code Coverage](https://img.shields.io/codecov/c/github/habedi/template-go-project?label=coverage&style=flat&labelColor=282c34&color=ffca28&logo=codecov)](https://codecov.io/gh/habedi/template-go-project)
[![CodeFactor](https://img.shields.io/codefactor/grade/github/habedi/template-go-project?label=code%20quality&style=flat&labelColor=282c34&color=4caf50&logo=codefactor)](https://www.codefactor.io/repository/github/habedi/template-go-project)
[![Docs](https://img.shields.io/badge/docs-latest-007ec6?label=docs&style=flat&labelColor=282c34&logo=readthedocs)](docs)
[![License](https://img.shields.io/badge/license-MIT-007ec6?label=license&style=flat&labelColor=282c34&logo=open-source-initiative)](https://github.com/habedi/template-go-project)

This is a generic project template for Go projects.
It provides a minimalistic project structure with pre-configured GitHub Actions, Makefile,
and example configuration files for a few popular development tools.
It is inspired by the recommendations
in [golang-standards/project-layout](https://github.com/golang-standards/project-layout).
I share it here in case it might be useful to others.

### Features

- Minimalistic project structure
- Pre-configured GitHub Actions for testing, building the binaries, and linting
- Makefile for managing the development workflow and tasks like formatting, testing, linting, etc.
- Example configuration files for popular tools like `golangci-lint`
- GitHub badges for tests, builds, code quality and coverage, documentation, etc.
- GitHub release workflow for creating releases and publishing binaries
- [Code of Conduct](CODE_OF_CONDUCT.md) and [Contributing Guidelines](CONTRIBUTING.md)

### Getting Started

Check out the [Makefile](Makefile) for available commands to manage the development workflow of the project.

```shell
# Install system dependencies (Go and GNU Make)
sudo apt install golang-go make
```

```shell
# See all available commands and their descriptions
make help
```

### Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to make a contribution.

### License

This project is licensed under the MIT License ([LICENSE](LICENSE) or https://opensource.org/licenses/MIT)
