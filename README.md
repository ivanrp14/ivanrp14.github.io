# ivanrp14.github.io

Sitio publicado en **GitHub Pages**. El repositorio contiene el resultado de un build de Vite, no el código fuente.

## Qué hay

```
index.html                          # entrada; el <title> sigue siendo "Vite + React"
assets/index-*.js                   # JavaScript ya empaquetado
assets/index-*.css                  # CSS ya empaquetado
images/                             # imágenes estáticas
vite.svg
```

No hay `package.json` ni carpeta `src`. Para cambiar textos o secciones hay que reconstruir desde el proyecto fuente y volver a copiar `index.html` y `assets/`.

El portfolio en React con las secciones y los idiomas está en el repositorio privado `portfolio`.

## Cómo se ve en local

Cualquier servidor estático sobre esta carpeta vale. Por ejemplo, con Node:

```bash
npx serve .
```

En GitHub, el sitio sale de la rama `main` (o de la rama que Pages tenga configurada) en la raíz del repo.
