# clerk-mode

An Emacs minor mode for presenting files in [Clerk](https://github.com/nextjournal/clerk)

## Usage

Place `clerk-mode.el` on your Emacs load path and then add the following to your `init.el`

```elisp
(require 'clerk-mode)

(add-hook 'clojure-mode #'clerk-mode)
```
