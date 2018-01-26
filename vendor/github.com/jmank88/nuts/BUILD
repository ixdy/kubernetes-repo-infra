load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "key.go",
        "nuts.go",
        "paths.go",
        "types.go",
    ],
    importpath = "github.com/jmank88/nuts",
    visibility = ["//visibility:public"],
    deps = ["//vendor/github.com/boltdb/bolt:go_default_library"],
)
