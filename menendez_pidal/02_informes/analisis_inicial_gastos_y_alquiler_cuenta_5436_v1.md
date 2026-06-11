# Análisis inicial gastos y alquiler cuenta 5436 v1

## Fuente
- Archivo: `/home/jero/cloud/02_proyectos/patrimonio_personal_jero/00_input/gastos_piso/resumen_movimientos_recurrentes_cuenta_5436_1.xlsx`
- Hojas detectadas:
  - `Resumen`
  - `Ingresos alquiler`
  - `Detalle clasificado`
  - `Puntuales y excluidos`
  - `Dudas pendientes`

---

## 1. Qué parece contener
El Excel no es un extracto bruto puro, sino una **primera capa ya trabajada/clasificada** de movimientos de la cuenta `5436` relacionados con el piso.

Periodo analizado en el propio archivo:
- **01/07/2024 a 05/06/2026**

Criterio declarado dentro del Excel:
- incluir solo lo **recurrente confirmado o detectado**
- excluir lo **puntual** y `TRANSF. A SU FAVOR`

---

## 2. Foto resumida que sale del propio Excel
### Gastos recurrentes estimados al año
- **5.229,46 € / año**
- estimación mensual: **435,79 € / mes**

### Ingresos alquiler recurrentes detectados
- **21.490,20 €**
- movimientos: **47**

### Ingreso puntual separado
- **1.412,00 €**
- etiquetado como: **fianza + prorrata agosto**

### Gastos recurrentes anuales estimados por categoría
- **Agua:** `444,39 € / año`
- **Luz:** `1.117,75 € / año`
- **Hipoteca/préstamo:** `2.646,24 € / año`
- **Seguro:** `541,08 € / año`
- **Comunidad:** `240,00 € / año`
- **Telefonía/internet:** `180,00 € / año`
- **Mantenimiento cuenta:** `60,00 € / año`

---

## 3. Lectura útil inicial
### Lo bueno
- el archivo ya viene bastante ordenado
- separa recurrente vs puntual
- separa ingresos de alquiler
- ya identifica varias dudas clave

### Lo que hay que tener presente
No es todavía una verdad contable final. Es una **clasificación operativa útil**, pero necesita validación en varios puntos antes de usarla como base fiscal cerrada.

---

## 4. Puntos que ahora mismo veo más delicados
### A. Lucía y German aparecen con ingresos de 1.200 €
En la hoja `Ingresos alquiler` figuran:
- **Lucía Tersoglio** → `6.000 €` en 5 movimientos → media `1.200 €`
- **German Cordero** → `3.600 €` en 3 movimientos → media `1.200 €`

Esto sugiere que esos ingresos podrían estar entrando como **transferencia agrupada del piso completo** o como cobro agregado, no como simple renta individual de habitación. Conviene confirmarlo.

### B. Comunidad no cuadra con el dato previo comunicado
En el trabajo anterior teníamos fijado:
- **comunidad: 30 €/mes**

Pero este Excel trabaja con:
- **20 €/mes**

Aquí hay una discrepancia clara que hay que cerrar.

### C. Hipoteca/préstamo tampoco cuadra del todo con el dato previo
Antes teníamos como referencia comunicada:
- **230 €/mes**

Este Excel usa:
- **220,52 €/mes**

Puede que:
- una fuera la cifra redondeada recordada
- y otra la cuota bancaria real

Pero conviene fijar cuál tomamos como válida.

### D. TransferWise necesita cierre prudente
El propio Excel reconoce duda sobre:
- **310,09 €** del `02/08/2024`

Parece poca cosa para el total, pero sí importa si queremos dejar fino el reparto por inquilino.

### E. Fianza + 21 días agosto = 1.412 €
Está bien separado, pero para lectura fiscal y de caja interesa desglosar:
- cuánto fue **fianza**
- cuánto fue **renta/prorrata**

### F. `TRANSF. A SU FAVOR` excluidas por 11.650 €
Bien excluidas por prudencia, pero conviene verificar que entre esas no haya:
- algún alquiler real
- o alguna regularización del piso

---

## 5. Mi lectura provisional de calidad
### Alta confianza
- estructura general del archivo
- categorías recurrentes principales
- utilidad como base de trabajo

### Confianza media
- reparto exacto por inquilino
- cuota real de comunidad
- cuota real de hipoteca/préstamo
- separación limpia entre ingreso recurrente y entrada agrupada

### Baja confianza / pendiente de aclarar
- desglose de `1.412 €`
- asignación exacta de algunos TransferWise
- certeza absoluta de que todo `TRANSF. A SU FAVOR` está bien excluido

---

## 6. Qué haría con este archivo
Lo tomaría como:
- **base operativa muy útil**
- pero no como cierre fiscal final todavía

Sirve muy bien para construir después:
1. cuadro real de ingresos del piso
2. cuadro real de gastos recurrentes
3. estimación de rendimiento ordinario
4. lista de dudas documentales a cerrar

---

## 7. Aclaraciones ya comunicadas por Jero
### Comunidad
- durante **2025** era **20 €/mes**
- el cambio a **30 €/mes** fue efectivo **a partir de enero de 2026**
- por tanto, para **2025** la cuota correcta a fijar es **20 €/mes**

### Hipoteca
- la cuota buena a fijar es **220,52 €/mes**

### Ingresos actuales de 1.200 €
- los ingresos de `1.200 €` no son la renta de una sola habitación
- corresponden a que los **cuatro contratos actuales** se unifican en **una sola transferencia**
- por tanto, Lucía/German no deben leerse aquí como pagadores individuales de 1.200 € por su habitación, sino como parte del sistema de cobro agrupado del piso

### Ingreso puntual de 1.412 €
- **1.200 €** = **fianza** (un mes)
- **212 €** = proporcional de agosto desde entrada al piso

### TransferWise 310,09 €
- sigue pendiente de atribución nominal totalmente segura
- Jero pide que se analice a partir del patrón

### `TRANSF. A SU FAVOR`
- Jero confirma que en esos aproximadamente `11.650 €` **no hay ningún alquiler**
- se mantienen **excluidas**

---

## 8. Lectura actualizada
Con estas aclaraciones, el Excel gana mucha más utilidad.

### Ya se puede fijar con bastante seguridad:
- **hipoteca real de referencia:** `220,52 €/mes`
- **comunidad histórica variable:** primero `20 €/mes`, ahora `30 €/mes`
- **fianza + prorrata agosto:** `1.200 € + 212 €`
- `TRANSF. A SU FAVOR` siguen fuera del análisis del alquiler
- los ingresos de `1.200 €` deben tratarse como **cobro agregado del piso**, no como renta individual por habitación

### Duda principal que queda viva en este archivo
- atribución más fina del **TransferWise 310,09 €**
- y, si se quiere dejar histórico perfecto, fecha exacta del cambio de comunidad de `20 €` a `30 €`

---

## 9. Conclusión
El Excel está bien y merece conservarse como pieza de control principal del piso para 2024-2026.
Con las aclaraciones de Jero, ya queda bastante más robusto para lectura económica y operativa.
Solo quedan pequeños cierres finos, no un problema estructural del archivo.
