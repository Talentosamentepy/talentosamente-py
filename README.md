# Talentosamente — Sitio web + diagnóstico

Sitio estático listo para GitHub Pages, preparado a partir de los archivos compartidos.

## Contenido

- `index.html`: página principal de Talentosamente, servicios, talleres y contacto.
- `diagnostico.html`: cuestionario interactivo de empleabilidad y resultados.
- `assets/logo.jpg`: logotipo original.
- `assets/anahid.jpg`: imagen original.
- `.nojekyll`: configuración opcional para publicar archivos estáticos.

## Publicación en GitHub Pages

1. Creá un repositorio en GitHub (por ejemplo, `talentosamente`).
2. Subí **el contenido de esta carpeta** a la raíz del repositorio, conservando la carpeta `assets`.
3. Confirmá los archivos con **Commit changes**.
4. Entrá en **Settings → Pages → Build and deployment**.
5. Elegí **Deploy from a branch**, la rama **main** y la carpeta **/(root)**. Guardá.
6. Visitá `https://TU-USUARIO.github.io/talentosamente/`. El diagnóstico estará en `/diagnostico.html`.

## Personalización

- Textos, enlaces y estilos principales: `index.html`.
- Preguntas, cálculo de resultados y datos de contacto: `diagnostico.html`.
- Colores de marca: variables CSS `--brand` y `--brand-hover`.
- Revisá números de WhatsApp, redes sociales, textos e imágenes antes de hacer público el repositorio.

## Alcances y privacidad

Este proyecto es HTML, CSS y JavaScript estático; no requiere servidor ni base de datos. El diagnóstico se calcula en el navegador. El envío por WhatsApp abre la aplicación/enlace con el resumen y requiere que la persona lo envíe. No hay almacenamiento automático de respuestas en servidor. Verificá que contás con autorización para publicar los recursos e información de marca.
