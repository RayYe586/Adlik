load("//adlik_serving:serving.bzl", "serving_cc_library")

package(default_visibility = ["//adlik_serving:internal"])

serving_cc_library(
    name = "topsinference_runtime",
    srcs = ["topsinference_runtime.cc"],
    deps = [
        "//adlik_serving/runtime/topsinference/model:topsinference_model",
        "//adlik_serving/runtime/util:unique_batcher_runtime_helper",
    ],
    alwayslink = 1,
)
