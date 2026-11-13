# angle-apple-build

CI that builds Google's ANGLE (OpenGL ES on Vulkan and Metal) for macOS arm64 and fetches MoltenVK
(Vulkan on Metal), for running OpenGL ES 3.1 programs on Apple machines. Only the build recipe lives
here; ANGLE and MoltenVK come from their own projects under their own licenses (BSD-3-Clause and
Apache-2.0). The built libraries are in each run's artifacts.
