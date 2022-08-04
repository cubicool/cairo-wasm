# cairo-wasm

A small template project for using Cairo with an HTML5/ES6 Canvas.

# Setup

The EMSDK is added as a submodule, using a specific tag (3.1.18). Go into the
directory and *activate* the build environment:

```
# cd emsdk
# ./emsdk install 3.1.18
# ./emsdk activate 3.1.18
# source emsdk_env.sh --build=Debug
```

# TODO

- [ ] A lot of great starting info [here](https://web.dev/drawing-to-canvas-in-emscripten/).

- [ ] Build up a basic example of drawing via Cairo into a Canvas element, using
  "Material Design" wrappers; implemented via [MaterializeCSS](https://materializecss.com).

- [ ] Integrate the template bits from [osg-wasm](https://github.com/cubicool/osg-wasm).

- [ ] Integrate the Cairo CMake build--if permissible--from employer
  [AlphaPixel](https://alphapixel.com).
