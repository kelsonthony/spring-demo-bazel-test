#Commands

bazel clean --expunge
bazel sync --configure
bazel build //...
bazel run project or 
bazel run projects/java_greeter/src/main/java/com/kelsonthony/javagreeter/hello

Run java project

bazel run projects/java_greeter/src/main/java/com/kelsonthony/javagreeter/hello

For java project with external resources

https://github.com/bazelbuild/rules_jvm_external

bazel query @maven//...

bazel run @maven//:pin

bazel run @unpinned_maven//:pin

bazel run //demobazel/src/main/java/com/kelsonthony/demobazel/demobazel:app