## Gazebo CMake 3.x

### Gazebo CMake 3.0.1 (2022-10-11)

1. 1. FindIgnOGRE2: preserve PKG_CONFIG_PATH
    * [Pull request #319](https://github.com/gazebosim/ign-cmake/pull/319)

1. FindSQLite3: Add SQLite::SQLite3 ALIAS
    * [Pull request #313](https://github.com/gazebosim/gz-cmake/pull/313)

1. FindUUID: Do not wrap LIBRARY_NAMES argument with quotes
    * [Pull request #315](https://github.com/gazebosim/gz-cmake/pull/315)

1. Disable source tooltips
    * [Pull request #314](https://github.com/gazebosim/gz-cmake/pull/314)

1. Don't assume `CMAKE_INSTALL_*DIR` variables are relative
    * [Pull request #305](https://github.com/gazebosim/gz-cmake/pull/305)

### Gazebo CMake 3.0.0 (2022-09-23)

1. CMake macro to find the assimp library
    * [Pull request #278](https://github.com/gazebosim/gz-cmake/pull/278)
    * [Pull request #291](https://github.com/gazebosim/gz-cmake/pull/291)
    * [Pull request #292](https://github.com/gazebosim/gz-cmake/pull/292)

1. Changes for OGRE-2.3
    * [Pull request #283](https://github.com/gazebosim/gz-cmake/pull/283)
    * [Pull request #297](https://github.com/gazebosim/gz-cmake/pull/297)

1. Migrate ign -> gz
    * [Pull request #308](https://github.com/gazebosim/gz-cmake/pull/308)
    * [Pull request #277](https://github.com/gazebosim/gz-cmake/pull/277)
    * [Pull request #274](https://github.com/gazebosim/gz-cmake/pull/274)
    * [Pull request #273](https://github.com/gazebosim/gz-cmake/pull/273)
    * [Pull request #271](https://github.com/gazebosim/gz-cmake/pull/271)
    * [Pull request #267](https://github.com/gazebosim/gz-cmake/pull/267)
    * [Pull request #266](https://github.com/gazebosim/gz-cmake/pull/266)
    * [Pull request #265](https://github.com/gazebosim/gz-cmake/pull/265)
    * [Pull request #263](https://github.com/gazebosim/gz-cmake/pull/263)
    * [Pull request #260](https://github.com/gazebosim/gz-cmake/pull/260)
    * [Pull request #258](https://github.com/gazebosim/gz-cmake/pull/258)
    * [Pull request #257](https://github.com/gazebosim/gz-cmake/pull/257)
    * [Pull request #256](https://github.com/gazebosim/gz-cmake/pull/256)
    * [Pull request #255](https://github.com/gazebosim/gz-cmake/pull/255)
    * [Pull request #254](https://github.com/gazebosim/gz-cmake/pull/254)
    * [Pull request #253](https://github.com/gazebosim/gz-cmake/pull/253)
    * [Pull request #252](https://github.com/gazebosim/gz-cmake/pull/252)
    * [Pull request #250](https://github.com/gazebosim/gz-cmake/pull/250)
    * [Pull request #249](https://github.com/gazebosim/gz-cmake/pull/249)
    * [Pull request #247](https://github.com/gazebosim/gz-cmake/pull/247)
    * [Pull request #246](https://github.com/gazebosim/gz-cmake/pull/246)
    * [Pull request #245](https://github.com/gazebosim/gz-cmake/pull/245)
    * [Pull request #244](https://github.com/gazebosim/gz-cmake/pull/244)

1. Removed hardcoded gtest include folder
    * [Pull request #268](https://github.com/gazebosim/gz-cmake/pull/268)

1. Deprecate utilities in favor of ign-utils
    * [Pull request #233](https://github.com/gazebosim/gz-cmake/pull/233)

1. Replace deprecated PythonInterp with Python3
    * [Pull request #213](https://github.com/gazebosim/gz-cmake/pull/213)

1. Disable long-running buildsystem tests by default
    * [Pull request #97](https://github.com/gazebosim/gz-cmake/pull/97)

1. Infrastructure
    * [Pull request #242](https://github.com/gazebosim/gz-cmake/pull/242)
    * [Pull request #209](https://github.com/gazebosim/gz-cmake/pull/209)
    * [Pull request #169](https://github.com/gazebosim/gz-cmake/pull/169)
    * [Pull request #90](https://github.com/gazebosim/gz-cmake/pull/90)
    * [Pull request #89](https://github.com/gazebosim/gz-cmake/pull/89)
    * [Pull request #87](https://github.com/gazebosim/gz-cmake/pull/87)
    * [Pull request #83](https://github.com/gazebosim/gz-cmake/pull/83)
    * [Pull request #77](https://github.com/gazebosim/gz-cmake/pull/77)
    * [Pull request #75](https://github.com/gazebosim/gz-cmake/pull/75)

## Gazebo CMake 2.x

### Gazebo CMake 2.16.0 (2022-10-08)

1. FindIgnOGRE2: preserve PKG_CONFIG_PATH
    * [Pull request #319](https://github.com/gazebosim/ign-cmake/pull/319)

1. FindSQLite3: Add SQLite::SQLite3 ALIAS
    * [Pull request #313](https://github.com/gazebosim/ign-cmake/pull/313)
    * [Pull request #317](https://github.com/gazebosim/ign-cmake/pull/317)

1. FindUUID: Do not wrap LIBRARY_NAMES argument with quotes
    * [Pull request #315](https://github.com/gazebosim/ign-cmake/pull/315)

1. Don't assume `CMAKE_INSTALL_*DIR` variables are relative
    * [Pull request #305](https://github.com/gazebosim/ign-cmake/pull/305)

1. Remove check for s3cfg
    * [Pull request #308](https://github.com/gazebosim/ign-cmake/pull/308)

### Gazebo CMake 2.15.0 (2022-08-29)

1. ign -> gz: add `gz/*` header files
    * [Pull request #303](https://github.com/gazebosim/gz-cmake/pull/303)

1. Backport `GZ_SANITIZER` variable
    * [Pull request #294](https://github.com/gazebosim/gz-cmake/pull/294)

1. Update doxygen file
    * [Pull request #276](https://github.com/gazebosim/gz-cmake/pull/276)

### Gazebo CMake 2.14.0 (2022-07-25)

1. Add code coverage ignore file
    * [Pull request #279](https://github.com/gazebosim/gz-cmake/pull/279)

### Gazebo CMake 2.13.0 (2022-07-22)

1. Backport `GZ_DESIGNATION` tick-tock
    * [Pull request #284](https://github.com/gazebosim/gz-cmake/pull/284)

1. Upload docs to an s3 bucket based only on the major version
    * [Pull request #281](https://github.com/gazebosim/gz-cmake/pull/281)

1. Exclude proto generated cpp in coverage test
    * [Pull request #272](https://github.com/gazebosim/gz-cmake/pull/272)

1. Add LTCG flag on Windows builds
    * [Pull request #251](https://github.com/gazebosim/gz-cmake/pull/251)

1. Update codeowners
    * [Pull request #261](https://github.com/gazebosim/gz-cmake/pull/261)
    * [Pull request #237](https://github.com/gazebosim/gz-cmake/pull/237)

1. Update documentation to gazebosim.org
    * [Pull request #248](https://github.com/gazebosim/gz-cmake/pull/248)

1. Improving CONFIG test
    * [Pull request #235](https://github.com/gazebosim/gz-cmake/pull/235)

### Gazebo CMake 2.12.1 (2022-04-12)

1. Allow to recreate targets created by GzPkgConfig
    * [Pull request #231](https://github.com/gazebosim/gz-cmake/pull/231)

1. Adding tests for CONFIG argument
    * [Pull request #230](https://github.com/gazebosim/gz-cmake/pull/230)

### Gazebo CMake 2.12.0 (2022-04-11)

1. Adding CONFIG option
    * [Pull request #211](https://github.com/gazebosim/gz-cmake/pull/211)

1. GzFindOGRE2: support for the ogre-next package on Ubuntu Jammy
    * [Pull request #224](https://github.com/gazebosim/gz-cmake/pull/224)

1. Fix check for missing components in OGRE2. Be more verbose with components
    * [Pull request #220](https://github.com/gazebosim/gz-cmake/pull/220)

1. FindGzOGRE2: exclude ogre versions different than 2.x
    * [Pull request #219](https://github.com/gazebosim/gz-cmake/pull/219)
    * [Pull request #221](https://github.com/gazebosim/gz-cmake/pull/221)

1. Specify sanitizers using GZ_SANITIZERS cmake variable
    * [Pull request #210](https://github.com/gazebosim/gz-cmake/pull/210)

1. Replace deprecated PythonInterp with Python3 (#213)
    * [Pull request #213](https://github.com/gazebosim/gz-cmake/pull/213)
    * [Pull request #223](https://github.com/gazebosim/gz-cmake/pull/223)

### Gazebo CMake 2.11.0 (2022-02-23)

1. Set source path to be used by common::testing
    * [Pull request #206](https://github.com/gazebosim/gz-cmake/pull/206)

3. Add examples using static libraries
    * [Pull request #202](https://github.com/gazebosim/gz-cmake/pull/202)

### Gazebo CMake 2.10.0 (2021-12-21)

1. doxygen allow all .cc, .hh, and CMakeLists.txt, not just in examples/ dir
    * [Pull request #198](https://github.com/gazebosim/gz-cmake/pull/198)

1. Add `LEGACY_PROJECT_PREFIX` parameter to `gz_create_core_library`
    * [Pull request #199](https://github.com/gazebosim/gz-cmake/pull/199)

1. Add `HIDE_SYMBOLS_BY_DEFAULT` parameter to `gz_configure_build`
    * [Pull request #196](https://github.com/gazebosim/gz-cmake/pull/196)

1. Add Ubuntu Jammy CI
    * [Pull request #194](https://github.com/gazebosim/gz-cmake/pull/194)

1. FindGzURDFDOM cmake module
    * [Pull request #193](https://github.com/gazebosim/gz-cmake/pull/193)

1. Do not modify `CMAKE_FIND_LIBRARY_PREFIXES` and `CMAKE_FIND_LIBRARY_SUFFIXES` on Windows
    * [Pull request #189](https://github.com/gazebosim/gz-cmake/pull/189)

1. Project option: `REPLACE_INCLUDE_PATH`
    * [Pull request #190](https://github.com/gazebosim/gz-cmake/pull/190)

1. Project option: `NO_PROJECT_PREFIX`
    * [Pull request #191](https://github.com/gazebosim/gz-cmake/pull/191)

### Gazebo CMake 2.9.0 (2021-09-02)

1. Fix include directory flags for codecheck
    * [Pull request #186](https://github.com/gazebosim/gz-cmake/pull/186)

1. Fix problems on GzOGRE when version is not found
    * [Pull request #175](https://github.com/gazebosim/gz-cmake/pull/175)

1. Remove bitbucket-pipelines.yml
    * [Pull request #181](https://github.com/gazebosim/gz-cmake/pull/181)

1. Include IMAGE_PATH directories in gz_create_docs
    * [Pull request #183](https://github.com/gazebosim/gz-cmake/pull/183)

1. Special case for ogre2.2 on Windows
    * [Pull request #176](https://github.com/gazebosim/gz-cmake/pull/176)
    * [Pull request #177](https://github.com/gazebosim/gz-cmake/pull/177)
    * [Pull request #178](https://github.com/gazebosim/gz-cmake/pull/178)
    * [Pull request #180](https://github.com/gazebosim/gz-cmake/pull/180)

1. Fix building OGRE / OGRE2 from source in colcon workspace
    * [Pull request #174](https://github.com/gazebosim/gz-cmake/pull/174)

1. Remove codecov badge from README
    * [Pull request #172](https://github.com/gazebosim/gz-cmake/pull/172)

1. Port codecov to new configuration
    * [Pull request #170](https://github.com/gazebosim/gz-cmake/pull/170)

### Gazebo CMake 2.8.0 (2021-04-30)

1. Fix hardcoded pkg-config library in examples
    * [Pull request #163](https://github.com/gazebosim/gz-cmake/pull/163)

1. User-friendly skip component warning
    * [Pull request #165](https://github.com/gazebosim/gz-cmake/pull/165)

1. Run gz-cmake's copy of check_test_ran
    * [Pull request #168](https://github.com/gazebosim/gz-cmake/pull/168)

### Gazebo CMake 2.7.0 (2021-03-30)

1. Support to find Ogre 2-2
    * [Pull request #157](https://github.com/gazebosim/gz-cmake/pull/157)

1. glib fix for Windows
    * [Pull request #154](https://github.com/gazebosim/gz-cmake/pull/154)

1. Fix cmake message types
    * [Pull request #159](https://github.com/gazebosim/gz-cmake/pull/159)

1. Support imported targets in FindGzOGRE.cmake
    * [Pull request #150](https://github.com/gazebosim/gz-cmake/pull/150)

1. Infrastructure
    * [Pull request #148](https://github.com/gazebosim/gz-cmake/pull/148)
    * [Pull request #149](https://github.com/gazebosim/gz-cmake/pull/149)
    * [Pull request #151](https://github.com/gazebosim/gz-cmake/pull/151)
    * [Pull request #152](https://github.com/gazebosim/gz-cmake/pull/152)
    * [Pull request #155](https://github.com/gazebosim/gz-cmake/pull/155)
    * [Pull request #153](https://github.com/gazebosim/gz-cmake/pull/153)
    * [Pull request #158](https://github.com/gazebosim/gz-cmake/pull/158)
    * [Pull request #160](https://github.com/gazebosim/gz-cmake/pull/160)

1. Set cmake CMP0079 policy
    * [Pull request 146](https://github.com/gazebosim/gz-cmake/pull/146)

1. Tutorial about building with cmake and colcon
    * [Pull request 145](https://github.com/gazebosim/gz-cmake/pull/145)

1. Add an option to disable docs when building
    * [Pull request 144](https://github.com/gazebosim/gz-cmake/pull/144)

1. Install hpp files as headers
    * [Pull request 143](https://github.com/gazebosim/gz-cmake/pull/143)

1. Suppress warning C5205 on Windows
    * [Pull request 141](https://github.com/gazebosim/gz-cmake/pull/141)

1. Windows installation instructions via conda-forge
    * [Pull request 139](https://github.com/gazebosim/gz-cmake/pull/139)

1. Ensure relocatable config files
    * [Pull request 129](https://github.com/gazebosim/gz-cmake/pull/129)

### Gazebo CMake 2.6.2 (2020-12-29)

1. FindUUID: Always define UUID::UUID on Apple platforms
    * [Pull request 128](https://github.com/gazebosim/gz-cmake/pull/128)

1. Remove deprecated doxygen configurations
    * [Pull request 136](https://github.com/gazebosim/gz-cmake/pull/136)

1. Generate doxygen tutorials for gz-cmake
    * [Pull request 137](https://github.com/gazebosim/gz-cmake/pull/137)

1. Enable make codecheck for gz-cmake
    * [Pull request 138](https://github.com/gazebosim/gz-cmake/pull/138)

1. Generate valid visibility macros by replacing hyphens in component name
    * [Pull request 135](https://github.com/gazebosim/gz-cmake/pull/135)

### Gazebo CMake 2.6.1 (2020-12-10)

1. Revert python to optional dependency
    * [Pull request 132](https://github.com/gazebosim/gz-cmake/pull/132)

### Gazebo CMake 2.6.0 (2020-12-08)

1. Added build-essential and cmake to packages.apt
    * [Pull request 130](https://github.com/gazebosim/gz-cmake/pull/130)

1. Fix FindGzOgre on Windows when not using vcpkg
    * [Pull request 124](https://github.com/gazebosim/gz-cmake/pull/124)

1. FindGzOGRE2: prefer versioned component libraries
    * [Pull request 125](https://github.com/gazebosim/gz-cmake/pull/125)

1. Correct CMake logic and update cpplint to Python3
    * [Pull request 117](https://github.com/gazebosim/gz-cmake/pull/117)

1. Improve fork experience
    * [Pull request 118](https://github.com/gazebosim/gz-cmake/pull/118)

### Gazebo CMake 2.5.0 (2020-09-05)

1. Add additional input directories to parse when generating documentation
    * [Pull request 111](https://github.com/gazebosim/gz-cmake/pull/111)

### Gazebo CMake 2.4.0 (2020-08-20)

1. Added an option to include generated code in the gz_create_docs function
    * [Pull request 108](https://github.com/gazebosim/gz-cmake/pull/108)

### Gazebo CMake 2.3.0 (2020-08-07)

1. New macros to help with filter google-test in some platforms
    * [Pull request 102](https://github.com/gazebosim/gz-cmake/pull/102)

1. Disable long-running buildsystem tests by default
    * [Pull request 97](https://github.com/gazebosim/gz-cmake/pull/97)

1. Fix use of FindYAML.cmake and FindJSONCPP without pkg-config
    * [Pull request 79](https://github.com/gazebosim/gz-cmake/pull/79)

1. Fix use of FindGzOGRE2 on Windows if OGRE2 is not found
    * [Pull request 94](https://github.com/gazebosim/gz-cmake/pull/94)
    * Thanks to Silvio Traversaro

1. FindUUID: Export include path as expected by Gazebo Libraries #104
    * [Pull request 104](https://github.com/gazebosim/gz-cmake/pull/104)
    * Thanks to Silvio Traversaro

1. Make the OGRE plugin path discovery portable
    * [Pull request 101](https://github.com/gazebosim/gz-cmake/pull/101)
    * Thanks to Sean Yen

### Gazebo CMake 2.2.0

1. Fix use of FindZIP without pkg-config.
    * [BitBucket pull request 182](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/182)

1. Use mathjax to render equations.
    * [BitBucket pull request 181](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/181)

1. Reduce example names to fix build on Windows
    * [BitBucket pull request 180](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/180)

1. Fix doxygen deprecation filter
    * [BitBucket pull request 160](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/160)

1. Change the diamond link icon to a material design link
    * [BitBucket pull request 159](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/159)

1. Disable long-running buildsystem tests by default.
    * [Pull request 97](https://github.com/gazebosim/gz-cmake/pull/97)
1. Set viewport for doxygen pages.
    * [BitBucket pull request 167](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/167)

1. Use upstream `CURL::libcurl` imported target in FindGzCURL.cmake if available.
    * [BitBucket pull request 175](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/175)

1. Avoid hardcoding /machine:x64 flag on 64-bit on MSVC.
    * [BitBucket pull request 171](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/171)
    * [BitBucket pull request 168](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/168)

1. FindGzOGRE2: fix include paths for new directory structure.
    * [BitBucket pull request 170](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/170)
    * [BitBucket pull request 157](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/157)

1. Support for custom vcpkg ogre2 windows port (backport of PR 155).
    * [BitBucket pull request 161](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/161)
    * [BitBucket pull request 155](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/155)

1. GzConfigureBuild: only `add_subdirectory(test)` if `BUILD_TESTING` is ON
    * [BitBucket pull request 169](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/169)

1. Add FindGzBullet cmake module.
    * [BitBucket pull request 162](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/162)

### Gazebo CMake 2.1.1 (2019-08-07)

1. Turn on doxygen warnings, add CI script to check for doxygen warnings.
    * [BitBucket pull request 158](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/158)

### Gazebo CMake 2.1.0 (2019-05-17)

1. Fixes for vcpkg ogre 1.11 version
    * [BitBucket pull request 152](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/152)

1. Add benchmark aggregation functionality
    * [BitBucket pull request 148](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/148)
    * [BitBucket pull request 149](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/149)

1. Use `PRIVATE_FOR` to skip cmake dependencies in addition to pkg-config
    * [BitBucket pull request 147](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/147)

1. `upload_doc.sh`: actually use dry-run, and allow the user to pass in a 'y' or 'n'
    * [BitBucket pull request 146](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/146)

1. Set favicon
    * [BitBucket pull request 145](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/145)

1. Fix tagfile generation by preventing the inclusion of tutorials
    * [BitBucket pull request 142](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/142)

1. Update datainstall dir
    * [BitBucket pull request 141](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/141)

1. Allow tests to build without automatic linking against project lib
    * [BitBucket pull request 140](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/140)

### Gazebo CMake 2.0.0 (2019-01-31)

1. Require cmake 3.10.2, support `CXX_STANDARD` 17
    * [BitBucket pull request 68](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/68)

    * [Full list of changes](https://github.com/gazebosim/gz-cmake/compare/ignition-cmake2_2.0.0...ign-cmake1)

## Gazebo CMake 1.x

1. Set viewport for doxygen pages.
    * [BitBucket pull request 167](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/167)

1. Use upstream `CURL::libcurl` imported target in FindGzCURL.cmake if available.
    * [BitBucket pull request 175](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/175)

1. Avoid hardcoding /machine:x64 flag on 64-bit on MSVC.
    * [BitBucket pull request 171](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/171)
    * [BitBucket pull request 168](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/168)

1. GzConfigureBuild: only `add_subdirectory(test)` if `BUILD_TESTING` is ON
    * [BitBucket pull request 165](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/165)

1. Fix race condition in test for issue 48
    * [BitBucket pull request 136](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/136)
    * [Issue 48](https://github.com/gazebosim/gz-cmake/issues/48)

1. Account for inter-component dependencies when importing targets
    * [BitBucket pull request 131](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/131)
    * [Issue 48](https://github.com/gazebosim/gz-cmake/issues/48)

### Gazebo CMake 1.1.0

* Initial version bumped to 1.1.0 since there was a 1.1.0 prerelease

### Gazebo CMake 1.0.0

    * [Full list of changes](https://github.com/gazebosim/gz-cmake/compare/ignition-cmake1_1.0.0...ign-cmake0)

## Gazebo CMake 0.x

1. Set viewport for doxygen pages.
    * [BitBucket pull request 167](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/167)

1. Use upstream `CURL::libcurl` imported target in FindGzCURL.cmake if available.
    * [BitBucket pull request 175](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/175)

1. Avoid hardcoding /machine:x64 flag on 64-bit on MSVC.
    * [BitBucket pull request 168](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/168)

1. GzConfigureBuild: only `add_subdirectory(test)` if `BUILD_TESTING` is ON
    * [BitBucket pull request 163](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/163)

1. GzConfigureProject.cmake: fix small typo PKCONFIG -> PKGCONFIG
    * [BitBucket pull request 118](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/118)

### Gazebo CMake 0.6.1

1. Fix duplicated imported target error
    * [BitBucket pull request 110](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/110)
    * [Issue 47](https://github.com/gazebosim/gz-cmake/issues/47)

### Gazebo CMake 0.6.0

1. Properly mark internal CMake cache variables as advanced
    * [BitBucket pull request 68](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/68)

1. Make line coverage by default, add separate coverage-branch target
    * [BitBucket pull request 66](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/66)

1. Refactor variable names in example test junit templates
    * [BitBucket pull request 57](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/57)

1. Suport for `CMAKE_BUILD_TYPE` None
    * [BitBucket pull request 54](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/54)

### Gazebo CMake 0.5.0

1. FindJSONCPP: fix target when pkg-config is successful
    * [BitBucket pull request 50](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/50)

1. Add branch coverage
    * [BitBucket pull request 46](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/46)

1. Add FindOptiX.cmake
    * [BitBucket pull request 34](https://osrf-migration.github.io/ignition-gh-pages/#!/ignitionrobotics/ign-cmake/pull-requests/34)

### Gazebo CMake 0.4.1

    * [Full list of changes](https://github.com/gazebosim/gz-cmake/compare/ignition-cmake_0.4.1...ignition-cmake_0.4.0)

### Gazebo CMake 0.4.0
