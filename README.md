# Curso de Tailwind desde Cero

Este proyecto es una práctica de Tailwind CSS, un framework de utilidades para crear interfaces modernas y responsivas rápidamente.

## Estructura del Proyecto

- `index.html`: Archivo principal HTML donde se aplica Tailwind CSS.
- `input.css`: Archivo fuente donde se importan las directivas de Tailwind (`@tailwind base;`, `@tailwind components;`, `@tailwind utilities;`).
- `assets/`: Carpeta con recursos como imágenes (`avatar.webp`), SVGs (`sprite.svg`) y el CSS generado (`output.css`).
- `tailwind.config.js`: Archivo de configuración de Tailwind CSS.
- `package.json` y `bun.lock`: Manejo de dependencias y scripts.

## Instalación y Uso

1. **Instalar dependencias**

   Si usas [Bun](https://bun.sh/):
   ```sh
   bun install
   ```
   O si prefieres npm:
   ```sh
   npm install
   ```

2. **Compilar Tailwind CSS**

   Ejecuta el comando para generar el CSS a partir de `input.css`:
   ```sh
   npx tailwindcss -i ./input.css -o ./assets/output.css --watch
   ```

3. **Abrir el proyecto**

   Abre `index.html` en tu navegador para ver la página con los estilos de Tailwind aplicados.

## Recursos útiles
- [Documentación oficial de Tailwind CSS](https://tailwindcss.com/docs/installation)

---

