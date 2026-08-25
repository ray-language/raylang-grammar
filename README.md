# raylang-grammar

TextMate grammar for the [raylang](https://github.com/ray-language/raylang)
programming language (`.ray`), extracted from the official raylang VS Code
extension so it can be consumed as a standalone dependency.

It is the grammar referenced by [github-linguist][linguist] to provide syntax
highlighting and language statistics for `.ray` files on GitHub.

- **Scope name:** `source.raylang`
- **File extension:** `.ray`
- **Grammar:** [`grammars/raylang.tmLanguage.json`](grammars/raylang.tmLanguage.json)
- **Editor config:** [`language-configuration.json`](language-configuration.json)

## License

MIT — see [`LICENSE`](LICENSE). This is one of the licenses accepted by
github-linguist for bundled grammars.

## Provenance

The grammar is maintained upstream in the raylang monorepo under
`editors/vscode/syntaxes/raylang.tmLanguage.json`; this repository mirrors it
verbatim for downstream consumers that need only the grammar.

[linguist]: https://github.com/github-linguist/linguist
