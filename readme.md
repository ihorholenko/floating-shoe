![](jumbo.jpg)

    npm install
    npm start
    
This is a small primer on how to use GLTF models on the web, specifically how to use them as dynamic assets.

Tutorial: https://www.youtube.com/watch?v=xy_tbV4pC54

Live demo: https://codesandbox.io/s/floating-shoe-forked-qxjoj

### How to compress assets and turn them into JSX components

1. `npx gltf-pipeline -i model.gltf -o model.glb --draco.compressionLevel=7`
1. `npx gltfjsx model.glb`

### How to include them in your project

1. Set up [react-three-fiber](https://github.com/pmndrs/react-three-fiber)
1. Put `model.glb` into `/public`
1. Put `Model.js` (the output of [gltfjsx](https://github.com/pmndrs/react-three-fiber)) anywhere inside `/src`



# Comands:
1. npm i valtio
1. npm install @react-three/drei (https://github.com/pmndrs/drei)
1. npm install three @react-three/fiber (js)
1. npm install @types/three (ts)

1. npm install @react-three/cannon (physics)
1. npm install @react-three/postprocessing
1. npm install @use-gesture/react


** ALERT !! DONT WORK  **

