load("//tools:cpplint.bzl", "cpplint")

package(default_visibility = ["//visibility:public"])

cc_library(
    name = "interface",
    srcs = [],
    hdrs = glob(["*.h"]),
    deps = [
        "//modules/drivers/proto:sensor_proto",
        "//modules/perception/lib/base",
        "//modules/perception/lib/pcl_util",
        "//modules/perception/obstacle/base",
        "//modules/perception/obstacle/onboard:hdmapinput",
        "@eigen",
    ],
)

cpplint()
