# Syntax analysis - Emacs minor mode


This Emacs packages provides syntax highlighting (nouns, verb, adverbs...) in English text.

It is a wrapper around the OSX program [syn](https://github.com/stephencelis/syn), which itself leverages
functionality of [MacOSX's natural language processing tools](https://developer.apple.com/library/mac/documentation/cocoa/reference/NSLinguisticTagger_Class/Reference/Reference.html)
and takes inspiration from [iA Writer Pro](http://writer.pro/).

## Usage:

- M-x wordsmith-mode
- pre-defined shortcuts:
* C-c w n : highlight nouns in buffer
* C-c w v : highlight verbs in buffer
* C-c w w : ido menu to pick which attribute to highlight
* C-c w k : disable wordsmith highlighting in buffer

## Compatibility

This emacs package currently only works under OSX.
Please install 'syn' first (see instructions at https://github.com/stephencelis/syn).

## Feedback

This is my first emacs package. Feedback and contributions are very welcome

## Screencast
![mini-screencast](wordsmith-screencast.gif)
