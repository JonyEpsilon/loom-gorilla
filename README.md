# loom-gorilla

A [Gorilla REPL](http://gorilla-repl.org) renderer for [loom](https://github.com/aysylu/loom) graphs.

## Usage

Add `[loom-gorilla "0.1.0"]` to the dependencies section of your `project.clj`. Then from within a Gorilla
worksheet `(use 'loom-gorilla.render)`. This provides a single function `loom-view`, which takes a loom
graph and the same options as `loom.io.view`.

See [this example worksheet](http://viewer.gorilla-repl.org/view.html?source=github&user=JonyEpsilon&repo=gorilla-test&path=ws/loom-test.clj)
for details.

## License

Copyright © 2014- Jony Hudson

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
