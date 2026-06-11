# Estado inicial reforma Menéndez Pidal v1

## Objetivo
Abrir una pieza específica para recopilar, ordenar y analizar todas las facturas y costes de la obra/reforma del piso de Menéndez Pidal.

La finalidad será doble:
- reconstruir cuánto se gastó realmente
- y analizar después si alguna parte tiene utilidad fiscal, patrimonial o de mejora del tratamiento del inmueble

---

## Estado inicial
- Jero va a aportar facturas de la obra/reforma del piso
- ya se ha cargado un **primer lote documental** con presupuestos, facturas de materiales/obra y un certificado de trabajos realizados
- existe ya una primera nota de lote y un primer CSV de control

### Lotes ya archivados
#### Lote 01
- Input: `/home/jero/cloud/02_proyectos/patrimonio_personal_jero/00_input/reforma_menendez_pidal/lote_2026_06_07_01/`
- Control: `/home/jero/cloud/02_proyectos/patrimonio_personal_jero/01_control/reforma_menendez_pidal_lote_2026_06_07_01.csv`
- Nota: `/home/jero/cloud/02_proyectos/patrimonio_personal_jero/02_informes/reforma/nota_lote_2026_06_07_01_v1.md`

#### Lote 02
- Input: `/home/jero/cloud/02_proyectos/patrimonio_personal_jero/00_input/reforma_menendez_pidal/lote_2026_06_07_02/`
- Control: `/home/jero/cloud/02_proyectos/patrimonio_personal_jero/01_control/reforma_menendez_pidal_lote_2026_06_07_02.csv`
- Nota: `/home/jero/cloud/02_proyectos/patrimonio_personal_jero/02_informes/reforma/nota_lote_2026_06_07_02_v1.md`

---

## Ruta de trabajo
### Input
- `/home/jero/cloud/02_proyectos/patrimonio_personal_jero/00_input/reforma_menendez_pidal/`

### Informes
- `/home/jero/cloud/02_proyectos/patrimonio_personal_jero/02_informes/reforma/`

---

## Qué conviene recoger de cada factura
- proveedor
- fecha
- concepto
- base imponible
- IVA
- total
- forma de pago si consta
- si parece:
  - reparación / conservación
  - mejora / reforma
  - mobiliario / equipamiento
  - electrodoméstico
  - decoración
  - gasto dudoso

---

## Estado de consolidación actual
Ya existen piezas de control separadas para:
- lotes documentales recibidos
- reconstrucción de pagos a SB
- y estado de soporte bancario/documental

### Documentos clave ya creados
- `nota_lote_2026_06_07_01_v1.md`
- `nota_lote_2026_06_07_02_v1.md`
- `aclaraciones_usuario_reforma_2026_06_07_v1.md`
- `reconstruccion_pagos_sb_v1.md`
- `estado_pago_y_soporte_reforma_menendez_pidal_v1.md`

## Meta futura
Una vez cargadas todas las facturas y justificantes, construir:
1. tabla maestra final de reforma
2. suma total invertida depurada
3. clasificación por tipo de gasto
4. cruce entre gasto, pago y soporte documental
5. nota fiscal/práctica sobre qué podría servir y qué no
