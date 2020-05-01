gocredits
=======

> Forked from original project https://github.com/Songmu/gocredits

[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)][license]
[![GoDoc](https://godoc.org/github.com/harshavardhana/gocredits?status.svg)][godoc]

[license]: https://github.com/harshavardhana/gocredits/blob/master/LICENSE
[godoc]: https://godoc.org/github.com/harshavardhana/gocredits

gocredits creates CREDITS file from LICENSE files of dependencies

## Synopsis

```console
gocredits . > CREDITS
```

## Description

When distributing built executable in Go, we need to include LICENSE of the dependent
libraries into the package, so gocredits bundle them together as a CREDITS file.

To use `gocredits`, we should use go modules for dependency management.

## Installation

### go get

```console
% go get github.com/harshavardhana/gocredits/cmd/gocredits
```

Built binaries are available on GitHub Releases.
<https://github.com/harshavardhana/gocredits/releases>
