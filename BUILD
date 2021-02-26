package(default_visibility = ["//visibility:public"])

cc_library(
    name = "xxhash",
    srcs = glob([
        "*.c",
        "*.h",
        "*.cc",
        ]),
    hdrs = glob([
        "*.h",
        ]),
    copts = ["-Iexternal/xxHash"],
    includes = ["xxHash"],
)
