# Oktana · Agentforce Industry Agent Library

Presentación interactiva en HTML/CSS para la **Agentforce Industry Agent Library** de Oktana.

## Estructura

```text
.
├── index.html
├── styles.css
└── README.md
```

## Ejecutar localmente

Puedes abrir `index.html` directamente en el navegador.

También puedes levantar un servidor HTTP local:

```bash
python -m http.server 8000
```

Y abrir:

```text
http://localhost:8000
```

## Desplegar con GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube `index.html`, `styles.css` y `README.md` a la raíz.
3. Ve a **Settings → Pages**.
4. En **Build and deployment**, selecciona:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)`
5. Guarda los cambios.
6. GitHub publicará el sitio en una URL similar a:

```text
https://TU-USUARIO.github.io/TU-REPOSITORIO/
```

## Navegación e interacción

La presentación mantiene la navegación interactiva de la versión original, incluyendo navegación entre slides, controles por teclado, comportamiento responsive y soporte para `prefers-reduced-motion`.

## Assets

El logo y la iconografía permanecen embebidos directamente en el HTML mediante `data:` y SVG, por lo que no se requiere una carpeta adicional de assets para este despliegue.

## Responsive

La experiencia está optimizada para desktop y cuenta con fallbacks responsive para pantallas más pequeñas.

## Archivos principales

- `index.html`: estructura, contenido e interacción.
- `styles.css`: sistema visual, layouts, cards, responsive y animaciones.
- `README.md`: instrucciones de uso y despliegue.

---

Basado en `oktana_agentforce_industry_agent_library_v03.html`.
