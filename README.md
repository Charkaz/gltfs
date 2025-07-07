# glTF Models Collection

A collection of 3D models in glTF (Graphics Language Transmission Format) for testing, development, and demonstration purposes.

## About glTF

glTF (GL Transmission Format) is a royalty-free specification for the efficient transmission and loading of 3D scenes and models by applications. glTF minimizes both the size of 3D assets and the runtime processing needed by applications using those assets.

## Included Models

This repository contains the following 3D models:

### Balloon Models
- `balloon.gltf` - Primary balloon model (45MB)
- `ballon2.gltf` - Alternative balloon model (3MB) 
- `ballon3.gltf` - Third balloon variant (1.7MB)
- `ballonesas.gltf` - Large balloon model with extensive data (60MB)

### Scene Files
- `scene.gltf` - 3D scene configuration (302KB)
- `scenee.gltf` - Alternative scene setup (302KB)
- `scene.glb` - Binary version of scene (1.7MB)

### Other Models
- `camera.gltf` - Camera configuration and positioning
- `testmodel.gltf` - Test model for development (2.3MB)
- `model.glb` - Binary glTF model (1.7MB)

## File Formats

- **`.gltf`** - JSON format, human-readable, larger file size
- **`.glb`** - Binary format, more compact, faster loading

## Usage

These models can be viewed and used with:

- **Online Viewers**: [glTF Viewer](https://gltf-viewer.donmccurdy.com/), [Three.js Editor](https://threejs.org/editor/)
- **3D Software**: Blender, Autodesk Maya, 3ds Max (with glTF plugins)
- **Game Engines**: Unity, Unreal Engine, Godot
- **Web Development**: Three.js, Babylon.js, A-Frame
- **Mobile**: Model Viewer (Android), AR Quick Look (iOS)

## Quick Start

1. Download or clone this repository
2. Open any `.gltf` file in a compatible viewer or import into your 3D application
3. For web development, reference the models in your JavaScript code:

```javascript
// Example with Three.js
import { GLTFLoader } from 'three/examples/jsm/loaders/GLTFLoader.js';

const loader = new GLTFLoader();
loader.load('path/to/balloon.gltf', function(gltf) {
    scene.add(gltf.scene);
});
```

## Resources

- [glTF Official Specification](https://github.com/KhronosGroup/glTF)
- [glTF Sample Models](https://github.com/KhronosGroup/glTF-Sample-Models)
- [Three.js glTF Documentation](https://threejs.org/docs/#examples/en/loaders/GLTFLoader)