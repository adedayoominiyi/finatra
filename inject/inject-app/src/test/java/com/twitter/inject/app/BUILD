junit_tests(
    sources = ["*.java"],
    compiler_option_sets = ["fatal_warnings"],
    strict_deps = True,
    tags = ["bazel-compatible"],
    dependencies = [
        "3rdparty/jvm/com/google/inject:guice",
        "3rdparty/jvm/com/google/inject/extensions:guice-assistedinject",
        "3rdparty/jvm/com/google/inject/extensions:guice-testlib",
        "3rdparty/jvm/javax/inject:javax.inject",
        "3rdparty/jvm/junit",
        "3rdparty/jvm/org/mockito:mockito-core",
        "3rdparty/jvm/org/slf4j:slf4j-api",
        scoped(
            "3rdparty/jvm/org/slf4j:slf4j-simple",
            scope = "runtime",
        ),
        "finatra/inject/inject-app/src/main/java/com/twitter/inject/annotations",
        "finatra/inject/inject-app/src/main/scala/com/twitter/inject/app",
        "finatra/inject/inject-app/src/main/scala/com/twitter/inject/app/internal",
        "finatra/inject/inject-app/src/test/java/com/twitter/inject/annotations",
        "finatra/inject/inject-app/src/test/scala/com/twitter/inject/app",
        "finatra/inject/inject-core/src/main/scala/com/twitter/inject",
        "finatra/inject/inject-core/src/test/scala/com/twitter/inject",
        "finatra/inject/inject-modules/src/main/scala/com/twitter/inject/modules",
        "finatra/inject/inject-modules/src/test/scala/com/twitter/inject/modules",
        "util/util-app/src/main/scala",
        "util/util-core:scala",
    ],
)
