# Syntax analysis - Emacs minor mode

This package highlights nouns, verb, adjectives etc. in English prose
to help with authoring. It is a wrapper around the OSX program [syn](https://github.com/stephencelis/syn)
and takes inspiration from [iA Writer Pro](http://writer.pro/).

## Usage:

- M-x wordsmith-mode
- pre-defined shortcuts:
* C-c w n : highlight nouns in buffer
* C-c w v : highlight verbs in buffer
* C-c w w : ido menu to pick which attribute to highlight
* C-c w k : disable wordsmith highlighting in buffer
- M-x wordsmith-mode again to disable mode

## Compatibility

This emacs package currently only works under OSX.
Please install 'syn' first (see instructions at https://github.com/stephencelis/syn).

## Feedback

This is my first emacs package. Feedback and contributions are very welcome

## Screencast
![mini-screencast](wordsmith-screencast.gif)
