cc_library(
    name = "subprocess",
    hdrs = ["subprocess/subprocess.h"],
    copts = ["-Wno-sign-compare"],
    visibility = ["//visibility:public"],
)

cc_test(
    name = "cat_test",
    size = "small",
    srcs = ["subprocess/test_cat.cc"],
    deps = [
        ":subprocess",
    ],
)
