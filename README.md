# hello-swearjure

[![Build Status](https://travis-ci.org/hyPiRion/hello-swearjure.png?branch=master)]
(https://travis-ci.org/hyPiRion/hello-swearjure)

`Hello, World!` application in Swearjure. Prints out `Hello, World!` in the
terminal window and exits.

hello-swearjure uses only 5 alphanumerical characters in the program itself on a
single line: `ns-map`. `project.clj` needs some more because Leiningen runs on
Clojure 1.5.1: 9 alphanumerical characters, 7 distinct ones. How hello-swearjure
works is explained at <http://www.hypirion.com/musings/hello-swearjure>.

## What is Swearjure?

Swearjure is Clojure code without alphanumerical characters (or with a very
limited amount of them). While one may think you can do very little with it, it
has a rather surprising amount of power.
[Swearjure — Clojure without alphanumerics][blogpost] describes the current
state of Swearjure, though this application uses some new inventions which will
be documented in the future. There has also been a [talk about Swearjure][talk],
done by Gary Fredericks ([@gfredericks_][gary]).

[talk]: http://upload.gfredericks.com/swearjure/talk.html
[blogpost]: http://hypirion.com/musings/swearjure
[gary]: https://twitter.com/gfredericks_

## Usage

As of now, you can run hello-swearjure by issuing the following command:

    $ lein run

*You must use Leiningen 2.1.0 or higher to run this program.* The program will
 otherwise crash, as it needs Leiningen to run on Clojure `1.5.x`.

For unknown reasons, it is currently impossible to make this program as a
standalone jar file. If you have attempted to do so, ensure you perform `lein
clean` before attempting to run the program again.

## License

Copyright © 2013 Jean Niklas L'orange

Distributed under the Eclipse Public License, the same as Clojure.
