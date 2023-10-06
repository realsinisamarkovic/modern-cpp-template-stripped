# Modern C++ Template

A quick C++ template for modern CMake projects, aimed to be an easy to use
starting point.

Forked from: [https://github.com/filipdutescu/modern-cpp-template](https://github.com/filipdutescu/modern-cpp-template)

Removed conan, catch2 and Github workflows to make the template simpler.

Added CMakePresets.json with Debug and Release configure/build/test presets.

Made C++20 the default.

Run the following setup commands while in project root dir:
```
git submodule init

git submodule update

cd vcpkg && ./bootstrap-vcpkg.sh
```
## License

This project is licensed under the [Unlicense](https://unlicense.org/) - see the
[LICENSE](LICENSE) file for details
