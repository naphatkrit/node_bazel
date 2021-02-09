load("@build_bazel_rules_nodejs//:index.bzl", "nodejs_binary")

nodejs_binary(
    name = "app",
    entry_point = "app.js",
    data = [
        "@npm_deps//:node_modules",
    ],
)
