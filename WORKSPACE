http_archive(
    name = "io_bazel_rules_go",
    #sha256 = "91fca9cf860a1476abdc185a5f675b641b60d3acf0596679a27b580af60bf19c",
    #url = "https://github.com/bazelbuild/rules_go/releases/download/0.7.0/rules_go-0.7.0.tar.gz",

    # contains gopkg.in fix.
    #473ed9b2bf3279bfb52cc85dd3a9d22a2f99d9a6
    strip_prefix = "rules_go-473ed9b2bf3279bfb52cc85dd3a9d22a2f99d9a6",
    urls = ["https://github.com/bazelbuild/rules_go/archive/473ed9b2bf3279bfb52cc85dd3a9d22a2f99d9a6.tar.gz"],
)

load("@io_bazel_rules_go//go:def.bzl", "go_rules_dependencies", "go_register_toolchains", "go_repository")

go_rules_dependencies()

go_register_toolchains()
