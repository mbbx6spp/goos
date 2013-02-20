# Evolving GOOS OO Java examples into more FP-ish Scala examples

For fun and profit!

The bookclub at work is reading Growing OO Software Guided By Tests (or
something) and since I am convinced the best way to grow OO software is to
make it more functional, I thought I would provide my own twist on this book
for coworkers :)

## Getting Started

Since my coworkers are mostly Ruby/Rails devs here is how to get started on
OS X (assuming you have Homebrew setup already and a reasonable JDK installed):

1. `brew update`
2. `brew install scala` or if you installed Scala a while ago `brew upgrade scala`
3. `brew install sbt` should be 0.12.2 or higher if not: `brew upgrade sbt`
4. `git clone https://github.com/mbbx6spp/goos.git`
5. `cd goos`
6. `sbt update`

If there is any code in here by the time you try it read through the code and
comments then you can `sbt compile` and `sbt test`.

## License

The initial Scala versions of the code will be fairly direct translations
of the Java examples in the GOOS book. This is so that readers can see the
transformation from OO to more FPish with possibly multiple transitions to
demonstrate various techniques.

The code I am writing will be released under the BSD 3-clause license where
I retain copyright.

The original Java code can be found in [goos-code](https://github.com/sf105/goos-code)
repository, which is released under the [Apache License, version 2.0](https://github.com/sf105/goos-code/blob/master/license.txt).

## Play

Feel free to fork and experiment on your own. That is the point of this
repository. If you do see actual bugs in my experiments, please submit
a PR from a branch in your own fork with the appropriate test to cover
the failure case.

Thanks!
