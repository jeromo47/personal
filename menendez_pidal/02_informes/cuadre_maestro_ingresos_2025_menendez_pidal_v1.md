# Cuadre maestro de ingresos 2025 - Menéndez Pidal v1

## Objetivo
Cuadrar la reconstrucción por habitación con la extracción ya trabajada del Excel de Unicaja (`resumen_movimientos_recurrentes_cuenta_5436_1.xlsx`), para separar:
- reconstrucción contractual teórica
- cobro recurrente realmente detectado en Unicaja
- ajustes puntuales no renta o no recurrentes

## Fuente bancaria usada
Archivo:
- `/home/jero/cloud/02_proyectos/patrimonio_personal_jero/00_input/gastos_piso/resumen_movimientos_recurrentes_cuenta_5436_1.xlsx`

Hoja relevante:
- `Ingresos alquiler`

## Lo que dice la hoja `Ingresos alquiler`
Resumen extraído:
- Juan José Iglesias López: `3.375,11 €` en `11` movimientos, desde `05/08/2024` hasta `03/06/2025`
- Andrea Centeno: `3.630,00 €` en `11` movimientos, desde `02/08/2024` hasta `03/07/2025`
- Erick Escoto: `3.410,09 €` en `12` movimientos, desde `02/08/2024` hasta `04/07/2025`
- Imadeddine Zerarka: `1.475,00 €` en `5` movimientos, desde `06/11/2024` hasta `04/03/2025`
- Lucía Tersoglio: `6.000,00 €` en `5` movimientos, desde `05/10/2025` hasta `08/02/2026`
- German Cordero: `3.600,00 €` en `3` movimientos, desde `10/03/2026` hasta `08/05/2026`
- total recurrente incluido en la hoja: `21.490,20 €`
- ingreso puntual separado: `1.412,00 €`, que en la reconstrucción final del expediente se relee como `812,00 €` de renta de agosto + `600,00 €` de fianza efectivamente ingresada en cuenta

## Criterio de lectura para 2025
### Etapa antigua 2025
Para 2025, la hoja bancaria permite fijar con bastante seguridad:
- Juanjo: enero-junio 2025 -> `6 x 310 = 1.860,00 €`
- Andrea: enero-julio 2025 -> `7 x 330 = 2.310,00 €`
- Erick: enero-julio 2025 -> `7 x 310 = 2.170,00 €`
- Imed: enero-marzo 2025 -> `3 x 295 = 885,00 €`

### Total etapa antigua 2025 según extracción bancaria resumida
- **`7.225,00 €`**

## Diferencia clave frente a la reconstrucción contractual previa
La reconstrucción contractual anterior (`extraccion_ingresos_por_habitacion_2025_menendez_pidal_v1.md`) daba:
- enero-julio 2025 = **`8.110,00 €`**

Pero el resumen de Unicaja apunta a un tramo antiguo 2025 más bien de:
- **`7.225,00 €`**

### Diferencia
- **`885,00 €`**

## Origen probable de la diferencia
La diferencia sale casi exactamente de:
- **Imed abril-junio 2025 = `295 x 3 = 885,00 €`**

Es decir:
- la reconstrucción contractual v1 asumía Imed hasta `30/06/2025`
- pero la extracción bancaria resumida de Unicaja solo le detecta ingresos hasta `04/03/2025`

## Lectura prudente
Con la aclaración posterior de Jero, abril-junio 2025 en la habitación 1 deben leerse como **vacante real desde abril 2025**, no como simple cobro no confirmado pendiente de aparecer.

## Tramo agosto 2025
Ya fijado y compatible con el expediente tras la última aclaración de Jero:
- ingreso visto en Unicaja: `1.412,00 €`
- renta prorrateada correcta de agosto: `812,00 €`
- fianza que sí entra en cuenta: `600,00 €` -> no renta
- importe restante sin factura válida: `600,00 €` -> fuera de gasto deducible, no ingreso

## Tramo septiembre-diciembre 2025
Base operativa ya fijada:
- `4 habitaciones x 300 € x 4 meses = 4.800,00 €`

## Cuadre operativo 2025 más coherente con Unicaja
### Ingreso recurrente etapa antigua validado por extracción resumida
- **`7.225,00 €`**

### Ajuste agosto 2025
- **`812,00 €`**

### Nueva etapa septiembre-diciembre 2025
- **`4.800,00 €`**

## Total operativo 2025 que mejor cuadra por ahora
- **`12.837,00 €`**

## Comparativa de totales
- reconstrucción contractual v1: `13.122,00 €`
- cuadre más coherente con extracción Unicaja resumida y agosto corregido: `12.837,00 €`
- diferencia: **`285,00 €`**

## Conclusión práctica
A día de hoy, si el objetivo es que el expediente cuadre mejor con la extracción ya hecha del Excel de Unicaja, la cifra de trabajo más sólida no es `13.122,00 €` sino:
- **`12.837,00 €`**

Y las dos correcciones principales introducidas son estas:
- **no computar abril-mayo-junio 2025 de Imed porque la habitación quedó vacante desde abril**
- **corregir agosto 2025 desde el neto erróneo de `212,00 €` a la renta prorrateada correcta de `812,00 €`**

## Siguiente cierre recomendado
Para dejarlo al céntimo todavía faltaría un segundo nivel:
1. leer el detalle movimiento a movimiento de la cuenta 5436 en 2025
2. asignar cada cobro a mes y habitación
3. usar ese detalle como refuerzo documental, no para reabrir la vacante de Imed ya aclarada por Jero

Hasta ese cierre fino, este documento debe tomarse como el mejor **cuadre intermedio prudente** entre contratos y Unicaja.
