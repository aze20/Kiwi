load("@build_bazel_rules_apple//apple:apple.bzl",
     "apple_static_framework_import",
)

apple_static_framework_import(
    name = "Kiwi2",
    framework_imports = glob(["/Kiwi.framework/**"]),
    visibility = ["//visibility:public"],
)

objc_library(
  name = "MyLibrary",
  srcs = [],
  deps = [":Kiwi2"],
)

