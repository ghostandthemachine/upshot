# Upshot

**WARNING: THIS IS NOT MERELY EXPERIMENTAL. IT IS REALLY MOST SINCERELY EXPERIMENTAL!**

A [Seesaw](https://github.com/daveray/seesaw) style Clojure API for [JavaFX](http://javafx.com).

## Usage
JavaFX isn't in Maven and, as a special bonus, has native deps. So, you'll need to unpack the JavaFX distribution somewhere and then do some setup whenever you play with Upshot:

  export JAVAFX_HOME="/Users/dave/Apps/javafx-sdk2.1.0-beta"
  source javafx.env.sh

  # do this only once. It installs JavaFX in your local maven repo.
  ./setup.sh
  lein deps

  # Now run the example (test/upshot/test/examples/example.clj)
  lein run -m upshot.test.examples.example

## License

Copyright (C) 2012 Dave Ray

Distributed under the Eclipse Public License, the same as Clojure.
