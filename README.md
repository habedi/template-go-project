# A Template for Go Projects

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="assets/logo-v1.svg">
    <source media="(prefers-color-scheme: dark)" srcset="assets/logo-v1.svg">
    <img alt="template-go-project logo" src="assets/logo-v1.svg" height="40%" width="40%">
  </picture>
</div>
<br>

[![Tests](https://img.shields.io/github/actions/workflow/status/habedi/template-go-project/tests.yml?label=tests&style=flat&labelColor=555555&logo=github)](https://github.com/habedi/template-go-project/actions/workflows/tests.yml)
[![Lints](https://img.shields.io/github/actions/workflow/status/habedi/template-go-project/lints.yml?label=linters&style=flat&labelColor=555555&logo=github)](https://github.com/habedi/template-go-project/actions/workflows/lints.yml)
[![Linux Build](https://img.shields.io/github/actions/workflow/status/habedi/template-go-project/build_linux.yml?label=linux%20build&style=flat&labelColor=555555&logo=linux)](https://github.com/habedi/template-go-project/actions/workflows/build_linux.yml)
[![Windows Build](https://img.shields.io/github/actions/workflow/status/habedi/template-go-project/build_windows.yml?label=windows%20build&style=flat&labelColor=555555&logo=github)](https://github.com/habedi/template-go-project/actions/workflows/build_windows.yml)
[![MacOS Build](https://img.shields.io/github/actions/workflow/status/habedi/template-go-project/build_macos.yml?label=macos%20build&style=flat&labelColor=555555&logo=apple)](https://github.com/habedi/template-go-project/actions/workflows/build_macos.yml)
<br>
[![Go Version](https://img.shields.io/github/go-mod/go-version/habedi/template-go-project?label=minimum%20go%20version&style=flat&labelColor=555555&logo=go)](go.mod)
[![Go Report Card](https://img.shields.io/badge/Go%20Report-Check-007ec6?label=go%20report%20card&style=flat&labelColor=555555&logo=go)](https://goreportcard.com/report/github.com/habedi/template-go-project)
[![Go Reference](https://img.shields.io/badge/Go%20Reference-Docs-3776ab?label=go%20reference&style=flat&labelColor=555555&logo=go)](https://pkg.go.dev/github.com/habedi/template-go-project)
[![Release](https://img.shields.io/github/release/habedi/template-go-project.svg?label=release&style=flat&labelColor=555555&logo=github)](https://github.com/habedi/template-go-project/releases/latest)
[![Total Downloads](https://img.shields.io/github/downloads/habedi/template-go-project/total.svg?label=downloades&style=flat&labelColor=555555&logo=github)](https://github.com/habedi/template-go-project/releases)
<br>
[![Code Coverage](https://img.shields.io/codecov/c/github/habedi/template-go-project?label=coverage&style=flat&labelColor=555555&logo=codecov)](https://codecov.io/gh/habedi/template-go-project)
[![CodeFactor](https://img.shields.io/codefactor/grade/github/habedi/template-go-project?label=code%20quality&style=flat&labelColor=555555&logo=codefactor)](https://www.codefactor.io/repository/github/habedi/template-go-project)
[![Docs](https://img.shields.io/badge/docs-latest-3776ab?label=docs&style=flat&labelColor=555555&logo=readthedocs)](docs)
[![License](https://img.shields.io/badge/license-MIT-007ec6?label=license&style=flat&labelColor=555555&logo=open-source-initiative)](https://github.com/habedi/template-go-project)

This is a template repository with a minimalistic structure to make it easier to start a new Go project.
It is inspired by the recommendations
in [golang-standards/project-layout](https://github.com/golang-standards/project-layout).
I share it here in case it might be useful to others.

## Features

- Minimalistic project structure
- Pre-configured GitHub Actions for testing, building, and releasing
- Makefile for managing common tasks such as formatting, testing, and linting
- Example configuration files for popular tools like `golangci-lint`
- GitHub badges for tests, builds, code quality and coverage, documentation, etc.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to make a contribution.

## License

This project is licensed under the MIT License ([LICENSE](LICENSE) or https://opensource.org/licenses/MIT)
