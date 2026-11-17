# Noticias de Panamá (datos abiertos)

Registro diario de noticias de Panamá y de cifras de malaria, buscado y clasificado automáticamente por Claude.
Los titulares y resúmenes están redactados con palabras propias; cada fila enlaza a la nota original.

- `data/noticias.geojson`: noticias como puntos (centro aproximado de la provincia o región).
- `data/malaria.geojson`: cifras de casos de malaria del Minsa o citadas por medios.

Cada mañana (hora de Panamá) se publican aquí las filas agregadas en los últimos días; un Data Pipeline de ArcGIS Online las agrega o actualiza en una capa alojada usando el campo `id`.
