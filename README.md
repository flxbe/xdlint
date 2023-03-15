# xdlint

[![CI](https://github.com/flxbe/xdlint/actions/workflows/test.yml/badge.svg)](https://github.com/flxbe/xdlint/actions/workflows/test.yml)

A linter for the [XÖV](https://www.xoev.de/)-standard [XDatenfelder](https://www.xrepository.de/details/urn:xoev-de:fim:standard:xdatenfelder).

## Getting Started

Either use the linter directly via `npx`:

```txt
npx xdlint [options] <path>
```

Or install it:

```sh
npm install -g xdlint
```

The linter should now be available globally:

```txt
xdlint [options] <path>
```

## Options

You can view all options by running `xdlint -h`.

```txt
Usage: xdlint [options] <path>

A linter for XDatenfelder v2.0.

Arguments:
  path           path to a folder or a XDatenfelder .xml file

Options:
  -V, --version  output the version number
  -s, --strict   fail not only for errors but also for warnings
  -h, --help     display help for command
```
