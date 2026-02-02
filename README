# OpenGL + GLFW + GLAD (Linux)

A minimal OpenGL project using **GLFW**, **GLAD**, and **CMake**. Tested on Arch/Manjaro; other distributions listed below are unverified but expected to work with the noted packages.

This project demonstrates how to:
- Create a window with GLFW
- Load OpenGL functions using GLAD
- Build the project using CMake
---

## Requirements

- Arch Linux (Wayland session)
- OpenGL (Mesa)
- GLFW (Wayland)
- CMake
- GCC or Clang

Install dependencies:

- Arch / Manjaro:
	```bash
	sudo pacman -S mesa glfw-wayland cmake gcc
	```
- Ubuntu / Debian:
	```bash
	sudo apt update
	sudo apt install build-essential cmake libglfw3-dev libglu1-mesa-dev libgl1-mesa-dev
	```
- Fedora / RHEL-based:
	```bash
	sudo dnf install gcc-c++ cmake glfw-devel mesa-libGL-devel mesa-libGLU-devel
	```

We will use GLAD to load OpenGL functions. You can generate the GLAD files from [the GLAD web service](https://glad.dav1d.de/) with the following settings:
- ``Language``: C/C++
- ``Specification``: OpenGL
- ``Profile``: Core
- ``gl``: Version 3.3
## Project Structure
```
.
├── CMakeLists.txt
├── include/
│   ├── glad/glad.h
│   └── KHR/khrplatform.h
├── src/
│   └── glad.c
└── main.cpp
```
## Build & Run
### Configure
```bash
cmake -S . -B build
```
### Build
```bash
cmake --build build
```
### Run
```bash
./build/app
```
You should see a window titled "Hello OpenGL" with a green background appear on your screen.

## References
- [GLFW Documentation](https://www.glfw.org/docs/latest/)
- [GLAD Documentation](https://glad.dav1d.de/)
- [Learn OpenGL](https://learnopengl.com/)