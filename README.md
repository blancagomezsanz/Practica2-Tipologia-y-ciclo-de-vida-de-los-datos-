# Práctica 2 - Análisis y modelización de datos socioeconómicos provinciales

## Integrantes del grupo
- Carlos Gómez Domínguez
- Blanca Gómez Sanz

## Descripción del proyecto
Este repositorio contiene el desarrollo de la **Práctica 2** de la asignatura *Tipología y ciclo de vida de los datos*.  
El objetivo del proyecto ha sido construir y analizar un dataset integrado a nivel de provincias españolas, combinando múltiples fuentes oficiales del **Instituto Nacional de Estadística (INE)** junto con información estructural adicional.

El análisis se centra en estudiar las diferencias socioeconómicas entre provincias y modelar su nivel de desarrollo económico a partir de variables como PIB, empleo, paro, renta, turismo, empresas y demografía.

## Fuentes de datos

Los datos han sido obtenidos del Instituto Nacional de Estadística (INE):

- https://www.ine.es/

## Estructura del repositorio

- `README.md`: descripción general del proyecto.
- `requirements.txt`: librerías necesarias para ejecutar el código.
- `practica2_tipologia.ipynb`: Data cleanning, análisis exploratorio, modelización y pruebas estadísticas.
- `dataset/`
  - `*.csv/`: datasets originales descargados del INE.

## Librerías necesarias

Las dependencias del proyecto están recogidas en el archivo `requirements.txt`.

Instalación:

```bash
pip install -r requirements.txt