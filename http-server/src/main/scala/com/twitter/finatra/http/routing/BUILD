scala_library(
    sources = ["*.scala"],
    compiler_option_sets = ["fatal_warnings"],
    provides = scala_artifact(
        org = "com.twitter",
        name = "finatra-http-routing",
        repo = artifactory,
    ),
    strict_deps = True,
    tags = ["bazel-compatible"],
    dependencies = [
        "3rdparty/jvm/javax/inject:javax.inject",
        "finagle/finagle-base-http/src/main",
        "finatra/http-core/src/main/scala/com/twitter/finatra/http/exceptions",
        "finatra/http-core/src/main/scala/com/twitter/finatra/http/request",
        "finatra/http-server/src/main/scala/com/twitter/finatra/http:controller",
        "finatra/http-server/src/main/scala/com/twitter/finatra/http/internal/routing",
        "finatra/inject/inject-core/src/main/scala/com/twitter/inject",
        "finatra/inject/inject-core/src/main/scala/com/twitter/inject/internal",
        "twitter-server/server/src/main/scala",
        "util/util-core:util-core-util",
        "util/util-jackson/src/main/scala/com/twitter/util/jackson",
        "util/util-slf4j-api/src/main/scala/com/twitter/util/logging",
    ],
    exports = [
        "3rdparty/jvm/javax/inject:javax.inject",
        "finagle/finagle-base-http/src/main",
        "finatra/http-server/src/main/scala/com/twitter/finatra/http:controller",
        "twitter-server/server/src/main/scala",
        "util/util-core:util-core-util",
        "util/util-slf4j-api/src/main/scala/com/twitter/util/logging",
    ],
)
