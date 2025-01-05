# Template Repository for Go Packages

[![Tests](https://github.com/habedi/template-go-package/actions/workflows/tests.yml/badge.svg)](https://github.com/habedi/template-go-package/actions/workflows/tests.yml)
[![Go Report Card](https://goreportcard.com/badge/github.com/habedi/template-go-package)](https://goreportcard.com/report/github.com/habedi/template-go-package)
[![Go Reference](https://pkg.go.dev/badge/github.com/habedi/template-go-package.svg)](https://pkg.go.dev/github.com/habedi/template-go-package)
[![License](https://img.shields.io/github/license/habedi/template-go-package)](https://github.com/habedi/template-go-package/blob/main/LICENSE)

This is a template repository to make it easier to start developing Go packages.
It includes a basic structure for a Go package plus some additional useful files like GitHub Actions for running unit
tests.

I made this template to have a starting point for my Go packages and to speed up the development process. I hope it will
be useful for you as well. Feel free to use it for your projects as is or modify it to fit your needs.

## Files

These files are included in the repository:

- `.github/workflows/tests.yml`: GitHub Actions workflow for running the unit tests.
- `.editorconfig`: Editor configuration file for consistent coding styles.
- `.gitignore`: A gitignore file for Go projects.
- `go.mod`: Go module file.
- `LICENSE`: License file.
- `README.md`: Readme file.
- `package.go`: Package file which includes the package code.
- `package_test.go`: Unit tests for the functions in the package file.
