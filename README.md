# SmPL Syntax for Sublime Text

This is syntax definition for SmPL (semantic patch) language used by the [Coccinelle] tool.

I [converted] it from [John Gardner]’s [Atom syntax].

## Installation

You can install this package using [Package Control](https://packagecontrol.io/installation) using the name “SmPL”.

For development, you will want to clone the repository into “SmPL” directory in the Sublime Text’s `Packages` directory (`Preferences` → `Browse Packages…`):

```
git clone git@github.com:jtojnar/Sublime-SmPL-Syntax.git SmPL
```

(Or create a symlink with such name from your projects directory.)

## Usage

After installation, the syntax should automatically apply to files with `.cocci` extension.

## Useful links

- [Grammar](https://coccinelle.gitlabpages.inria.fr/website/docs/main_grammar.html)
- [Testing](https://www.sublimetext.com/docs/syntax.html#testing)

[Coccinelle]: https://coccinelle.gitlabpages.inria.fr/website/
[converted]: https://forum.sublimetext.com/t/using-syntax-highlighting-from-github-atom/65023
[Atom syntax]: https://github.com/Alhadis/language-etc/blob/669f7b1ca0d1a37bf63754b9df7c53bd89ba4fd9/grammars/smpl.cson
[John Gardner]: https://github.com/Alhadis
