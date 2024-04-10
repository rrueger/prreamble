## Prreamble

A LaTeX preamble package useful for compiling mathematics.

### How to use

(Locally)

1. Copy the `.sty` file to a directory of your choosing.
2. Export the `$TEXMFHOME` variable in your shell to that directory.
   (e.g. by adding `export TEXMFHOME=/path/to/dir` to your `~/.bashrc`)
3. Include the package in your LaTeX source file with `\usepackage{prreamble}`
4. Pass options like you usually would e.g. `\usepackage[modern]{prreamble}`

(Overleaf)

I believe overleaf is clever, and automatically configures everything in the
background. Copy the `.sty` file into your project folder, and include it by
using `\usepackage{prreamble}` as you usually would.

**It is probably a good idea to pass the 'nomath' and 'noletters' options when
first experimenting with this package as not to create endless macro clashes.**

### Examples

The documentation (part of this repository) is compiled using `prreamble`,
however this is not particularly enlightening, because it is not mathematical
work.

[Here](https://doi.org/10.3929/ethz-b-000646162) is a thesis compiled using this package.

Also see the `samples` directory for some samples showcasing how the math is
typeset in the different versions.

### Typo in name?

Temporarily, I called this `prreamble` because it was a preamble for many of my
documents and my initials are `rr`.

Since then, I have not found a better name, so I left it at `prreamble`.

*"There is nothing more permanent than a temporary solution"*

If you have any better names, please tell me.
