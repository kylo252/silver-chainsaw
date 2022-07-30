cmake_minimum_required(VERSION 3.10)

project(
  integration-test
  LANGUAGES C
  )

find_package(tree-sitter REQUIRED)
option(BUILD_SHARED_LIBS "Build shared libraries" ON)
