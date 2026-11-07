# Benchmark de Rendimiento: CSV vs. Parquet

Este repositorio contiene los scripts en formato `.ipynb` y datos utilizados para evaluar y comparar la eficiencia de los formatos de archivo **CSV** y **Parquet** en operaciones de lectura, escritura, filtrado, agregación y uso de memoria RAM a escala (5M y 15M de registros).

## Resultados

- **Almacenamiento:** Parquet reduce el tamaño en disco en aproximadamente un **69%** respecto a CSV.
- **Escritura:** Parquet es entre **8.7× y 10.9× más rápido** al guardar archivos.
- **Consultas Selectivas:** Las operaciones de agregación sobre columnas específicas son hasta **26× más rápidas** con Parquet gracias a su formato columnar.
