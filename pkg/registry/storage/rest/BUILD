package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_binary",
    "go_library",
    "go_test",
    "cgo_library",
)

go_library(
    name = "go_default_library",
    srcs = ["storage_storage.go"],
    tags = ["automanaged"],
    deps = [
        "//pkg/api/rest:go_default_library",
        "//pkg/apis/storage:go_default_library",
        "//pkg/apis/storage/v1beta1:go_default_library",
        "//pkg/genericapiserver:go_default_library",
        "//pkg/registry/generic:go_default_library",
        "//pkg/registry/storage/storageclass/etcd:go_default_library",
    ],
)
