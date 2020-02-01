# C-Escapes LaTeX Package

> Escape C-like escape sequences from your TeX.

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/urushiyama/cescapes)](https://github.com/urushiyama/cescapes/releases/latest)
[![LICENSE](https://img.shields.io/github/license/urushiyama/cescapes)](https://github.com/urushiyama/cescapes/tree/master/LICENSE)
[![Total Download of All Releases](https://img.shields.io/github/downloads/urushiyama/cescapes/total)](https://github.com/urushiyama/cescapes/releases)
[![Twitter Follow](https://img.shields.io/twitter/follow/YUrushiyama?style=social)](https://twitter.com/YUrushiyama)

## Abstract

This LaTeX Package escapes C-like escape sequences to be shown as plain text rather than LaTeX commands.

## Usage

First, copy `cescapes.sty` into your TeX directory.

```LaTeX
\usepackage{cescapes}
```
provides C-like escape sequences as LaTeX commands except overriding ones of default LaTeX commands.

```LaTeX
\usepackage[override]{cescapes}
```
overrides default LaTeX commands.

```LaTeX
\usepackage[regex]{cescapes}
```
provides not only C-like escape sequences but also Perl-like special sequences for regular expression (regex).

As same as C-like escape sequences, special sequences for regex can override default LaTeX commands by:
```LaTeX
\usepackage[regexoverride]{cescapes}
```

## Future work

- Overriding only in particular environments
- Semantic overriding

## Author

Yuta Urushiyama ([@YUrushiyama](https://twitter.com/YUrushiyama))

## License

[MIT License](/LICENSE)
