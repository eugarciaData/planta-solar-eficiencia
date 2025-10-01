# Análisis de Pérdida de Eficiencia en Plantas Solares Fotovoltaicas

Este repositorio muestra un notebook con un análisis de Business Analytics aplicado a una compañía de generación de energía solar fotovoltaica.
El objetivo es detectar anomalías en la eficiencia de generación y proponer recomendaciones de mejora.

## Descripción

Durante el análisis se detectaron comportamientos anómalos en **2 de las plantas**.
Actualmente,  **no somos capaces de identificar el motivo**, por lo que este estudio busca aportar claridad mediante el análisis de datos de generación y variables ambientales.

## Conclusiones principales

Tras el análisis de los datos podemos concluir que:

- Existen **problemas de calidad de datos**; se recomienda revisar la cadena de medición.
- La **generación DC de la Planta 1** es muy alta comparada con la Planta 2, lo que sugiere posibles datos escalados. Se asume su validez por ahora.
- Ambas plantas recibieron buena irradiación; la **temperatura no impacta significativamente**.
- **DC Planta 1:** correcta. **DC Planta 2:** baja en algunos módulos.
- **AC Planta 1:** eficiencia baja (~10%), constante; posible problema estructural o de datos.
- **AC Planta 2:** funciona bien (>97% de eficiencia tras eliminar periodos cero).

## Recomendaciones

- Revisar la **captación y fiabilidad de los datos**.
- Revisar mantenimiento de **módulos/inverters en Planta 2** con generación DC cero.
- Revisar mantenimiento de **inverters en Planta 1**.

## Contenido del repositorio

- `notebook_final.ipynb`: Notebook con el análisis, gráficos y conclusiones.
- `README.md`: Este archivo con la descripción y resultados principales.