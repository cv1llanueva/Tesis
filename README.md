# Tesis

Este repositorio contiene los archivos y modelos utilizados para la tesis sobre la estimación del margen de estabilidad de tensión en sistemas eléctricos mediante redes neuronales convolucionales (CNN) y su comparación con otros modelos tradicionales.

## Contenido del Repositorio

### Archivos Principales

- **TESIS-FINAL.ipynb**: 
  Contiene el modelo final desarrollado para el sistema IEEE de 13 barras. Incluye:
  - Entrenamiento del modelo CNN.
  - Comparación del rendimiento del modelo CNN con otros métodos tradicionales como ANN, RF, SVM y DT.

- **SISTEMA GRANDE.ipynb**: 
  Modelo implementado para el sistema IEEE de 39 barras. Este archivo incluye simulaciones más complejas para sistemas eléctricos de mayor escala.

### Carpetas de Arquitectura Modificada

- **ARQUI 3**, **ARQUI 4**, **ARQUI 5**: 
  Contienen variantes del modelo CNN con diferentes arquitecturas aplicadas al sistema IEEE de 13 barras. Estas modificaciones se realizaron para analizar el impacto de la arquitectura de la red en la precisión del modelo.

- **ARQUITECTURA** y **ARQUITECTURA CON DIFERENTES CAPAS**: 
  Exploración de diversas configuraciones de la red CNN utilizadas en el sistema IEEE de 13 barras.

### Otras Carpetas

- **SISTEMA DE 39 BARRAS**: 
  Archivos y datos relacionados específicamente con las simulaciones y modelos desarrollados para el sistema IEEE de 39 barras.

- **DATASET**: 
  Contiene los datos utilizados para el entrenamiento y validación de los modelos. Los datos incluyen tensiones, ángulos de voltaje, potencia activa y reactiva, y el margen de cargabilidad calculado.

## Notas

Este repositorio proporciona una base completa para replicar los experimentos realizados en la tesis, abarcando tanto sistemas pequeños (IEEE 13 barras) como sistemas más grandes y complejos (IEEE 39 barras). Los ajustes en la arquitectura de los modelos CNN y las comparaciones con métodos tradicionales están documentados en sus respectivos archivos.

¡Gracias por visitar este repositorio!
