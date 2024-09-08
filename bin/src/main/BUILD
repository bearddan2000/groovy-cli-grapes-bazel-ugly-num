load("@io_bazel_rules_groovy//groovy:groovy.bzl", "groovy_binary")

groovy_binary (
    name = "BazelApp",
    srcs = glob(["groovy/**/*.groovy"]),
    main_class = "example.Main",
    deps = [
      
    ],
    resources = ["resources/log4j.xml"],
    visibility = ["//visibility:public"],
)
