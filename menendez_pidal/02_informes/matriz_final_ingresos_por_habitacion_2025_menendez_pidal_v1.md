# Matriz final de ingresos por habitación 2025 - Menéndez Pidal v1

## Archivo principal
- `matriz_final_ingresos_por_habitacion_2025_menendez_pidal_v1.csv`

## Objetivo
Blindar el expediente frente a revisión, separando por habitación y por mes:
- ocupación
- renta devengada
- cobro bancario
- fianza
- y criterio de ingreso fiscal final

## Criterios usados
1. **Unicaja manda** para los cobros confirmados.
2. **Imed** se trata como salida en fecha y **vacante desde abril 2025**.
3. **Agosto 2025** se trata con criterio corregido:
   - renta total etapa nueva: **`812,00 €`**
   - fianza efectivamente ingresada en cuenta: **`600,00 €`**
   - ingreso total visto en Unicaja: **`1.412,00 €`**
4. El importe restante de `600,00 €` vinculado a la agencia **no se mete como gasto deducible** por falta de factura válida.
5. Desde septiembre 2025 el cobro bancario es **agrupado** (`1.200 €/mes`), por lo que la matriz distingue entre:
   - filas por habitación con renta devengada
   - y filas `GLOBAL` para el cobro efectivo agrupado del piso

## Totales de trabajo que soporta la matriz
- tramo antiguo enero-julio: **`7.225,00 €`**
- agosto 2025: **`812,00 €`**
- septiembre-diciembre 2025: **`4.800,00 €`**
- **total 2025: `12.837,00 €`**

## Advertencia útil para asesor
Las filas por habitación de la etapa nueva sirven para reconstrucción contractual y fiscal por habitación.

Las filas `GLOBAL` son las que reflejan el **cobro bancario agrupado real** del piso en la nueva etapa.

Por tanto, esta matriz está pensada para:
- defender el cuadre de ingresos
- separar fianza de renta
- y facilitar luego el prorrateo del tramo nuevo para la reducción del 50 %.
