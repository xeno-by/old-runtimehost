### Runtime reflection host

Runtime reflection host for [Project Palladium](http://scalamacros.org/news/2014/03/02/project-palladium.html) provides
an environment that can host Project Palladium macros using runtime reflection facilities. Key components of the runtime
are [AST persistence](https://github.com/scalareflect/persistence) and [AST interpretation](https://github.com/scalareflect/interpreter)
technologies. This project is part of the [Mars](https://github.com/scalareflect/mars) project. Design notes can be found in the
[Runtime Expansion](https://docs.google.com/document/d/1iUL6Rcea04K68lFWlj9n-A_29pFNMo8uPH-H2kwx8Sg/edit) document
at [Palladium Shared](https://drive.google.com/#folders/0Bxbd8B9L-XfmcE9tRFBXVjZtY0k).

### How to use

The project is in a very early stage, so it's not supposed to be useful just yet. However, if you're brave enough, we have a nightly build that publishes artifacts to Sonatype at `"org.scalareflect" % "runtimehost_2.11.0-RC3" % "0.1.0-SNAPSHOT"`.
