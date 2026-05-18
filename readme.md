# Clustering Deforestación Colombia

Proyecto estático de presentación del análisis de clustering de deforestación en Colombia usando Orange.

## Descripción

Este sitio muestra un resumen visual y narrativo de un pipeline de Orange para análisis de deforestación en Colombia (2001–2024).
Incluye:
- Dataset con columnas de deforestación y emisiones.
- Workflow visual en Orange.
- Configuración de K-Means con k=4.
- Validación de calidad con Silhouette.
- Resultados y segmentos identificados.
- Visualizaciones de Box Plot, Scatter Plot y Heat Map.

## Estructura del proyecto

- `index.html` — página principal del proyecto.
- `readme.md` — documentación del proyecto.
- `screenshots/` — capturas de pantalla usadas en la página.

## Capturas incluidas

La carpeta `screenshots` contiene las imágenes usadas en la presentación:
- `p1_datatable.png`
- `p2_canvas.png`
- `p3_kmeans.png`
- `p4_silhouette.png`
- `p5_boxplot.png`
- `p6_scatter.png`
- `p7_tabla_c3.png`
- `p8_silhouette_tabla.png`
- `p10_heatmap.png`

## Cómo ver el sitio localmente

Solo abre `index.html` en un navegador moderno. No requiere servidor ni dependencias.

## Despliegue en GitHub Pages

1. Crea un repositorio en GitHub y súbelo con tu proyecto.
2. Asegúrate de que `index.html` esté en la raíz del repositorio.
3. En el repositorio de GitHub, ve a `Settings` → `Pages`.
4. En `Build and deployment`, selecciona `Deploy from a branch`.
5. Elige la rama `main` (o `master`) y la carpeta `/ (root)`.
6. Guarda y espera unos minutos: GitHub generará la URL de Pages.

### Alternativa con GitHub CLI

```bash
cd "c:/Users/juand/Desktop/Universidad 2026/Orange"
git init
git add .
git commit -m "Agregar sitio de Clustering Deforestación Colombia"
git branch -M main
git remote add origin https://github.com/<tu-usuario>/<tu-repo>.git
git push -u origin main
```

Luego configura GitHub Pages desde la página del repositorio.

## Notas

- Esta aplicación es estática; no necesita JavaScript adicional para mostrarse.
- Las capturas se cargan desde `screenshots/` mediante rutas relativas en `index.html`.
- Si quieres usar otra rama para Pages, selecciona la rama correcta en la configuración de GitHub.
