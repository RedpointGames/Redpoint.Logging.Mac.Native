# UET (native libraries)

This repository builds and publishes libraries for UET that are dependent on native APIs: `Redpoint.Logging.Mac.Native` which provides the native macOS `.dylib` files that are necessary to support logging to the macOS system log in `Redpoint.Logging.Mac`, and `Redpoint.AutoDiscovery` which can only be built on Windows.

The C# projects in this repository used to be part of the [UET](https://github.com/RedpointGames/uet) repository, but they were moved here to simplify the build process of UET when developing on a local machine. These library implementations basically never change, so having it build and publish from it's own repository, and having UET simply depend on the published NuGet packages was considered far more maintainable.

All bug reports should be reported in the [UET](https://github.com/RedpointGames/uet) repository.

All code in this repository is licensed MIT.