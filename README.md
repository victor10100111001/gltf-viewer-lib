# gltf-viewer
glTF Viewer written in Rust (early WIP)

### Goals
* Complete gltF 2.0 support
* Reusable & extensible renderer
* Platforms: Windows/Linux/macOS; Browser via WebAssembly
* Graphics backends:
  - OpenGL ES 3.0 (-> WebGL 2.0 via WebAssembly)
  - OpenGL 4.1+
  - Vulkan?
* VR support (Focus: HTC Vive)

### Non-goals
* Fancy UI (i.e. No more than command line + "switches" for changing scenes, toggling animations etc.)
