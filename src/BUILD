load("@io_bazel_rules_kotlin//kotlin:kotlin.bzl", "kt_jvm_binary")
load("@io_bazel_rules_kotlin//kotlin:kotlin.bzl", "kt_jvm_library")

kt_jvm_library(
    name = "src",
    srcs = glob(["*.kt"]),
    deps = [
    ],
)

kt_jvm_binary(
    name = "test",
    main_class = "TestKt",
    srcs = glob(["*.kt"]),
)