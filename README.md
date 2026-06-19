# 🐕 Dogfy 3D
Prueba de concepto con estética Nintendo 64: un perrito low-poly construido íntegramente con geometría procedural para validar el look retro 3D antes de dar el salto a un cartucho real.

## ✨ Características
- Perrito modelado con primitivas de Three.js (esferas, cilindros y conos), ~200 polígonos en total.
- Estética N64 auténtica: sin antialiasing, `pixelRatio` a 1 y niebla a media distancia.
- `flatShading` con `MeshLambertMaterial` para el sombreado plano clásico.
- Suelo con textura dibujada en canvas 64x64 y filtrado `NearestFilter` para que se vea bien pixelada.
- Paleta verde DMG que conecta con el resto del universo Dogfy.
- Cero instalación: usa Three.js vía CDN.

## 🚀 Cómo jugar / ejecutar
```bash
open index.html
```
Funciona en cualquier navegador moderno, sin dependencias ni build.

## 🎮 Controles
- Arrastra: girar la cámara.
- Scroll: zoom.
- Doble-click: reset de cámara.

## 🛠️ Tecnología
- JavaScript + Three.js (vía CDN).
- `OrbitControls` para la cámara.
- Geometría 100% procedural, sin modelos externos.

## 📦 Parte de mi colección de juegos
Uno más de mis proyectos de juegos hechos por hobby. 🎮
