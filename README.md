# Scilla Mode for Emacs

Provides support for font-lock, indentation, type-checking for the
[Scilla](https://scilla-lang.org) programming language.

## Installation

Add the following line to your `.emacs` file to load this mode for files ending
with `.scilla` and `.scillib`.

```elisp
;; For enabling flycheck mode for Scilla.
(setq scilla-root "/path/to/scilla/root")
;; Scilla mode
(load-file "/path/to/scilla-mode.el")
```

To enable `scilla-checker` (Scilla typechecker) for editing Scilla files,
install Flycheck for Emacs. See installation instructions
[here](http://www.flycheck.org/en/latest/user/installation.html).

