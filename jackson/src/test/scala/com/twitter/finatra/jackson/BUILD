junit_tests(
    sources = [
        "**/*.java",
        "**/*.scala",
    ],
    tags = ["bazel-compatible"],
    dependencies = [
        "3rdparty/jvm/com/fasterxml/jackson/core:jackson-annotations",
        "3rdparty/jvm/com/fasterxml/jackson/core:jackson-core",
        "3rdparty/jvm/com/fasterxml/jackson/core:jackson-databind",
        "3rdparty/jvm/com/fasterxml/jackson/datatype:jackson-datatype-joda",
        "3rdparty/jvm/com/fasterxml/jackson/module:jackson-module-scala",
        "3rdparty/jvm/com/github/nscala_time",
        "3rdparty/jvm/com/google/inject:guice",
        "3rdparty/jvm/com/google/inject/extensions:guice-assistedinject",
        "3rdparty/jvm/com/google/inject/extensions:guice-testlib",
        "3rdparty/jvm/io/netty",
        "3rdparty/jvm/javax/inject:javax.inject",
        "3rdparty/jvm/joda-time",
        "3rdparty/jvm/junit",
        "3rdparty/jvm/net/codingwell:scala-guice",
        "3rdparty/jvm/org/apache/thrift:libthrift",
        "3rdparty/jvm/org/json4s:json4s-core",
        "3rdparty/jvm/org/scalacheck",
        "3rdparty/jvm/org/scalatest",
        "3rdparty/jvm/org/scalatestplus:junit",
        "3rdparty/jvm/org/scalatestplus:scalacheck",
        "3rdparty/jvm/org/slf4j:slf4j-api",
        scoped(
            "3rdparty/jvm/org/slf4j:slf4j-simple",
            scope = "runtime",
        ),
        "finagle/finagle-base-http/src/main",
        "finagle/finagle-http/src/main/scala",
        "finatra/inject/inject-app/src/test/scala/com/twitter/inject/app",
        "finatra/inject/inject-core/src/main/scala/com/twitter/inject",
        "finatra/inject/inject-core/src/test/scala/com/twitter/inject",
        "finatra/inject/inject-utils/src/main/scala",
        "finatra/jackson/src/main/scala/com/twitter/finatra/jackson/caseclass/exceptions",
        "finatra/jackson/src/main/scala/com/twitter/finatra/jackson/modules",
        "finatra/jackson/src/main/scala/com/twitter/finatra/jackson/streaming",
        "finatra/jackson/src/main/scala/com/twitter/finatra/json",
        "finatra/jackson/src/test/java/com/twitter/finatra/jackson",
        "finatra/validation/src/main/java/com/twitter/finatra/validation",
        "finatra/validation/src/main/scala/com/twitter/finatra/validation",
        "finatra/validation/src/test/scala/com/twitter/finatra/validation",
        "util/util-core:scala",
        "util/util-jackson/src/main/scala/com/twitter/util/jackson",
        "util/util-jackson/src/main/scala/com/twitter/util/jackson/caseclass",
        "util/util-jackson/src/main/scala/com/twitter/util/jackson/caseclass/exceptions",
        "util/util-mock/src/main/scala/com/twitter/util/mock",
        "util/util-slf4j-api/src/main/scala",
        "util/util-validator/src/main/scala/com/twitter/util/validation",
    ],
)
