# Syntax analysis - Emacs minor mode


This Emacs packages provides syntax highlighting (nouns, verb, adverbs...) in English text.

It is a wrapper around the OSX program [syn](https://github.com/stephencelis/syn), which itself leverages
functionality of [MacOSX's natural language processing tools](https://developer.apple.com/library/mac/documentation/cocoa/reference/NSLinguisticTagger_Class/Reference/Reference.html)
and takes inspiration from [iA Writer Pro](http://writer.pro/).

## Usage:

* enable via `M-x wordsmith-mode'

* shortcuts:

    > C-c w n : highlight nouns in buffer

    > C-c w v : highlight verbs in buffer

    > C-c w w : ido menu to pick an attribute to highlight

    > C-c w k : disable wordsmith highlighting in buffer

* currently, you need to manually re-run the command for it to update when the buffer has changed.

## Installation

Install [syn](https://github.com/stephencelis/syn) first (requires OSX 10.7+) via shell:

```
curl -Ls https://github.com/stephencelis/syn/releases/download/v0.2.1/syn > syn && chmod 755 syn && mv syn /usr/local/bin
```

Then install the wordsmith Emacs package using [melpa](http://melpa.milkbox.net/#/):

```
M-x package-install RET wordsmith-mode RET
```

## Screencast

![mini-screencast](wordsmith-screencast.gif)
