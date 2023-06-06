![](jumbo.jpg)

    yarn install
    yarn dev

This is a small primer on how to use GLTF models on the web, specifically how to use them as dynamic assets.

Live demo: 

### How to compress assets and turn them into JSX components

1. `npx gltf-pipeline -i model.gltf -o model.glb --draco.compressionLevel=7`
1. `npx gltfjsx model.glb`

### How to include them in your project

1. Set up [react-three-fiber](https://github.com/pmndrs/react-three-fiber)
1. Put `model.glb` into `/public`
1. Put `Model.js` (the output of [gltfjsx](https://github.com/pmndrs/react-three-fiber)) anywhere inside `/src`


# Comands:
1. yarn add valtio
1. yarn add @react-three/drei (https://github.com/pmndrs/drei)
1. yarn add three @react-three/fiber (js)
1. yarn add @types/three (ts)

1. yarn add @react-three/cannon (physics)
1. yarn add @react-three/postprocessing
1. yarn add @use-gesture/react


