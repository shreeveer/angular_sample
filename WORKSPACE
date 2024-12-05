workspace(name = "angular_bazel_project")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

# Angular-related repository setup
http_archive(
    name = "angular",
    url = "https://github.com/bazelbuild/rules_angular/releases/download/v0.25.0/angular-0.25.0.tar.gz",
    strip_prefix = "angular-0.25.0",
)

load("@angular//:defs.bzl", "angular_workspace")

angular_workspace()
