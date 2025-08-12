# Mapacampanasdevidrio
Mapas interactivos de Medio Ambiente Chillán

# Mapa de Puntos de Interés

Este proyecto muestra un mapa interactivo con puntos de interés utilizando [Leaflet.js](https://leafletjs.com/) y un archivo GeoJSON.

## ¿Cómo funciona?

- **index.html** carga el mapa y los estilos.
- **campanas.geojson** contiene la ubicación y nombre de cada punto de interés.
- El mapa se centra automáticamente para mostrar todos los puntos.

## Ver el mapa en línea

> **Accede a tu mapa en:**  
> [https://pedrerosszk.github.io/REPO-NAME/](https://pedrerosszk.github.io/REPO-NAME/)

> _Reemplaza_ `REPO-NAME` _por el nombre real de tu repositorio._

## Estructura del repositorio

```
/
├── index.html
├── campanas.geojson
└── README.md
```

## Uso local

Si quieres probarlo localmente, utiliza un servidor local (por ejemplo, Python):

```bash
python -m http.server 8000
```

Y abre en tu navegador:  
[http://localhost:8000/](http://localhost:8000/)

## Personalización

- Para agregar o modificar puntos, edita el archivo `campanas.geojson`.
- Si necesitas otro tipo de marcador o popup, modifica el JavaScript en `index.html`.

---

**Hecho con [Leaflet.js](https://leafletjs.com/) y datos GeoJSON.**
