# 🗺️ Mapa Interactivo – Zonas de A Coruña

Este proyecto contiene un mapa interactivo que representa tres zonas urbanas de la ciudad de **A Coruña**, en Galicia. El mapa se ha construido con código HTML y JavaScript, utilizando la librería Leaflet para la visualización geográfica.

## 📌 ¿Qué hace el mapa?

- Muestra tres zonas delimitadas mediante polígonos sobre un mapa base de OpenStreetMap.
- Cada zona tiene un color distintivo:  
  - Zona 1: azul (#6063AA)  
  - Zona 2: celeste (#64BBC1)  
  - Zona 3: verde (#60B576)
- Al hacer clic en una zona, esta se resalta en amarillo (#BDD72E) y se desactiva el resaltado de las demás.
- El mapa está centrado en las coordenadas de A Coruña: `43.371048, -8.417363` con un nivel de zoom 14.

## 🌐 Despliegue

El mapa ha sido alojado en [Netlify](https://app.netlify.com/login), iniciando sesión con GitHub y seleccionando este repositorio como fuente.  
Una vez desplegado, se ha incrustado mediante un iframe en el dashboard del proyecto **ZBE**.

## 📁 Contenido del repositorio

- `index.html`: contiene todo el código necesario para visualizar el mapa, definir las zonas, y gestionar la interactividad.

## 🖼️ Ejemplo de incrustación

```html
<iframe src="https://TU_DOMINIO_NETLIFY.netlify.app" width="900" height="600" frameborder="0"></iframe>

```
---
## Licencia

Este proyecto se distribuye bajo la licencia **GNU**. Consulta [LICENSE](LICENSE).

