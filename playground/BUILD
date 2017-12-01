cc_library(
    name = "hello_world_lib",
    hdrs = ["hello_world_lib.h"],
    srcs = ["hello_world_lib.cc"]
)


cc_binary(
    name = "hello_world",
    srcs = ["hello_world.cc"],
)

cc_test(
     name = "hello_world_lib_test",
     srcs = ["hello_world_lib_test.cc"],
     deps = [":hello_world_lib",
             "//googletest:gtest_main",]
)