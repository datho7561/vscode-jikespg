# vscode-jikespg

TextMate grammar (syntax highlighting) and VS Code extension for [jikespg](https://github.com/daveshields/jikespg), the compiler compiler used by Eclipse JDT.

As with many TextMate grammars, this is a series of hacks meant to perform a "best effort" syntax highlighting.
It doesn't actually parse the grammar definition file,
so it may colour some constructs incorrectly.

### Assumptions
- The default `BLOCKB` (`/.`), `BLOCKE` (`./`), and `ESCAPE` (`$`) are used.
  jikespg allows you to configure these in `%options`, but the TextMate grammar cannot adapt to this.

