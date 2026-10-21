# Boulder Escape — COMP1401A T2

Videojuego 3D original con HTML, CSS, JavaScript y Three.js. Luma corre por una ruta selvática mientras una roca gigante la persigue.

## Rúbrica cubierta

- Escena Three.js con cámara en perspectiva, iluminación, sombras y renderizado mediante `requestAnimationFrame`.
- Camino y jungla construidos con geometrías básicas.
- Personaje 3D original, centrado al iniciar y controlado lateralmente con A/D o flechas, limitado al camino.
- Roca gigante `SphereGeometry` con textura local cargada usando `TextureLoader`, detrás del personaje y con rotación continua.
- Conos, pirámides y estalagmitas aleatorios en movimiento; la carrera se simula de forma continua y acaba al colisionar.

## Ejecutar localmente

En la carpeta del proyecto ejecute:

```powershell
py -m http.server 8000
```

Abra `http://localhost:8000`. Pulse **Comenzar carrera** y use **A/D** o las flechas izquierda/derecha.

## Estructura

```
boulder-escape-threejs/
├── index.html
├── styles.css
├── js/game.js
└── assets/stone-texture.svg
```

Three.js se carga como módulo desde jsDelivr, por lo que se necesita internet la primera vez.