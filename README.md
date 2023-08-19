# CSV Data Toolkit

Este script bash te permite extraer, filtrar y procesar datos de archivos CSV de manera rápida y fácil. Si tienes que trabajar con archivos CSV, este script puede simplificar tu flujo de trabajo al permitirte seleccionar columnas específicas, eliminar duplicados y ordenar valores según tus requisitos.

## Características

- **Selección de Columnas:** Elige las columnas que deseas extraer de los datos del CSV.
- **Eliminación de Duplicados:** Filtra automáticamente los valores duplicados para mantener solo la información relevante.
- **Ordenación de Valores:** Ordena los datos de acuerdo con tus necesidades, ya sea de forma ascendente o descendente.
- **Personalización:** Ajusta las opciones del script para adaptarse a tus requerimientos particulares.

## Uso

1. Clona este repositorio o descarga el script `csv-parser.sh`.
2. Abre una terminal y navega hasta la ubicación del script.
3. Ejecuta el script con los parámetros adecuados. Por ejemplo:

   ```bash
   bash csv-parser.sh -c 2,3 -o output.txt -h -s asc data.csv

Esto seleccionará las columnas 2 y 3 del archivo data.csv, eliminará duplicados, ordenará en orden ascendente y guardará el resultado en output.txt.

## Parámetros

- -h: Indica si el archivo CSV tiene un encabezado (obligatorio).
- -o archivo_salida.txt: Archivo de salida (obligatorio).
- -c <num_columna1,num_columna2,...>: Números de columna para mostrar (opcional).
- -s asc|desc: Indica si hay que ordenar los valores (opcional).

## Requisitos

- Bash (compatible con la mayoría de las distribuciones de UNIX y Linux).

Si encuentras errores, tienes ideas para mejoras o deseas contribuir de alguna manera, ¡siéntete libre de hacerlo! Abre un problema o envía una solicitud de extracción.

## Licencia

Este script se distribuye bajo la Licencia GNU General Public License v3.0.
