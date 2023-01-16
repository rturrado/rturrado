Welcome to my GitHub site! 👋

Most of the repositories you'll find here are just forks. However, a few of them are projects of my own.

## Modern C++

After leaving my previous job, I've been catching up with *Modern C++* and some of its ecosystem during 2021 and 2022.

The project [the_modern_cpp_challenge](https://github.com/rturrado/the_modern_cpp_challenge) touches many different tools from this ecosystem: libraries (`fmt`, `range-v3`), unit testing (`gtest`, fakes, mocks), benchmarking (`Google benchmark`), build systems (`CMake`), package management (`FetchContent`, `vcpkg`), continuous integration (`GitHub actions`), sanitizers and static analysis tools (`address sanitizer`, `clang-tidy`, `code coverage`), `docker`...

Regarding package management, some of these projects could serve as templates for the available alternatives. For example, [the_modern_cpp_challenge](https://github.com/rturrado/the_modern_cpp_challenge) manage dependencies via `FetchContent` and `vcpkg`, [word_converter](https://github.com/rturrado/word_converter) only through `FetchContent`, and [aoc_2022](https://github.com/rturrado/aoc_2022) with `Conan`. I have yet to explore `Bazel`.

[aoc_2022](https://github.com/rturrado/aoc_2022) contains a few little examples of ranges (from Eric Niebler's `range-v3` library, not C++23 standard ones). I find functional programming quite beautiful.

I'm also interested in coroutines and how they can be helpful in certain situations. The [coro](https://github.com/rturrado/coro) project makes use of the reference implementation of the `std::generator` proposal, as well as `boost::asio` coroutines. And the [word_converter](https://github.com/rturrado/word_converter) project implements the tokenizer for a small language parser as a a coroutine.

## Before C++11

[rubik](https://github.com/rturrado/rubik.git) and [snooker](https://github.com/rturrado/snooker.git) are a couple of projects from another span of a few months when I was also unemployed, back in 2008. They use `OpenGL` for rendering, and `autotools` as build system.
