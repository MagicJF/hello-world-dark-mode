# hello-world-dark-mode

Página "Hello, World!" de un solo archivo con modo claro y oscuro.

## Uso

Abre `index.html` en el navegador, o sirve la carpeta:

```sh
python3 -m http.server 8000
```

Luego visita http://localhost:8000

## Características

- Botón para alternar entre modo claro y oscuro.
- El tema elegido se guarda en `localStorage`.
- En la primera visita respeta `prefers-color-scheme` del sistema.
- Sin dependencias ni build: solo HTML, CSS y JavaScript.
