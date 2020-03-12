# vscode-mosaic

This is an extremely basic Mosaic syntax highlighter for Visual Studio Code. It uses code and ideas from both [the Prisma Visual Studio Code extension](https://github.com/prisma/vscode) and [the Felix Atom extension](https://github.com/felix-lang/felix-atom-editor).

This is not a particularly refined syntax highlighter, so there will likely be issues. I have little experience writing regexes and leaned heavily on the prior two examples for help with getting the basics right. I have also simply borrowed the numeric regex from the latter.

Notable missing features include:

* Syntax highlighting for variables.
* Syntax highlighting for user-defined records and types in declarations.
* Proper automatic closing statements for `if` and `do` blocks.

Despite that, this should at least be a good start. Improvements will be ongoing as I find time.

You can find more info about Mosaic [here](https://github.com/sal55/langs/tree/master/Mosaic) and [here](https://github.com/sal55/langs/blob/master/mfeatures.md).