#Commands

bazel clean --expunge

bazel sync --configure

bazel build //...

bazel query @maven//...

bazel run @maven//:pin

bazel run @unpinned_maven//:pin

bazel run //demobazel/src/main/java/com/kelsonthony/demobazel/demobazel:app
