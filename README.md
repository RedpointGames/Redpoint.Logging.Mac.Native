# Redpoint.Logging.Mac.Native

This repository builds and publishes the `Redpoint.Logging.Mac.Native` NuGet package, which provides the native macOS `.dylib` files that are necessary to support logging to the macOS system log in `Redpoint.Logging.Mac`.

This folder used to be part of the [UET](https://github.com/RedpointGames/uet) repository, but was moved here to simplify the build process of UET when developing on a local machine. This library basically never changes it's implementation, so having it build and publish from it's own repository, and having UET simply depend on the published NuGet package was considered far more maintainable.

All bug reports should be reported in the [UET](https://github.com/RedpointGames/uet) repository.

All code in this repository is licensed MIT.