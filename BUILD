load("@rules_java//java:defs.bzl", "java_binary","java_library")

java_binary(
    name = "ProjectRunner",
    srcs = ["src/main/java/com/example/ProjectRunner.java"],
    deps = ["//:greeter"]
)

java_library(
    name = "greeter",
    srcs = ["src/main/java/com/example/Greeting.java"],
    visibility = ["//visibility:public"]
)
