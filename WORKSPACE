workspace(name = "com_github_bazelboost_winapi")

load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")

git_repository(
    name = "boost",
    remote = "https://github.com/bazelboost/boost",
    branch = "main",
)

load("@boost//:index.bzl", "boost_git_repositories")
boost_git_repositories(branch = "develop")
