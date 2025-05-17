# Análisis de Datos de Tiendas

Este proyecto realiza un análisis exploratorio de datos de ventas de cuatro tiendas. El objetivo es proporcionar información sobre las características de los datos, identificar tendencias clave y comparar el rendimiento entre las tiendas.

## Estructura del Proyecto

El proyecto se organiza en un cuaderno de Jupyter (`AluraStoreLatam.ipynb`) que contiene el código y el análisis.

## Datos

Los datos se obtienen de cuatro archivos CSV, uno por cada tienda, alojados en el siguiente repositorio de GitHub:

* [https://github.com/alura-es-cursos/challenge1-data-science-latam/tree/refs/heads/main/base-de-datos-challenge1-latam](https://github.com/alura-es-cursos/challenge1-data-science-latam/tree/refs/heads/main/base-de-datos-challenge1-latam)

Cada archivo CSV contiene información sobre las ventas, incluyendo:

* Producto
* Categoría del Producto
* Precio
* Costo de envío
* Fecha de Compra
* Vendedor
* Lugar de Compra
* Calificación
* Método de pago
* Cantidad de cuotas
* lat (latitud)
* lon (longitud)

## Dependencias

El proyecto utiliza las siguientes bibliotecas de Python:

* `pandas`
* `matplotlib`
* `seaborn`
* `numpy`
* `logging`
* `dataclasses`
* `IPython`

Se puede instalar las dependencias usando pip:

```bash
pip install pandas matplotlib seaborn numpy
```

