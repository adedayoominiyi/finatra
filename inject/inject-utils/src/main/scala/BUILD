scala_library(
    sources = ["**/*.scala"],
    compiler_option_sets = ["fatal_warnings"],
    provides = scala_artifact(
        org = "com.twitter",
        name = "inject-utils",
        repo = artifactory,
    ),
    tags = [
        "bazel-compatible",
        "known-jdk11-failure:CSL-11503",
    ],
    dependencies = [
        "3rdparty/jvm/com/github/nscala_time",
        "3rdparty/jvm/javax/xml/bind:jaxb-api",
        "3rdparty/jvm/joda-time",
        "3rdparty/jvm/org/slf4j:slf4j-api",
        "finagle/finagle-core/src/main",
        "finatra/inject/inject-core/src/main/scala/com/twitter/inject",
        "util/util-core:scala",
        "util/util-slf4j-api/src/main/scala/com/twitter/util/logging",
    ],
    exports = [
        "3rdparty/jvm/com/github/nscala_time",
        "util/util-slf4j-api/src/main/scala/com/twitter/util/logging",
    ],
)
