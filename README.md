# XO integration for emacs
This adds support for [XO](https://github.com/sindresorhus/xo) inside [emacs compilation mode](https://www.gnu.org/software/emacs/manual/html_node/emacs/Compilation-Mode.html).

# Requirements
- Having `xo` in your ```$PATH```

# Installation
Add melpa to your packages archive.

Then do ```M-x package-install``` and look for `xo`

# Usage
```M-x compile``` and then ```xo --compact myfile.js```
