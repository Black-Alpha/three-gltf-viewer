# glTF Viewer

Preview glTF 2.0 models in WebGL using three.js and a drag-and-drop interface.

* Web (https://gltf-viewer.donmccurdy.com/)
* Desktop apps for Windows, MacOS, and Linux ([download](https://github.com/donmccurdy/three-gltf-viewer/releases))

![screenshot](https://user-images.githubusercontent.com/1848368/31580352-b7354096-b101-11e7-86d7-f07677835812.png)

## Quickstart

### FBX TO GLTF 
(recommended)
https://github.com/facebookincubator/FBX2glTF/releases


### Web

```
npm install
npm run dev
```
### Desktop (Electron)

To build the desktop application, run:

```shell
# development build
npm run dev:electron

# package for release
npm run package
```

## glTF 2.0 Resources

- [THREE.GLTFLoader](https://github.com/mrdoob/three.js/blob/dev/examples/js/loaders/GLTFLoader.js)
- [glTF 2.0 Specification](https://github.com/KhronosGroup/glTF/blob/master/specification/2.0/README.md)
- [glTF 2.0 Sample Models](https://github.com/KhronosGroup/glTF-Sample-Models/tree/master/2.0/)

## Known Issues

- [ ] Limited drag-and-drop support in Safari.
