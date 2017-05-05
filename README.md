mingus
======

mingus is a package for Python used by programmers, musicians, composers
and researchers to make and analyse music.

[Browse the documentation](http://bspaans.github.io/python-mingus/)

## TODO:

- update transpose
  - NoteContainer('A').transpose('m6')
    - right now it allows 'b6' or '#7' which is just dumb
    - it should take 'm6', 'M6', 'aug5', '+4', ...
  - fix related unit tests
  - the wierd shorthand should not be exposed to the user
- update unit tests for intervals
  - diminished fourth
  - augmented fifth
  - augmented sixth
  - diminished seventh
- update unit tests for chords
  - augmented sixth chords
    - german
    - french
    - italian
