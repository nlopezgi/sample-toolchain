package(default_visibility = ["//visibility:public"])

filegroup(
    name = "empty",
    srcs = [],
)

cc_toolchain_suite(
    name = "default-toolchain",
    toolchains = {
        "k8|gcc": ":cc-compiler-k8",
    },
)

cc_toolchain(
    name = "cc-compiler-k8",
    all_files = ":empty",
    compiler_files = ":empty",
    cpu = "k8",
    dwp_files = ":empty",
    dynamic_runtime_libs = [":empty"],
    linker_files = ":empty",
    objcopy_files = ":empty",
    static_runtime_libs = [":empty"],
    strip_files = ":empty",
    supports_param_files = 1,
)

