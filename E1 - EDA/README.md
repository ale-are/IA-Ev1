# E1 - EDA Rendimiento Académico

Esta carpeta contiene los archivos correspondientes a la Evaluación 1 de
Análisis Exploratorio de Datos (EDA), enfocada en el diagnóstico de calidad,
análisis exploratorio y tratamiento de un dataset de rendimiento académico.

## Contenido

- `E1_EDA.ipynb`: Notebook con el desarrollo completo de la evaluación:
  carga de datos, diagnóstico de calidad, análisis exploratorio,
  preguntas de investigación, tratamiento de los datos, Pipeline,
  validación y exportación del dataset limpio.

- `E1_EDA_Presentacion.pptx`: Presentación utilizada para exponer los
  principales problemas encontrados, decisiones de tratamiento,
  resultados del EDA y estado final de los datos.

- `rendimiento_academico_evaluacion.csv`: Dataset original utilizado
  para realizar el análisis.

- `rendimiento_academico_limpio.csv`: Dataset resultante después del
  proceso de limpieza y tratamiento.

## Resumen del proceso

El trabajo contempla las siguientes etapas:

1. Carga del dataset.
2. Diagnóstico de calidad de los datos.
3. Análisis exploratorio de datos (EDA).
4. Identificación de valores faltantes, duplicados, inconsistencias,
   valores inválidos y valores atípicos.
5. Tratamiento de los problemas detectados.
6. Implementación de un proceso reproducible mediante `Pipeline` y
   `ColumnTransformer` de scikit-learn.
7. Validación del dataset tratado.
8. Exportación del dataset limpio.

## Resultado final

El dataset pasó de **5.100 a 4.996 registros**.

Después del tratamiento se obtuvieron:

- 0 valores faltantes.
- 0 registros duplicados.
- 0 valores fuera de dominio.
- Categorías normalizadas.
- Valores atípicos tratados mediante acotamiento basado en IQR.

El dataset final queda preparado para su utilización en futuros modelos
predictivos.
