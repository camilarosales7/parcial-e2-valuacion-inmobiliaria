# Fuentes, licencia y preparación

I-Cheng Yeh (2018), Real Estate Valuation. UCI Machine Learning Repository.
Ficha: https://archive.ics.uci.edu/dataset/477/real+estate+valuation+data+set
DOI: https://doi.org/10.24432/C5J30W
Licencia: CC BY 4.0, https://creativecommons.org/licenses/by/4.0/
Consulta y descarga: 18/09/2026.

La cátedra convirtió el XLSX original a CSV, tradujo los nombres de columnas y agregó grupo de ubicación y asignación de pliegues. No alteró valores ni eliminó filas. Total: 414 transacciones. Desarrollo: 344 filas y 207 ubicaciones. Prueba: 70 filas y 52 ubicaciones. La reserva es el 20 % de grupos, redondeado hacia arriba, no exactamente el 20 % de filas.

Grupos por igualdad exacta de coordenadas; GroupShuffleSplit con semilla 42 para la reserva y GroupKFold de cinco pliegues para desarrollo. No equivale a un corte temporal ni a bloques geográficos completos. Las huellas de los CSV distribuidos se detallan abajo. En esta revisión no se encontró el archivo fuente XLSX ni el script original de preparación de E2; el procedimiento descrito es el registrado por la cátedra y se comprueban sus particiones sobre los CSV entregados.

SHA-256 de los CSV distribuidos:
- desarrollo.csv: 45105f76927356b5607632aebbaf5b4346565e4191eb69fed32fd7ee7101710c
- prueba.csv: 3310869a25d4b3cb3bf06c0ead84e5b687c3857d16207cd0950abccec1c5379a

Conservar la atribución al redistribuir los datos y señalar cambios posteriores. La licencia del dataset no implica aval del autor sobre este examen.
