# Elementor / WordPress

Esta carpeta contiene una version lista para pegar en un widget HTML de Elementor:

- `monitoring-technology-elementor.html`
- `monitoring-technology-elementor-inline-assets.html`
- `monitoring-technology-elementor-template.json`

Uso:

1. Abre `monitoring-technology-elementor.html`.
2. Copia todo el contenido del archivo.
3. Pegalo dentro de un widget HTML de Elementor.

Uso recomendado cuando algunas personas no pueden ver los iconos:

1. En WordPress, ve a Elementor > Herramientas > Importar / Exportar kit o Plantillas > Importar plantillas.
2. Importa `monitoring-technology-elementor-template.json`.
3. Inserta la plantilla importada en la pagina.

Alternativa:

1. Abre `monitoring-technology-elementor-inline-assets.html`.
2. Copia todo el contenido.
3. Pegalo en un widget HTML de Elementor.

Notas tecnicas:

- Todas las clases usan el prefijo `dalog-mt` para evitar conflictos con Elementor, WordPress o el tema activo.
- El CSS esta encapsulado bajo `.dalog-mt`.
- El JavaScript solo inicializa widgets dentro de `.dalog-mt` y evita inicializar el mismo bloque dos veces.
- Las imagenes cargan desde `https://jt-desing.github.io/multisensor/assets/`, asi el bloque funciona sin subir assets a WordPress.
- Si quieres alojar los assets en WordPress, reemplaza `https://jt-desing.github.io/multisensor/assets/` por la URL de tu carpeta en Medios o en el tema.
- La version `inline-assets` y el JSON importable incluyen los iconos en base64 para evitar bloqueos de recursos externos.
