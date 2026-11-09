## 1.2 Diccionario incorporado

| Columna | Significado / unidad | Uso |
|---|---|---|
| `id_operacion` | Número de fila original | Identificación; nunca predictor |
| `fecha_decimal` | Fecha de transacción en la codificación numérica original | Predictor |
| `antiguedad_anios` | Antigüedad, años; cero admite un inmueble nuevo | Predictor |
| `distancia_mrt_m` | Distancia a la estación MRT más cercana, metros | Predictor |
| `comercios_cercanos` | Cantidad de comercios del entorno caminable | Predictor |
| `latitud`, `longitud` | Coordenadas, grados | Predictores |
| `precio_10mil_twd_ping` | Precio por superficie, en 10.000 TWD/ping | Objetivo |
| `grupo_ubicacion` | Código creado por la cátedra para coordenadas exactamente coincidentes | Sólo separación |
| `fold_validacion` | Pliegue (fold) de validación; columna presente sólo en desarrollo | Sólo separación; no predictor |

La cátedra renombró columnas y agregó campos de separación. No completó valores faltantes ni suavizó extremos. Las coordenadas coincidentes se mantienen juntas, pero **no identifican con certeza un edificio** ni eliminan toda dependencia entre lugares próximos.
