junit_tests(
    sources = [
        "*.java",
        "*.scala",
        "constraints/*.scala",
    ],
    strict_deps = True,
    tags = ["bazel-compatible"],
    dependencies = [
        "3rdparty/jvm/com/fasterxml/jackson/core:jackson-annotations",
        "3rdparty/jvm/org/joda:joda-convert",
        "3rdparty/jvm/org/scalacheck",
        "3rdparty/jvm/org/scalatest",
        "3rdparty/jvm/org/scalatestplus:junit",
        "3rdparty/jvm/org/scalatestplus:scalacheck",
        "3rdparty/jvm/org/slf4j:slf4j-api",
        scoped(
            "3rdparty/jvm/org/slf4j:slf4j-simple",
            scope = "runtime",
        ),
        "finatra/inject/inject-core/src/test/scala/com/twitter/inject",
        "finatra/inject/inject-utils/src/main/scala",
        "finatra/validation/src/main/java/com/twitter/finatra/validation",
        "finatra/validation/src/main/scala/com/twitter/finatra/validation",
        "finatra/validation/src/test/scala/com/twitter/finatra/validation",
        "util/util-validator/src/main/scala/com/twitter/util/validation",
        "util/util-validator/src/main/scala/com/twitter/util/validation/conversions",
    ],
)
