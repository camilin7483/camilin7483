# Portafolio de Camilo — 2026

Web estática bilingüe (ES/EN) y responsive. Funciona sin backend ni compilación.

## Ver localmente

```bash
python -m http.server 8000
```

Abre `http://localhost:8000/`.

## Proyectos seleccionados (auditoría de 16-11-2026)

- **Kastral** (`camilin7483/kastral`): CI pública exitosa en el commit actual `5e72492`; stack Next.js, TypeScript, Rust/Tauri.
- **kdenlive-mcp** (`camilin7483/kdenlive-mcp`): servidor MCP con código público; informe local reportó 91 tests y render verificado. GitHub aún muestra una versión anterior; quedan verificaciones de GUI.
- **cine-cli** (`camilin7483/cine-cli`): CI pública exitosa en el commit actual `f77f48f`; CLI/TUI en Go.

**Retirados de la selección (no borrados de GitHub):** `mcp-onlyoffice` y `DevOS`. Hay código, documentación y capturas, pero no se verificó su ejecución o una CI reciente durante esta revisión. No implica que estén rotos. Otros repos sin evidencia comparable no se incorporaron.

## Contacto

`cuentacamilo48@gmail.com` (enlace `mailto:`). Esta dirección queda pública al publicar el sitio, por petición expresa del propietario.

## Publicar en GitHub Pages

La carpeta es apta para servir desde la raíz de una rama `gh-pages` (incluye `.nojekyll`). Si se publica en `camilin7483/camilin7483`, en Settings → Pages se debe seleccionar **Deploy from a branch** → `gh-pages` → `/(root)` y guardar. El enlace normalmente sería `https://camilin7483.github.io/camilin7483/` una vez activado y completado el despliegue; confirmar la URL en **Visit site**.

GitHub Pages no se activa automáticamente por crear una rama. Comprueba el estado de publicación antes de compartir el enlace.

## Notas

- `index.html` y `portfolio.html` son idénticos.
- CSS y JS en `assets/`; imágenes SVG propias del diseño y una captura enlazada desde GitHub para cine-cli.
- No se incluyen tokens ni servicios de seguimiento.
- Los enlaces a repositorios son públicos; la presencia de código no certifica todas sus capacidades.
