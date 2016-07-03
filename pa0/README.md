# Description
In the folder `src/main/scala` look for the package `example` and edit
the file `Lists.scala`. There are two methods in this file that need to be
implemented (`sum` and `max`).
## Running and Testing Code
In the sbt console, start the Scala REPL by typing *console*.

    > console
    [info] Starting scala interpreter...

    scala>
The classes of the assignment are available inside the REPL, so you can
for instance import all the methods from object *Lists*:

    scala> import example.Lists._
    import example.Lists._

    scala> max(List(1,3,2))
    res1: Int = 3
We will be using the `ScalaTest` testing framework to write our unit
tests. In eclipse, navigate to the folder `src/test/scala` and open the
file `ListsSuite.scala` in package `example`. This file contains a
step-by-step tutorial to learn how to write and execute `ScalaTest` unit
tests.
