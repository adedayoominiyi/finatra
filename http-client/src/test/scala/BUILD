junit_tests(
    sources = ["com/twitter/finatra/httpclient/*.scala"],
    tags = ["bazel-compatible"],
    dependencies = [
        ":test-deps",
        "3rdparty/jvm/com/fasterxml/jackson/core:jackson-databind",
        "3rdparty/jvm/com/fasterxml/jackson/datatype:jackson-datatype-joda",
        "3rdparty/jvm/com/fasterxml/jackson/module:jackson-module-scala",
        "3rdparty/jvm/com/google/inject:guice",
        "3rdparty/jvm/com/google/inject/extensions:guice-assistedinject",
        "3rdparty/jvm/com/google/inject/extensions:guice-testlib",
        "3rdparty/jvm/junit",
        "3rdparty/jvm/net/codingwell:scala-guice",
        "3rdparty/jvm/org/scalatest",
        "3rdparty/jvm/org/scalatestplus:junit",
        "3rdparty/jvm/org/slf4j:slf4j-api",
        scoped(
            "3rdparty/jvm/org/slf4j:slf4j-simple",
            scope = "runtime",
        ),
        "finagle/finagle-core/src/main",
        "finagle/finagle-http/src/main/scala",
        "finatra/http-client/src/main/scala",
        "finatra/http-client/src/test/resources",
        "finatra/inject/inject-app/src/test/scala/com/twitter/inject/app",
        "finatra/inject/inject-core/src/main/scala",
        "finatra/inject/inject-core/src/test/scala/com/twitter/inject",
        "finatra/jackson/src/main/scala/com/twitter/finatra/jackson/modules",
        "twitter-server/server/src/main/scala",
        "util/util-core:scala",
        "util/util-jackson/src/main/scala/com/twitter/util/jackson",
        "util/util-mock/src/main/scala/com/twitter/util/mock",
        "util/util-slf4j-api/src/main/scala",
    ],
)

scala_library(
    name = "test-deps",
    sources = ["com/twitter/finatra/httpclient/test/*.scala"],
    compiler_option_sets = ["fatal_warnings"],
    provides = scala_artifact(
        org = "com.twitter",
        name = "finatra-httpclient-tests",
        repo = artifactory,
    ),
    tags = ["bazel-compatible"],
    dependencies = [
        "3rdparty/jvm/org/slf4j:slf4j-api",
        "finagle/finagle-core/src/main",
        "finagle/finagle-http/src/main/scala",
        "finatra/inject/inject-app/src/test/scala/com/twitter/inject/app",
        "finatra/inject/inject-core/src/main/scala/com/twitter/inject",
        "finatra/inject/inject-core/src/test/scala/com/twitter/inject",
        "util/util-core:scala",
        "util/util-slf4j-api/src/main/scala/com/twitter/util/logging",
    ],
)
