# Summary

[Introduction](index.md)

# Part I: Core

- [🧭 Quickstart](quickstart.md)
- [📚 Tutorial: A Flutter+Rust app](tutorial_with_flutter.md)
  - [Android setup](tutorial/setup_android.md)
    - [Alternative NDK setup](tutorial/alternative_ndk.md)
- [🎼 Features](feature.md)
  - [Language translations](feature/lang.md)
    - [Simple correspondence](feature/lang_simple.md)
    - [Vec and array](feature/lang_vec.md)
    - [Struct](feature/lang_struct.md)
    - [Enum](feature/lang_enum.md)
    - [External types](feature/lang_external.md)
    - [Option](feature/lang_option.md)
    - [Methods](feature/lang_methods.md)
    - [Return types](feature/lang_return_types.md)
    - [Dynamic](feature/lang_dynamic.md)
    - [Arbitrary Rust types (opaque)](feature/lang_rust_opaque.md)
    - [Arbitrary Dart types (opaque)](feature/lang_dart_opaque.md)
    - [Type alias](feature/lang_type_alias.md)
    - [Exceptions](feature/lang_exceptions.md)
    - [Parameter defaults](feature/lang_default.md)
  - [Zero copy](feature/zero_copy.md)
  - [Stream / Iterator](feature/stream.md)
  - [Async in Dart](feature/async_dart.md)
  - [Sync in Dart](feature/sync_dart.md)
  - [Concurrency](feature/concurrency.md)
  - [Handler](feature/handler.md)
  - [Initialization](feature/init.md)
  - [Async in Rust](feature/async_rust.md)
  - [Multiple files](feature/multiple_files.md)
  - [Run in build.rs](feature/build_rs.md)
  - [Cancellable tasks](feature/cancelable_task.md)
  - [Object pools](feature/object_pool.md)
  - [WASM](feature/wasm.md)
  - [Miscellaneous](feature/misc.md)
  - [Logging](feature/logging.md)
  - [Stack Traces](feature/stack_trace.md)
  - [Worker pool](feature/worker_pool.md)

# Part II: User Guide

- [Create new projects from a template](template.md)
  - [Creating a new project](template/setup.md)
    - [Android setup](template/setup_android.md)
    - [iOS setup](template/setup_ios.md)
    - [Web setup](template/setup_web.md)
    - [Windows and Linux](template/setup_desktop.md)
    - [Other platforms](template/setup_others.md)
  - [Template tour](template/tour.md)
    - [native/src/api.rs](template/tour_api.md)
    - [`android/app/build.gradle`](template/tour_gradle.md)
    - [`native/native.xcodeproj`](template/tour_native_proj.md)
    - [`justfile`](template/tour_justfile.md)
    - [`rust.cmake`](template/tour_cmake.md)
  - [Generating code](template/generate.md)
    - [Installing codegen](template/generate_install.md)
    - [Adding new code](template/generate_adding_code.md)
    - [Using build_runner](template/generate_build_runner.md)
    - [Wrapping up](template/generate_finish.md)
- [Integrating with existing projects](integrate.md)
  - [Creating a new crate](integrate/new_crate.md)
  - [Installing dependencies](integrate/deps.md)
  - [Integrating with Android](integrate/android.md)
    - [Hooking onto tasks](integrate/android_tasks.md)
    - [CMake with Gradle](integrate/android_cmake.md)
  - [Integrating with iOS/MacOS](integrate/ios.md)
    - [Creating the Rust project](integrate/ios_proj.md)
    - [Linking the project](integrate/ios_linking.md)
    - [Generating bindings](integrate/ios_gen.md)
    - [Using dummy headers](integrate/ios_headers.md)
  - [Integrating with Windows and Linux](integrate/desktop.md)
  - [Integrating with Web](integrate/web.md)
  - [Using the dynamic library](integrate/usage.md)
  - [Wrapping up](integrate/finish.md)
- [Creating a Dart/Flutter library](library.md)
  - [Overview](library/overview.md)
    - [Setup](library/setup.md)
    - [Monorepo with Melos](library/melos.md)
  - [Creating the libraries](library/creating_libraries.md)
    - [Dart-only base](library/dart_only.md)
    - [Flutter wrapper](library/flutter_wrapper.md)
  - [Platform specific setup](library/platform_setup.md)
    - [Windows & Linux](library/platform_setup/windows_and_linux.md)
    - [iOS & macOS](library/platform_setup/ios_and_macos.md)
    - [Android](library/platform_setup/android.md)
  - [Continuous Integration & Deployment (CI/CD)](library/ci.md)

# Part III: Contributor Guide

- [Overview](contributing/overview.md)
- [Overall design](contributing/design.md)
- [Submodule implementations](contributing/submodule.md)
  - [Rust opaque type safety](contributing/rust_opaque_type_safety.md)
  - [Dart opaque type safety](contributing/dart_opaque_type_safety.md)
- [Appendix](contributing/appendix.md)
- [Translate](contributing/translate.md)

# Part IV: More Doc
- [Unit testing in Flutter](unit_tests_dart.md)
- [Tutorial: Pure Dart](tutorial_pure_dart.md)
- [Safety concerns](safety.md)
- [Troubleshooting](troubleshooting.md)
- [Command line arguments](command_line.md)
- [Set up Flutter/Dart+Rust support from scratch](set_up_from_scratch.md)
- [Building a WASM binary manually](build_wasm.md)
- [Limitations of WASM](wasm_limitations.md)
- [Articles](article.md)
  - [Async in Rust](article/async_in_rust.md)
  - [Generate multiple files](article/generate_multiple_files.md)
