# Zed TLA+

A [TLA+](https://github.com/tlaplus/tlaplus) extension for [Zed](https://zed.dev/).

## Features

- TLA+ syntax highlighting
- PlusCal syntax highlighting

## Status

This extension currently focuses on editor support for working with TLA+ and PlusCal in Zed. The main functionality available today is syntax highlighting.

## Roadmap
- [X] Basic syntac highlighting for `.tla` files
- [ ] TLA+ configuration file syntax highlighting  
  Requires a Tree-sitter grammar for `.cfg` files. See the discussion [here](https://github.com/tlaplus-community/tree-sitter-tlaplus/discussions/144).
- [ ] Language server integration  
  This depends on support via the [Language Server Protocol](https://microsoft.github.io/language-server-protocol/) as described [here](https://zed.dev/docs/extensions/languages#language-servers).
- [ ] Run the model checker from inside Zed
- [ ] Generate LaTeX and PDF output from inside Zed

## Installation

### From the Zed extensions marketplace

Search for **TLA+** in Zed's extensions view and install the extension.

### From source

Clone this repository and install via dev extension.

## Usage

Open any `.tla` file in Zed to get TLA+ syntax highlighting.

## Related Projects

If you want a more full featured TLA+ development environment today, take a look at [TLA+ for Visual Studio Code](https://github.com/tlaplus/vscode-tlaplus), which includes:

- syntax highlighting and snippets
- PlusCal translation support
- TLC model checking
- expression evaluation
- LaTeX and PDF generation
- code completion and formatting

This Zed extension aims to enable basic TLA+ editing experience in Zed and may grow toward some of those capabilities over time.

## Contributing

Contributions, bug reports, and suggestions are welcome.

Especially helpful areas include:

- improving the grammar and highlighting queries
- testing against real world TLA+ specifications
- experimenting with Zed language server integration
- exploring support for TLA+ `.cfg` files

## License

[MIT](LICENSE)
