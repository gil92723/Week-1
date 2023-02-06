Lab Questions:
* The paths used by target_sources and target_include_directories are relative, not absolute. What file or folder are they relative to?
    They should be relative to whatever source and include directories need to be accessed and used through the Makefile
* What some differences between cmake and ninja?
    ninja is a build system and is a target for cmake, like an intermediary that usually isn’t directly used by people
* Why is it important to run cmake in its own directory?
    so that the makefile knows where to find and create additional files needed for the build.
