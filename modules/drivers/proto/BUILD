package(default_visibility = ["//visibility:public"])

cc_proto_library(
    name = "sensor_proto",
    deps = [
        ":sensor_proto_lib",
    ],
)

proto_library(
    name = "sensor_proto_lib",
    srcs = [
        "mobileye.proto",
        "delphi_esr.proto",
    ],
    deps = [
        "//modules/common/proto:header_proto_lib",
    ],
)
