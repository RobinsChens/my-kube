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
    srcs = [
        "doc.go",
        "fake_authorization_client.go",
        "fake_generated_expansion.go",
        "fake_localsubjectaccessreview.go",
        "fake_selfsubjectaccessreview.go",
        "fake_subjectaccessreview.go",
    ],
    tags = ["automanaged"],
    deps = [
        "//pkg/apis/authorization:go_default_library",
        "//pkg/client/clientset_generated/internalclientset/typed/authorization/unversioned:go_default_library",
        "//pkg/client/restclient:go_default_library",
        "//pkg/client/testing/core:go_default_library",
    ],
)
