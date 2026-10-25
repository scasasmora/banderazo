# Banderazo

Juego de flag football 5 contra 5 para el navegador, en versión 2D y 3D.

**Jugar:** abre `index.html` o la página de GitHub Pages del repositorio.

## Cómo se juega

- **Ataque:** elige una jugada y toca **¡Hut!**. Toca a un receptor para lanzarle (en 3D también con los botones 1–4). El color del anillo indica qué tan libre está. Arrastra para esquivar con el QB o correr tras la atrapada.
- **Downs:** 4 intentos para cruzar medio campo; si lo cruzas, los downs se reinician y tienes 4 más para anotar. El QB tiene 7 segundos para lanzar.
- **Conversión:** después de anotar eliges 1 punto (desde la 5) o 2 puntos (desde la 12).
- **Defensa:** después de cada serie tuya, el rival ataca. Elige Hombre a hombre, Zona, Blitz o Profunda, y controla a tu defensor arrastrando; toca a otro para cambiar.
- **Editor de jugadas:** crea rutas para cada receptor, guárdalas y úsalas en el juego. Se guardan en el navegador de cada persona.

## Online 1 contra 1

En `banderazo-online.html`, un jugador toca **Crear partida** y comparte el código de 4 letras; el otro lo escribe en **Unirse**. Se turnan en ataque y defensa, y ninguno ve la jugada que eligió el otro hasta el snap. La conexión es directa entre los dos dispositivos (PeerJS); en algunas redes muy restringidas puede fallar, en ese caso prueben con otro wifi.

Con teclado: flechas para moverte, 1–4 para lanzar, espacio para ¡Hut!

## Archivos

| Archivo | Qué es |
|---|---|
| `index.html` | Página de inicio para elegir versión |
| `banderazo-2d.html` | Versión 2D (campo visto desde arriba) |
| `banderazo-online.html` | Versión 2D para jugar 1 contra 1 por internet (usa [PeerJS](https://peerjs.com)) |
| `banderazo-3d.html` | Versión 3D con cámara de QB (usa [three.js](https://threejs.org) r128 desde CDN) |

Cada juego es un solo archivo HTML sin dependencias que instalar.
