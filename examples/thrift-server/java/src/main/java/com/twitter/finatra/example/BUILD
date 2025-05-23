java_library(
    sources = ["**/*.java"],
    compiler_option_sets = ["fatal_warnings"],
    tags = ["bazel-compatible"],
    dependencies = [
        "3rdparty/jvm/com/google/inject:guice",
        "3rdparty/jvm/javax/inject:javax.inject",
        "finagle/finagle-thriftmux/src/main/scala",
        "finatra/examples/thrift-server/idl/src/main/thrift:thrift-java",
        "finatra/inject/inject-core/src/main/scala",
        "finatra/inject/inject-server/src/main/scala/com/twitter/inject/server",
        "finatra/thrift/src/main/scala/com/twitter/finatra/thrift",
        "finatra/thrift/src/main/scala/com/twitter/finatra/thrift:controller",
        "finatra/thrift/src/main/scala/com/twitter/finatra/thrift/exceptions",
        "finatra/thrift/src/main/scala/com/twitter/finatra/thrift/filters",
        "finatra/thrift/src/main/scala/com/twitter/finatra/thrift/modules",
        "finatra/thrift/src/main/scala/com/twitter/finatra/thrift/response",
        "finatra/thrift/src/main/scala/com/twitter/finatra/thrift/routing",
        "twitter-server/server/src/main/scala",
        "util/util-app/src/main/scala",
        "util/util-slf4j-api/src/main/scala/com/twitter/util/logging",
    ],
)

jvm_binary(
    name = "bin",
    basename = "java-thrift-server",
    main = "com.twitter.finatra.example.CalculatorServerMain",
    tags = ["bazel-compatible"],
    dependencies = [
        ":example",
        "finatra/examples/thrift-server/java/src/main/resources",
        "twitter-server/logback-classic/src/main/scala",
    ],
)
