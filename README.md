# Visor · Análisis Geoespacial de las UOPSI y el sistema educativo público 2026

Visor web del documento *Análisis Geoespacial de las UOPSI y el sistema educativo público Nacional* (Dirección de Prestaciones Económicas y Sociales, Unidad de Prestaciones Sociales, IMSS).

## Contenido

- `index.html`: página principal del visor.
- `data/geo/`: registros de planteles por OOAD (DENUE, INEGI, 2026), cargados al seleccionar cada OOAD.
- `maps/`: mapas de georreferencia de cada UOPSI tomados del documento.
- `docs/`: documento completo del análisis en PDF.
- `img/`: elementos de identidad gráfica.

## Publicación con GitHub Pages

1. Suba el contenido de esta carpeta a la raíz del repositorio (rama `main`).
2. En el repositorio, abra **Settings → Pages**.
3. En **Build and deployment**, elija **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Guarde.
4. En uno o dos minutos el visor estará disponible en `https://<usuario>.github.io/<repositorio>/`.

El visor requiere conexión a internet para cargar el mapa de OpenStreetMap y las bibliotecas Leaflet y SheetJS desde cdnjs.

## Fuentes

- Planteles educativos: Directorio Estadístico Nacional de Unidades Económicas (DENUE), INEGI, 2026.
- Mapa base: © colaboradores de OpenStreetMap.
