# Threejs

## Como correr 

```
npm install 
npm run dev
```

## Relevante 
Con estas propiedades se puede agregar una escena al canvas en threejs

```
const cubeTextureLoader = new THREE.CubeTextureLoader();

const environmentMapTexture = cubeTextureLoader.load([
  "/env/px.png",
  "/env/nx.png",
  "/env/py.png",
  "/env/ny.png",
  "/env/pz.png",
  "/env/nz.png",
]);
scene.background = environmentMapTexture;
```


