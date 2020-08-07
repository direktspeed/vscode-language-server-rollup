# (WiP) vscode-language-server-rollup
A Rollup vscode-language-server for .mjs .cjs .js files.

## Concepts
typescript does lazy or lets say smart resolve files that algo is broken and not future proof.
rollup implements the most flexible userland resolve algorythm at present coupled with acorn as JS Parser

This is a dropin replacement for the typescript language server inside vscode 
later will produce typescript code hints and functions via plugin typescript.
