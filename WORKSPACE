workspace(name = "com_github_bazelboost_winapi")

load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")

git_repository(
    name = "boost",
    commit = "develop",
    remote = "git@github.com:bazelboost/boost.git",
)

load("@boost//:index.bzl", "boost_repositories")

boost_repositories()
