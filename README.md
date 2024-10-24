# Sistema de Recomendación - Recomendación de libros

## Descripción del Proyecto
Este proyecto se desarrolló como parte del segundo trabajo práctico en la materia de Data Mining. El objetivo principal fue implementar un sistema de recomendación para predecir si a un lector le gustará un libro en particular, basándose en la preferecia de lo lectores del sitio quelibroleo.com para ciertos usuarios y libros. A lo largo del desarrollo del proyecto, se utilizó una combinación de técnicas de web scraping y transformación de datos. Al igual que el primer trabajo práctico, el modelo no fue optimizado, ya que el foco principal estuvo en la preparación de los datos y el diseño del sistema de recomendación. Como metodo de evaluacion se creó una competencia en Kaggle (https://www.kaggle.com/competitions/fcen-dm-2024-recomendacion-de-libros) donde fuimos subiendo nuestros resultados. En dicha competencia podran encontrar los datos que se usaron para entrenar y predecir el modelo.

## Metodología

### Extracción de Datos (Web Scraping)

- **Obtención de Datos:** Se utilizó web scraping para recolectar información sobre libros y sus reseñas desde sitios web relevantes. El objetivo fue recopilar datos suficientes para entrenar el sistema de recomendación, incluyendo valoraciones de usuarios y metadatos de los libros.
- **Limpieza de Datos:** Posteriormente, los datos fueron limpiados para eliminar entradas duplicadas, valores faltantes o inconsistencias que pudieran afectar el modelo.

### Análisis Exploratorio de Datos

- **Visualización de los Datos:** Se realizaron gráficos para explorar la relación entre las valoraciones de los usuarios y las características de los libros, como género, autor y año de publicación.
- **Distribución de Preferencias:** Se analizaron las preferencias de los usuarios para entender mejor los patrones de comportamiento y lecturas frecuentes.

### Transformación de Datos

- **Codificación de Variables Categóricas:** Se realizó la transformación de variables categóricas, como géneros de libros y nacionalidad de los autores, a variables dummy para poder utilizarlas en el modelo.
- **Creación de Nuevas Características:** Se generaron nuevas variables derivadas de las valoraciones y comportamientos previos de los usuarios para enriquecer el dataset. Estas nuevas características ayudaron a capturar patrones más sutiles en las preferencias de lectura.
- **Normalización de Datos:** Los datos numéricos fueron escalados o normalizados para garantizar que todas las características tuvieran la misma relevancia en el modelo.

## Resultados y Conclusiones

A través de las distintas transformaciones de datos y la integración de las reseñas obtenidas por web scraping, el sistema de recomendación logró identificar patrones de preferencias de los usuarios. Si bien no se optimizó el modelo, los resultados obtenidos demostraron que la preparación adecuada de los datos es esencial para mejorar la calidad de las predicciones en sistemas de recomendación.

Este proyecto permitió explorar cómo las técnicas de transformación de datos y la obtención de datos externos pueden influir significativamente en el rendimiento de un sistema de recomendación.
