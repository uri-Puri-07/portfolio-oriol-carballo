# Portfolio de Oriol Carballo López

Portfolio personal hecho con **Astro + Tailwind CSS**.

## Qué incluye

- Página de inicio personalizada con el nombre de Oriol.
- Secciones: Proyectos, Tecnologías, Certificados y Sobre mí.
- Certificados reales añadidos en `public/certificates/`:
  - Matrícula de honor FP · Escola Pia Santa Anna de Mataró · junio 2025.
  - Curso de SQL desde Cero · OpenWebinars · 08 julio 2025.
  - Certified Engineer · Hornetsecurity · 03/10/25.
  - Ciberseguridad NIVEL I · bLearn / SonicWall / Bytemaster · 02 julio 2024.
  - Curso de HTML5 y CSS3 · OpenWebinars · 04 noviembre 2024.

## Cómo arrancarlo

```bash
npm install
npm run dev
```

## Cómo generar la versión final

```bash
npm run build
```

La web compilada queda en la carpeta `dist/`.

## Cosas que debes cambiar antes de publicarlo

En `src/pages/index.astro` y `src/components/Footer.astro`, cambia estos enlaces por los tuyos:

- `https://www.linkedin.com/`
- `https://github.com/`
- `mailto:oriol.carballo10@gmail.com`

También puedes editar los proyectos en `src/components/Proyectos.astro` cuando tengas repositorios o demos reales.
