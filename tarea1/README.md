# Tarea 1. Exploración avanzada de datos, PCA, regresión y análisis crítico multivariado

Machine Learning I, Especialización de Big Data y Analytics.

**Autora:** Maria Alejandra Colorado Ríos  
**Docente:** José Daniel Ramírez Soto  
**Entrega:** 23 de noviembre de 2026, 11:55 p. m.

## Qué hay

- [tarea1_exploracion_datos_022026_v1.docx](docs/tarea1_exploracion_datos_022026_v1.docx): documento de la entrega.
- [analisisCiudades.xlsx](docs/analisisCiudades.xlsx): datos de las 30 ciudades y las fórmulas del punto 1.1.
- [tarea1.ipynb](src/notebook/tarea1.ipynb): análisis en Python. Lee el Excel con la ruta `../../docs/analisisCiudades.xlsx`.
- [faces.zip](src/notebook/data/faces.zip): caras en escala de grises del punto 4. El notebook las lee desde `data/faces.zip` y solo descarga el archivo si no está.

El notebook se ejecuta desde su carpeta, `tarea1/src/notebook`.

## Avance

| Punto | Qué cubre |
| --- | --- |
| 1.1 | Media, mediana, desviación, moda y lectura de la desigualdad. |
| 1.2 | Boxplots y valores atípicos. |
| 1.3 | Covarianza entre PIB y población. |
| 1.4 | Correlación entre PIB y población. |
| 1.5 | Por qué la escala cambia la covarianza y no la correlación. |
| 1.6 | K-means con k = 4, sin librería de clustering, y perfil de cada grupo. |
| 1.7 | Dendrograma con enlace completo y comparación con el K-means. |
| 2.1 | Matriz de covarianza de PIB y población, y dispersión de las dos variables. |
| 2.2 | Eigenvalues. |
| 2.3 | Proporción de varianza que explica cada componente. |
| 2.4 | Eigenvector. |
| 2.5 | Proyección de cada ciudad en el primer componente. |
| 2.6 | Pérdida al reconstruir las dos variables con una sola dimensión. |
| 2.7 | Ciudades sobre una línea, en el primer componente. |
| 2.8 | Ciudades en dos dimensiones, con las variables numéricas estandarizadas. |
| 3.1 | Pendiente e intercepto del PIB sobre la población, sin librería de regresión, y su lectura económica y estadística. |
| 3.2 | Recta de regresión junto a las ciudades, y el residuo de cada una. |
| 4.1 | Cara promedio de las 1.300 caras de entrenamiento, cada una de 128 × 128. |
| 4.2 | PCA de las caras centradas, sin librería de PCA. El 95 % de la varianza pide 155 componentes y el 99 %, 466. Reconstrucción de las primeras cinco con 1, 3, 20, 155 y 466 componentes. |

Las gráficas se ven al ejecutar el notebook. No se guardan como archivo.

```
tarea1/
├── README.md
├── docs/
│   ├── analisisCiudades.xlsx
│   └── tarea1_exploracion_datos_022026_v1.docx
└── src/
    └── notebook/
        ├── tarea1.ipynb
        └── data/
            └── faces.zip
```
