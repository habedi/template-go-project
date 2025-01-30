# A Template for Go Projects

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="assets/logo-v1.svg">
    <source media="(prefers-color-scheme: dark)" srcset="assets/logo-v1.svg">
    <img alt="template-go-project logo" src="assets/logo-v1.svg" height="40%" width="40%">
  </picture>
</div>
<br>

<p align="center">
  <a href="https://github.com/habedi/template-go-project/actions/workflows/tests.yml">
    <img alt="Tests" 
src="https://img.shields.io/github/actions/workflow/status/habedi/template-go-project/tests.yml?label=Tests&style=flat&
labelColor=555555&logo=github">
  </a>
  <a href="https://github.com/habedi/template-go-project/actions/workflows/build_linux.yml">
    <img alt="Linux Build" 
src="https://img.shields.io/github/actions/workflow/status/habedi/template-go-project/build_linux.yml?label=Linux%
20Build&style=flat&labelColor=555555&logo=linux">
  </a>
  <a href="https://github.com/habedi/template-go-project/actions/workflows/build_windows.yml">
    <img alt="Windows Build" 
src="https://img.shields.io/github/actions/workflow/status/habedi/template-go-project/build_windows.yml?label=Windows%
20Build&style=flat&labelColor=555555&logo=github">
  </a>
  <a href="https://github.com/habedi/template-go-project/actions/workflows/build_macos.yml">
    <img alt="MacOS Build" 
src="https://img.shields.io/github/actions/workflow/status/habedi/template-go-project/build_macos.yml?label=MacOS%
20Build&style=flat&labelColor=555555&logo=apple">
  </a>
  <br>
  <a href="https://goreportcard.com/report/github.com/habedi/template-go-project">
    <img alt="Go Report Card" 
src="https://img.shields.io/badge/Go%20Report-Check-007ec6?style=flat&labelColor=555555&logo=go">
  </a>
  <a href="https://pkg.go.dev/github.com/habedi/template-go-project">
    <img alt="Go Reference" 
src="https://img.shields.io/badge/Go%20Reference-Docs-3776ab?style=flat&labelColor=555555&logo=go">
  </a>
  <a href="https://codecov.io/gh/habedi/template-go-project">
    <img alt="Code Coverage" 
src="https://img.shields.io/codecov/c/github/habedi/template-go-project?style=flat&labelColor=555555&logo=codecov">
  </a>
  <a href="https://www.codefactor.io/repository/github/habedi/template-go-project">
    <img alt="CodeFactor" 
src="https://img.shields.io/codefactor/grade/github/habedi/template-go-project?style=flat&labelColor=555555&logo=
codefactor">
  </a>
  <br>
  <a href="docs">
    <img alt="Docs" src="https://img.shields.io/badge/docs-latest-3776ab?style=flat&labelColor=555555&logo=readthedocs">
  </a>
  <a href="LICENSE">
    <img alt="License" 
src="https://img.shields.io/badge/license-MIT-007ec6?style=flat&labelColor=555555&logo=open-source-initiative">
  </a>
  <a href="https://github.com/habedi/template-go-project/releases/latest">
    <img alt="Release" 
src="https://img.shields.io/github/release/habedi/template-go-project.svg?style=flat&labelColor=555555&logo=github">
  </a>
  <a href="https://github.com/habedi/template-go-project/releases">
    <img alt="Total Downloads" 
src="https://img.shields.io/github/downloads/habedi/template-go-project/total.svg?style=flat&labelColor=555555&logo=
github">
  </a>
</p>

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

Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to make a contribution.

## License

This project is licensed under the MIT License ([LICENSE-MIT](LICENSE-MIT) or https://opensource.org/licenses/MIT)
