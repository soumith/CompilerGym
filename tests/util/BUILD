# Copyright (c) Facebook, Inc. and its affiliates.
#
# This source code is licensed under the MIT license found in the
# LICENSE file in the root directory of this source tree.

py_test(
    name = "capture_output_test",
    srcs = ["capture_output_test.py"],
    deps = [
        "//compiler_gym/util",
        "//tests:test_main",
    ],
)

cc_test(
    name = "EnumUtilTest",
    srcs = ["EnumUtilTest.cc"],
    deps = [
        "//compiler_gym/util:EnumUtil",
        "//tests:TestMacros",
        "//tests:TestMain",
        "@gtest",
    ],
)

cc_test(
    name = "StrLenConstexprTest",
    srcs = ["StrLenConstexprTest.cc"],
    deps = [
        "//compiler_gym/util:StrLenConstexpr",
        "//tests:TestMain",
    ],
)

py_test(
    name = "temporary_working_directory_test",
    timeout = "short",
    srcs = ["temporary_working_directory_test.py"],
    deps = [
        "//compiler_gym/util",
        "//tests:test_main",
    ],
)

py_test(
    name = "timer_test",
    srcs = ["timer_test.py"],
    deps = [
        "//compiler_gym/util",
        "//tests:test_main",
    ],
)
