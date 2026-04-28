cmake_minimum_required(VERSION 3.11)
project(qrgen VERSION 0.1.0 LANGUAGES C CXX)

include(FetchContent)

FetchContent_Declare(
  cli11
  GIT_REPOSITORY https://github.com/CLIUtils/CLI11.git
  GIT_TAG v2.6.2
)
FetchContent_MakeAvailable(cli11)

add_executable(qrgen main.cpp)

target_link_libraries(qrgen PRIVATE CLI11::CLI11)
