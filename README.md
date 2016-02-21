# clojure-maven

An example Clojure project that uses Maven instead of Leiningen.

## Installation

    $ git clone git@github.com:dainiusjocas/clojure-maven.git

## Usage

The `clojure-maven-plugin` is binded to Maven's compile and test phases.

Maven's `shade` plugin helps to create an 'uberjar'.

    $ mvn clean package
    $ java -cp target/mvn-project-0.1.0-SNAPSHOT.jar mvn_project.core
    $ java -jar mvn-project-0.1.0-standalone.jar [args]

## License

Copyright © 2016 FIXME

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
