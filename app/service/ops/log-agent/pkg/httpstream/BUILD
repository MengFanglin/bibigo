package(default_visibility = ["//visibility:public"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_library",
)

go_library(
    name = "go_default_library",
    srcs = [
        "conf.go",
        "httpstream.go",
    ],
    importpath = "go-common/app/service/ops/log-agent/pkg/httpstream",
    tags = ["automanaged"],
    visibility = ["//visibility:public"],
    deps = ["//app/service/ops/log-agent/event:go_default_library"],
)

filegroup(
    name = "package-srcs",
    srcs = glob(["**"]),
    tags = ["automanaged"],
    visibility = ["//visibility:private"],
)

filegroup(
    name = "all-srcs",
    srcs = [":package-srcs"],
    tags = ["automanaged"],
    visibility = ["//visibility:public"],
)
