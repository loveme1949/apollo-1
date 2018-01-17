load("//tools:cpplint.bzl", "cpplint")

package(default_visibility = ["//visibility:public"])

cc_library(
    name = "lattice_planner",
    hdrs = [
        "lattice_planner.h",
    ],
    srcs = [
        "lattice_planner.cc",
    ],
    deps = [
        "//modules/common:log",
        "//modules/common/vehicle_state:vehicle_state_provider",
        "//modules/common/adapters:adapter_manager",
        "//modules/planning/common:planning_gflags",
        "//modules/planning/constraint_checker:constraint_checker",
        "//modules/planning/planner:planner",
        "//modules/planning/proto:planning_proto",
        "//modules/planning/lattice/util:lattice_util",
        "//modules/planning/lattice/trajectory_generator:trajectory1d_generator",
        "//modules/planning/lattice/trajectory_generator:trajectory_evaluator",
        "//modules/planning/lattice/behavior_decider:behavior_decider",
        "//modules/planning/lattice/behavior_decider:path_time_neighborhood",
    ],
)

cpplint()