package(default_visibility = ["//visibility:public"])

cc_library(
    name = "xxhash",
    srcs = glob([
        "*.c",
        "*.h",
        "*.cc",
        "cli/*.c",
        "cli/*.h",
        "cli/*.cc",
        ]),
    hdrs = glob([
        "*.h",
        "cli/*.h",
        "xxhash/*.h",
        "xxHash/*.h",
        ]),
    copts = [
        "-Iexternal/xxHash",
        "-Iexternal/xxhash",
        ],
)
