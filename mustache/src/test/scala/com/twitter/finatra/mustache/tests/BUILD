junit_tests(
    sources = ["**/*.scala"],
    tags = ["bazel-compatible"],
    dependencies = [
        "3rdparty/jvm/javax/inject:javax.inject",
        "3rdparty/jvm/org/scalatestplus:junit",
        scoped(
            "3rdparty/jvm/org/slf4j:slf4j-nop",
            scope = "runtime",
        ),
        "finatra/inject/inject-app/src/test/scala/com/twitter/inject/app",
        "finatra/inject/inject-core/src/test/scala/com/twitter/inject",
        "finatra/mustache/src/main/scala/com/twitter/finatra/mustache/marshalling",
        "finatra/mustache/src/main/scala/com/twitter/finatra/mustache/modules",
        "finatra/mustache/src/test/resources",
        "finatra/utils/src/main/scala/com/twitter/finatra/modules",
    ],
)
