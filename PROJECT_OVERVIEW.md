# Project Overview: Fedora GoogleTest, GoogleMock, and Valgrind Environment (`gtestmock-docker`)

## Purpose and Scope

`gtestmock-docker` (`/botworkspace/gtestmock-docker`) provides a Fedora-based C++ test and memory-analysis container specification bundling `gcc-c++`, `cmake`, `gtest`, `gmock`, `valgrind`, AddressSanitizer (`libasan`), LeakSanitizer (`liblsan`), and `lcov` code coverage tooling.

## Repository Contents

- [Dockerfile](file:///botworkspace/gtestmock-docker/Dockerfile): Fedora image definition installing `@development-tools`, `gmock`, `gmock-devel`, `gtest`, `gtest-devel`, `cmake`, `extra-cmake-modules`, `gcc-c++`, `valgrind`, `libasan`, `liblsan`, and `lcov`.
- [README.md](file:///botworkspace/gtestmock-docker/README.md): Overview of the Fedora GTest + GMock development environment.
