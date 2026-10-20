# Los Refugios del Pirineo Aragonés

Mapa navegable en relieve de los 225 refugios de montaña del Pirineo aragonés: 15 refugios guardados, 136 refugios libres y 74 cabañas donde se puede pasar la noche. Cada refugio tiene una ficha con altitud, plazas, equipamiento, estado, normas de pernocta del espacio protegido, cimas y refugios cercanos y la ruta de aproximación más rápida con su perfil, y un modelo 3D del entorno que se puede girar.

**Ver el mapa:** https://rforcano.github.io/refugios-pirineo-aragones/

Proyecto creado por [Ricardo Forcano](https://ricardoforcano.es/) con Claude. Es el compañero del mapa de los [tresmiles del Pirineo](https://rforcano.github.io/tresmiles-pirineo/).

## Archivos

- `index.html`: la aplicación (mapa WebGL, índice de refugios, fichas y visor 3D).
- `datos-base.js`: relieve de 50 m, cobertura del suelo, ríos, lagos, glaciares, valles, senderos GR, cimas, refugios, rutas de aproximación y fotos.
- `datos-relieve-1.js`, `datos-relieve-2.js` y `datos-relieve-3.js`: relieve de 10 m alrededor de los refugios y de la alta montaña. Se cargan después de mostrar el mapa.

Es una web estática: funciona en GitHub Pages o en cualquier servidor de archivos. Las tipografías se cargan desde Google Fonts y el visor 3D usa three.js desde cdnjs.

## Datos y licencias

- Relieve: © Instituto Geográfico Nacional de España (MDT02, MDT05 y MDT25, CC BY 4.0); IGN France, RGE ALTI (Licence Ouverte Etalab 2.0), servidos a través de Mapterhorn; Copernicus DEM GLO-30 (© DLR e.V. 2010-2014 y © Airbus Defence and Space GmbH 2014-2018, proporcionado en el marco de COPERNICUS por la Unión Europea y la ESA).
- Cobertura del suelo: © ESA WorldCover project 2021 (CC BY 4.0), con datos modificados de Copernicus Sentinel (2021).
- Refugios, caminos, senderos GR, ríos, lagos, glaciares, carreteras, pueblos y cimas: © colaboradores de OpenStreetMap (ODbL).
- Inventario y descripción de los refugios contrastados con refugiosnoguardados.org, pyrenees-refuges.com, refuges.info y la red de refugios de la Federación Aragonesa de Montañismo. Las notas de cada ficha son un resumen propio.
- Normas de pernocta: Decreto 49/2015 del Parque Nacional de Ordesa y Monte Perdido (modificado por el Decreto 16/2022), planes de los parques naturales Posets-Maladeta y Valles Occidentales, y Decreto 61/2006 de Aragón.
- Fotos: Wikimedia Commons. El autor y la licencia de cada foto aparecen en su ficha.
- Visor 3D: three.js (licencia MIT). Tipografías Barlow, Barlow Condensed y Cormorant Garamond (SIL Open Font License).

Las rutas de aproximación se calculan sobre la red de caminos de OpenStreetMap y los tiempos son estimaciones sin paradas (método MIDE). El estado de los refugios libres y cabañas cambia de un año a otro: antes de salir, consulta una guía actualizada, el estado de la montaña y, en los refugios guardados, la apertura y la reserva.
