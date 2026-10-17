# Planning Talent 360° — Planning for Evolution

Versión 1.0 · 17 de octubre de 2026

## Aplicación

**[Abrir aplicación web](https://harambulo-afk.github.io/planning-talent-360/)** · **[Repositorio independiente](https://github.com/harambulo-afk/planning-talent-360)**

Abrir **Planning_Talent_360.html** en un navegador moderno (Chrome, Edge o Safari). Es una aplicación autónoma con los estilos, el catálogo y el código JavaScript integrados. No requiere instalación ni servidor.

## Funciones

- 348 perfiles profesionales en 9 familias
- Banco de candidatos y búsqueda de perfiles
- Vacantes y necesidades de proyectos
- Evaluación explicable de compatibilidad (matching)
- Búsqueda externa mediante enlaces a plataformas profesionales
- Exportación e importación JSON, además de CSV para análisis

## Archivos

- `Planning_Talent_360.html`: versión autónoma ejecutable
- `catalogo.json`: taxonomía de perfiles
- `app.js`: lógica y componentes de interfaz
- `styles.css`: estilos
- `index.html`: entrada del sitio web; abre la aplicación autónoma
- `.nojekyll`: permite servir los archivos directamente en GitHub Pages

## Seguridad y privacidad

El sitio público distribuye la aplicación y su catálogo de referencia. Comienza sin candidatos ni vacantes; los ejemplos se cargan únicamente cuando el usuario elige la demostración.

**No subir información personal real de candidatos a GitHub**, ni credenciales, tokens o copias de seguridad exportadas. El banco de candidatos se almacena localmente en el navegador del dispositivo. Esta versión no ofrece autenticación, control multiusuario ni almacenamiento centralizado; no es un portal compartido para publicar CV o expedientes de candidatos.

Los datos locales no están cifrados por la aplicación. Evita registrar información sensible en equipos compartidos. Las exportaciones JSON y CSV contienen los datos que hayas registrado y deben conservarse fuera del repositorio. Las búsquedas externas se abren por una acción explícita del usuario. GitHub Pages puede registrar visitas al sitio, pero esta aplicación no envía a GitHub los registros del banco de talento.

El matching apoya las decisiones humanas, pero no toma decisiones de contratación de forma autónoma.

## Publicación independiente

Separado el 17 de octubre de 2026 como repositorio público propio de Planning for Evolution. El código funcional, los estilos y el catálogo se conservaron tal como estaban en la aplicación original. El proyecto de media tensión conserva su copia y su configuración.

GitHub Pages publica desde la rama `main`, carpeta raíz. Para usarlo sin conexión, descarga `Planning_Talent_360.html` desde el repositorio y ábrelo con doble clic.

Los datos del navegador no se trasladan automáticamente entre la versión local y la web. Para migrarlos, usa **Datos y respaldo → Exportar JSON** en la versión anterior e **Importar respaldo JSON** en la nueva. La importación reemplaza los registros locales del navegador de destino.

© Planning for Evolution.
