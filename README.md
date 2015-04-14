# My experimental Emacs config

## Organization

[`init.el`](./init.el) acts as a kind of table of contents.
It's a good idea to eventually go through `init.el` and the
files under the `customizations` directory so that you know exactly
what's going on.

    customizations/
    ├── editing.el
    ├── elisp-editing.el
    ├── misc.el
    ├── navigation.el
    ├── setup-clojure.el
    ├── setup-js.el
    ├── shell-integration.el
    └── ui.el

## Supporting CSS, HTML, JS, etc.
* [Customizes js-mode and html editing](https://github.com/flyingmachine/emacs.d/blob/master/customizations/setup-js.el)
    * Sets indentation level to 2 spaces for JS
    * enables subword-mode so that M-f and M-b break on capitalization changes
    * Uses `tagedit` to give you paredit-like functionality when editing html
    * adds support for coffee mode
* Adds support for YAML and SCSS using the yaml-mode and scss-mode packages

## Supporting Clojure
* Cider REPL smartness

## Package dependencies
* paredit
* clojure-mode
* clojure-mode-extra-font-locking
* scss-mode
* cider
* ido-ubiquitous
* smex
* projectile
* rainbow-delimiters
* tagedit
* magit

## References
If you're new to emacs, check out
[this introductory tutorial](http://www.braveclojure.com/basic-emacs/)!
