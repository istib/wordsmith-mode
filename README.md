# Syntax analysis - Emacs minor mode


This Emacs packages provides syntax highlighting (nouns, verb, adverbs...) in English text.

It is a wrapper around the OSX program [syn](https://github.com/stephencelis/syn), which itself leverages
functionality of [MacOSX's natural language processing tools](https://developer.apple.com/library/mac/documentation/cocoa/reference/NSLinguisticTagger_Class/Reference/Reference.html)
and takes inspiration from [iA Writer Pro](http://writer.pro/).

## Usage:

* M-x wordsmith-mode
* shortcuts:

    > C-c w n : highlight nouns in buffer

    > C-c w v : highlight verbs in buffer

    > C-c w w : ido menu to pick an attribute to highlight

    > C-c w k : disable wordsmith highlighting in buffer

- currently, you need to manually re-run the command for it to update when the buffer has changed.

## Installation

Please install the OSX tool `syn' first (see instructions at https://github.com/stephencelis/syn).

You can then install the package using [melpa](http://melpa.milkbox.net/#/):

```
M-x package-install RET wordsmith-mode RET
```

## Compatibility

This emacs package currently only works under OSX.


## Screencast
![mini-screencast](wordsmith-screencast.gif)
