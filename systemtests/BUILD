package(default_visibility = ["//visibility:public"])

java_test(
    name = "systemtests.test",
    test_class = "systemtests.test.AllTests",
    srcs = glob(["test/**/*.java", "test/*.java"]),
    deps = [
        "//lib:lib",
        "//protolib:protolib",
        "//miner:miner",
        "//node",
        "//client:client",
        "//shackleton:shackleton",
        "@duckutil//:duckutil_lib"
    ]
)
