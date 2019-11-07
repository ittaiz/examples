load("//attributes:printer.bzl", "printer")

filegroup(
  name = "sources",
  srcs = glob(["*.scala"]),
)

printer(
    name = "some_target",
    deps = [
        ":sources",
    ],
)
