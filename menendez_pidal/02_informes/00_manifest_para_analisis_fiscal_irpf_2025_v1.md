# Manifest para analisis fiscal IRPF 2025 - Menendez Pidal v1

## Objetivo del archivo

Este archivo sirve como briefing maestro para entregar el expediente de Menendez Pidal a Claude, ChatGPT u otro analista fiscal/documental.

No sustituye al analisis fiscal final. Su funcion es indicar:

1. que documentacion existe,
2. que informes previos existen,
3. que piezas son fuertes,
4. que piezas son provisionales,
5. que contradicciones hay,
6. que documentos faltan,
7. que paquete minimo debe entregarse para un analisis serio del IRPF 2025.

---

## Regla de privacidad

El expediente contiene informacion personal, bancaria, inmobiliaria y fiscal. Si se sube a GitHub, el repositorio debe ser privado.

Antes de pasar documentos a otro modelo, conviene anonimizar o tapar, si no es necesario para el analisis:

- DNI completo.
- Numeros de cuenta completos.
- Telefonos.
- Emails personales.
- Firmas.
- Datos personales completos de inquilinos.

Para el analisis fiscal, normalmente basta con mantener:

- fechas,
- importes,
- conceptos,
- inmueble,
- relacion con el alquiler,
- identidad de pagador/inquilino si es necesaria para cuadrar ingresos.

---

## Foto general del expediente

### Inmueble

- Inmueble: Calle Menendez Pidal 52, Almeria.
- Referencia catastral localizada: 9383002WF4798S0058SY.
- Finca registral: 909.
- Registro: Almeria numero 5.
- Superficie construida registral: 81,48 m2.
- Superficie util: 66,31 m2.
- Superficie catastral simplificada: 81 m2.
- Ano de construccion catastral: 1974.

Documento resumen principal:

- `menendez_pidal/02_informes/ficha_maestra_inmueble_menendez_pidal_v1.md`

---

## Documentos e informes ya localizados en GitHub

### 1. Ficha maestra

Archivo:

- `menendez_pidal/02_informes/ficha_maestra_inmueble_menendez_pidal_v1.md`

Utilidad:

- Documento de sintesis del inmueble.
- Resume compra, hipoteca, seguro, tasacion, catastro, datos economicos durables y pendientes.

Estado:

- FUERTE como indice interno.
- No sustituye documentos originales.

---

### 2. Compra / adquisicion

Archivos relevantes:

- `menendez_pidal/02_informes/extraccion_lote_documental_menendez_pidal_2026_03_v1.md`
- `menendez_pidal/02_informes/extraccion_lote_documental_menendez_pidal_2026_03_b_v1.md`
- `menendez_pidal/02_informes/extraccion_modelo_600_compra_menendez_pidal_v1.md`

Documentos fuente que deberian incluirse en el ZIP final:

- Escritura de compraventa.
- Escritura de hipoteca.
- Contrato de arras.
- Modelo 600 / justificante de pago ITPAJD.
- Tasacion.
- Catastro.
- Nota simple precompra.
- Si existe, nota simple actualizada postcompra.

Datos ya trabajados:

- Compra: 27/07/2023.
- Precio compraventa: 64.000,00 EUR.
- Arras: 3.200,00 EUR.
- Resto: 60.800,00 EUR.
- Modelo 600 presentado el 21/09/2023.
- Base declarada / valor referencia: 71.350,88 EUR.
- Tipo aplicado: 3,50%.
- Cuota ingresada: 2.497,28 EUR.

Estado:

- FUERTE para adquisicion si se adjuntan los PDFs originales.
- PROVISIONAL para amortizacion si no se adjunta calculo final suelo/construccion y base amortizable definitiva.

Pendiente:

- Nota simple postcompra.
- Facturas de notaria, registro y gestoria si existen.
- Criterio final de base amortizable.

---

### 3. Hipoteca

Archivos relevantes:

- `menendez_pidal/02_informes/extraccion_lote_documental_menendez_pidal_2026_03_v1.md`
- `menendez_pidal/02_informes/extraccion_intereses_hipoteca_y_recibo_2026_v1.md`
- `menendez_pidal/02_informes/ficha_maestra_inmueble_menendez_pidal_v1.md`

Documentos fuente que deberian incluirse:

- Escritura de hipoteca.
- FEIN si esta disponible.
- Resumen anual de intereses 2025 de Unicaja.
- Recibos hipotecarios 2025 si existen.
- Recibos de 2026 usados como soporte auxiliar.
- Certificado de deuda pendiente 2026 como soporte patrimonial, no como gasto 2025.

Datos ya trabajados:

- Entidad: Unicaja.
- Principal: 54.000,00 EUR.
- Plazo: 360 meses.
- Cuota inicial: 220,52 EUR/mes.
- Primer periodo: 36 meses al 2,750% fijo.
- Cuenta asociada: terminada en 5436.
- Cuota total 2025 detectada: 2.646,24 EUR.
- Intereses 2025 localizados: 1.423,76 EUR.

Estado:

- FUERTE para identificar prestamo y condiciones.
- FUERTE/PROVISIONAL para intereses 2025: hay resumen anual bancario, pero se indica que no tiene validez fiscal perfecta.

Pendiente:

- Si existe, certificado fiscal formal de intereses 2025.
- Si no existe, conservar resumen anual bancario y recibos.

Criterio para el analista:

- No deducir la cuota hipotecaria completa.
- Separar intereses deducibles de amortizacion de principal.

---

### 4. Catastro / IBI / Nota simple / Tasacion

Archivos relevantes:

- `menendez_pidal/02_informes/extraccion_lote_documental_menendez_pidal_2026_03_b_v1.md`
- `menendez_pidal/02_informes/nota_fiscal_inicial_alquiler_menendez_pidal_v1.md`
- `menendez_pidal/02_informes/base_fiscal_2025_menendez_pidal_v2_casi_lista_para_declarar.md`

Documentos fuente que deberian incluirse:

- Catastro.
- IBI 2025.
- Tasacion.
- Nota simple precompra.
- Nota simple postcompra si se obtiene.

Datos ya trabajados:

- IBI 2025: 256,26 EUR.
- Valor catastral total localizado en informe previo: 42.010,31 EUR.
- Valor suelo localizado: 25.571,48 EUR.
- Valor construccion localizado: 16.438,83 EUR.
- Tasacion: 70.035,33 EUR.
- Valor suelo en tasacion: 25.268,58 EUR.
- Valor seguro reconstruccion: 74.000,95 EUR.

Estado:

- FUERTE para identificacion del inmueble y gasto IBI si se adjunta PDF original.
- PROVISIONAL para amortizacion hasta que el analista valide que valor usar: adquisicion vs catastro, y porcentaje suelo/construccion.

Pendiente:

- Nota simple actualizada postcompra.
- Calculo final de amortizacion inmueble.

---

### 5. Seguro CASER

Archivos relevantes:

- `menendez_pidal/02_informes/extraccion_condiciones_particulares_seguro_caser_menendez_pidal_v1.md`
- `menendez_pidal/02_informes/extraccion_recibo_seguro_caser_menendez_pidal_v1.md`
- `menendez_pidal/02_informes/extraccion_lote_documental_menendez_pidal_2026_03_b_v1.md`
- `menendez_pidal/02_informes/ficha_maestra_inmueble_menendez_pidal_v1.md`

Documentos fuente que deberian incluirse:

- Condiciones particulares CASER.
- Recibo o justificante de pago del seguro.
- Extractos bancarios donde se cargue el seguro.
- Si existe, certificado de coberturas.

Datos ya trabajados:

- Poliza: 96560081.
- Fecha efecto: 27/07/2023.
- Fecha vencimiento: 27/07/2026.
- Producto: Hogar trianual clientes / Hogar Proteccion.
- Continente: 75.000 EUR.
- Contenido/mobiliario: 18.000 EUR.
- Total visible del tramo trianual: aprox. 994,08 EUR - 1.007,77 EUR, segun documento.
- Coste anual equivalente orientativo: 331-336 EUR/ano.
- En base 2025 solo aparecen cargos por 135,28 EUR.

Riesgos detectados:

- Uso declarado en poliza: residencia habitual.
- Uso real actual: alquiler por habitaciones.
- Superficie declarada al seguro: 98 m2.
- Superficie registral/catastral: aprox. 81 m2.
- El importe 2025 detectado en extractos parece incompleto frente al coste trianual.

Estado:

- PROVISIONAL para IRPF hasta decidir criterio de devengo/pago/prorrateo.
- DUDOSO si solo se usa el importe parcial de 135,28 EUR sin explicar por que.

Pendiente:

- Confirmar coste imputable a 2025.
- Confirmar si debe prorratearse el seguro trianual.
- Revisar si el uso declarado en poliza debe actualizarse.

---

### 6. Ingresos de alquiler 2025

Archivos relevantes:

- `menendez_pidal/02_informes/base_fiscal_2025_menendez_pidal_v1.md`
- `menendez_pidal/02_informes/base_fiscal_2025_menendez_pidal_v2_casi_lista_para_declarar.md`
- `menendez_pidal/02_informes/resumen_operativo_irpf_menendez_pidal_v1.md`
- `menendez_pidal/02_informes/estado_inicial_alquiler_menendez_pidal_v1.md`

Documento fuente esencial:

- `resumen_movimientos_recurrentes_cuenta_5436_1.xlsx`

Datos ya trabajados:

- Ingresos recurrentes 2025 detectados: 10.825,00 EUR.
- Ingreso puntual 1.412,00 EUR separado en:
  - fianza: 1.200,00 EUR.
  - prorrata agosto: 212,00 EUR.
- Transferencias `TRANSF. A SU FAVOR` por 11.650 EUR excluidas del alquiler por instruccion previa.
- En la fase final del ano aparece patron de 1.200 EUR/mes.

Riesgos y pendientes:

- Agosto y septiembre 2025 aparecen sin ingresos recurrentes en la base.
- Confirmar si los 212 EUR de prorrata de agosto ya estan incluidos o deben anadirse.
- Confirmar que la fianza de 1.200 EUR no se trato como renta ordinaria.
- Cruzar contratos por habitacion con cobros reales.
- Revisar cobros sin contrato y contratos sin cobro.

Estado:

- PROVISIONAL/FUERTE si se adjunta Excel clasificado + extractos bancarios + contratos.
- PROVISIONAL si solo se adjuntan informes, sin Excel ni extractos.

---

### 7. Contratos de alquiler por habitaciones

Archivos relevantes:

- `menendez_pidal/02_informes/estado_inicial_alquiler_menendez_pidal_v1.md`
- `menendez_pidal/02_informes/historico_contractual_menendez_pidal_2024_2025_v1.md`
- `menendez_pidal/02_informes/nota_fiscal_inicial_alquiler_menendez_pidal_v1.md`

Documentos fuente que deberian incluirse:

- Contratos actuales 2025/2026 de todas las habitaciones.
- OCR o texto extraido de cada contrato.
- Contratos historicos solo si realmente corresponden al mismo inmueble o si se usan como comparativa contractual.
- Tabla de ocupantes por habitacion y fechas.
- Comunicaciones o declaraciones responsables si se quiere defender vivienda habitual.

Contradiccion critica:

- El archivo de historico contractual 2024-2025 dice que los contratos historicos hacen referencia a `Calle Antonio Cano, 51, 3o-2, Almeria`, no a Menendez Pidal.
- Por tanto, esos contratos NO deben usarse como soporte directo de ingresos/gastos de Menendez Pidal sin aclaracion.
- Pueden servir como comparativa de modelo contractual anterior, pero no como prueba directa del inmueble Menendez Pidal.

Riesgos:

- Diferencia entre modelo historico temporal/Codigo Civil y modelo actual vivienda habitual/LAU.
- Cobro unico de 1.200 EUR con suministros/WiFi incluidos.
- Falta de separacion renta vs suministros.
- Falta de prueba de uso como vivienda habitual si se pretende aplicar reduccion fiscal.

Estado:

- DUDOSO para defensa de reduccion fiscal si no se adjuntan todos los contratos actuales y prueba de uso real.
- PROVISIONAL para ingresos si solo se trabaja con extractos.

---

### 8. Suministros, comunidad, internet y cuenta bancaria

Archivos relevantes:

- `menendez_pidal/02_informes/base_fiscal_2025_menendez_pidal_v1.md`
- `menendez_pidal/02_informes/base_fiscal_2025_menendez_pidal_v2_casi_lista_para_declarar.md`
- `menendez_pidal/02_informes/resumen_operativo_irpf_menendez_pidal_v1.md`

Documento fuente esencial:

- `resumen_movimientos_recurrentes_cuenta_5436_1.xlsx`
- Extractos bancarios 2025 de la cuenta 5436.
- Facturas de suministros, si existen.

Datos 2025 ya trabajados:

- Agua: 362,03 EUR.
- Luz: 633,50 EUR.
- Comunidad: 240,00 EUR.
- Internet/telefonia: 144,03 EUR.
- Mantenimiento de cuenta: 60,00 EUR.

Estado:

- Agua/luz/comunidad: FUERTE si hay extracto + factura/recibo o contrato que pruebe que los asume arrendador.
- Internet: PROVISIONAL, defendible si el alquiler incluye WiFi.
- Mantenimiento de cuenta: PROVISIONAL/DUDOSO, defendible si la cuenta esta funcionalmente dedicada al inmueble.

Pendiente:

- Facturas de luz, agua, internet.
- Recibos de comunidad o certificado administrador.
- Confirmar que suministros estaban incluidos en renta.

---

### 9. Reforma / obra / materiales / equipamiento

Archivos relevantes:

- `menendez_pidal/02_informes/reforma/estado_inicial_reforma_menendez_pidal_v1.md`
- `menendez_pidal/02_informes/reforma/nota_lote_2026_06_07_01_v1.md`
- `menendez_pidal/02_informes/reforma/nota_lote_2026_06_07_02_v1.md`

Documentos fuente que deberian incluirse:

- Factura principal Multiservicios SB 014/2024.
- Certificado de trabajos realizados de Multiservicios SB.
- Factura fontaneria SB 006/2023.
- Presupuesto SB R 012/2023.
- Facturas Obramat.
- Pedidos web Obramat.
- Anticipos Obramat.
- Justificantes bancarios de pago a contratista.
- Tabla de cruce factura-pago.
- CSVs de control de lotes.
- Fotos antes/despues si existen.

Datos ya trabajados:

- Factura principal SB 014/2024: 16.335,00 EUR IVA incluido.
- Base: 13.500,00 EUR.
- IVA: 2.835,00 EUR.
- Conceptos: reforma general en bano, muros pladur, alisado paredes, suelo parquet, pintura.
- Factura fontaneria SB 006/2023: 181,50 EUR.
- Obramat lote 01 utilizable provisional: 444,72 EUR, evitando duplicar anticipos.
- Obramat lote 02 facturas cerradas nuevas: 16.697,77 EUR incluyendo la factura principal SB y dos facturas Obramat.
- Hay anticipos relevantes pendientes de netear, incluido un anticipo Obramat de 4.803,37 EUR.

Aclaracion importante ya fijada:

- No hubo ampliacion de superficie.
- Si hubo creacion de una habitacion nueva.
- Si hubo transformacion de un bano anterior en dos banos completos.
- Si hubo reconfiguracion interior del salon hacia habitacion + pasillo/comedor.

Riesgo fiscal principal:

- No conviene tratar toda la obra como conservacion pura.
- Hay que separar:
  - reparacion/conservacion,
  - mejora/reconfiguracion,
  - mobiliario/equipamiento,
  - simples anticipos,
  - documentos que son presupuesto y no factura,
  - pagos sin factura,
  - facturas sin pago.

Estado:

- FUERTE: factura SB 014/2024 si se adjunta original y pago.
- PROVISIONAL: tratamiento fiscal de la obra.
- DUDOSO: anticipos Obramat sin cruce con factura final.
- EXCLUIBLE: presupuestos no facturados o importes duplicados.

Pendiente:

- Tabla maestra final de reforma.
- Cruce completo de facturas vs pagos.
- Clasificacion fiscal partida a partida.
- Separacion gasto corriente vs mejora/amortizacion.

---

## Que debe pasarse a Claude / ChatGPT para el analisis final

### Paquete minimo obligatorio

Entregar una carpeta ZIP con esta estructura:

```text
00_BRIEFING/
  00_manifest_para_analisis_fiscal_irpf_2025_v1.md
  prompt_analisis_fiscal_irpf_2025.md

01_INFORMES_PREVIOS/
  ficha_maestra_inmueble_menendez_pidal_v1.md
  base_fiscal_2025_menendez_pidal_v2_casi_lista_para_declarar.md
  resumen_operativo_irpf_menendez_pidal_v1.md
  nota_fiscal_inicial_alquiler_menendez_pidal_v1.md
  estado_inicial_alquiler_menendez_pidal_v1.md
  historico_contractual_menendez_pidal_2024_2025_v1.md

02_COMPRA_ADQUISICION/
  escritura_compraventa.pdf
  contrato_arras.pdf
  modelo_600_itp.pdf
  tasacion.pdf
  catastro.pdf
  nota_simple_precompra.pdf
  nota_simple_postcompra_si_existe.pdf
  facturas_notaria_registro_gestoria_si_existen.pdf

03_HIPOTECA/
  escritura_hipoteca.pdf
  fein.pdf
  resumen_anual_intereses_unicaja_2025.pdf
  recibos_hipoteca_2025_si_existen.pdf
  recibos_hipoteca_2026_soporte_auxiliar.pdf
  certificado_deuda_pendiente_2026.pdf

04_SEGURO_CASER/
  condiciones_particulares_caser.pdf
  recibo_seguro_caser.pdf
  extractos_cargos_seguro_2025.pdf
  certificado_coberturas_si_existe.pdf

05_INGRESOS_ALQUILER_2025/
  resumen_movimientos_recurrentes_cuenta_5436_1.xlsx
  extractos_bancarios_2025_cuenta_5436.pdf_o_xlsx
  tabla_ingresos_2025_si_existe.xlsx
  justificantes_transferencias_inquilinos_si_existen.pdf

06_CONTRATOS_HABITACIONES/
  contratos_actuales_2025_2026_todas_habitaciones.pdf
  ocr_contratos_actuales.md_o_txt
  tabla_ocupacion_por_habitacion_2025.xlsx_o_md
  declaraciones_responsables_vivienda_habitual_si_existen.pdf
  contratos_historicos_solo_si_corresponden_o_para_comparativa.pdf

07_GASTOS_RECURRENTES_2025/
  facturas_luz_2025.pdf
  facturas_agua_2025.pdf
  facturas_internet_2025.pdf
  recibos_comunidad_2025.pdf
  ibi_2025.pdf
  extractos_pagos_gastos_2025.pdf

08_REFORMA_OBRA_EQUIPAMIENTO/
  factura_SB_014_2024.pdf
  certificado_trabajos_SB.pdf
  factura_SB_006_2023_fontaneria.pdf
  facturas_obramat.pdf
  pedidos_web_obramat.pdf
  justificantes_pago_contratista.pdf
  justificantes_pago_obramat.pdf
  csv_control_lote_01.csv
  csv_control_lote_02.csv
  fotos_antes_despues_si_existen.pdf_o_zip
  tabla_maestra_reforma_si_existe.xlsx_o_csv

09_CONTROL/
  tabla_cruce_factura_pago.xlsx_o_csv
  tabla_gastos_excluidos.xlsx_o_csv
  tabla_amortizaciones.xlsx_o_csv
  dudas_pendientes.md
```

---

## Archivo que falta generar o completar antes del analisis final

El archivo mas importante que falta es una **tabla maestra de cierre** en Excel/CSV.

Nombre recomendado:

- `tabla_maestra_irpf_2025_menendez_pidal.xlsx`

Hojas recomendadas:

1. `00_indice_documental`
2. `01_ingresos_2025`
3. `02_gastos_recurrentes_2025`
4. `03_hipoteca_intereses`
5. `04_seguro`
6. `05_reforma_facturas`
7. `06_reforma_pagos`
8. `07_cruce_factura_pago`
9. `08_mobiliario_equipamiento`
10. `09_amortizaciones`
11. `10_gastos_dudosos_excluidos`
12. `11_riesgos_y_pendientes`

Columnas minimas para ingresos:

```text
fecha | pagador | habitacion | concepto | importe | renta/fianza/suministro/otro | documento_soporte | cuenta | incluido_IRPF_si_no | observaciones
```

Columnas minimas para gastos:

```text
fecha | proveedor | concepto | bloque | importe | IVA | total | documento_soporte | pago_soporte | tratamiento_propuesto | fuerza_probatoria | riesgo | accion_recomendada
```

Columnas minimas para reforma:

```text
fecha | proveedor | factura/pedido/presupuesto | concepto | importe | tipo_documento | pagado_si_no | pago_cruzado | clasificacion_fiscal | gasto_directo_si_no | amortizable_si_no | excluible_si_no | observaciones
```

Clasificacion obligatoria:

- FUERTE.
- PROVISIONAL.
- DUDOSO.
- EXCLUIBLE.

---

## Faltantes criticos antes de pedir analisis fiscal final

### Imprescindibles

1. Excel clasificado real:
   - `resumen_movimientos_recurrentes_cuenta_5436_1.xlsx`.

2. Extractos bancarios 2025 de la cuenta 5436.

3. IBI 2025 original.

4. Resumen anual de intereses 2025 Unicaja o certificado fiscal formal si existe.

5. Contratos actuales de todas las habitaciones.

6. Tabla de ocupacion por habitacion y fechas de entrada/salida.

7. Factura SB 014/2024 original.

8. Justificantes de pago al contratista SB.

9. Facturas Obramat originales y pedidos vinculados.

10. Tabla de cruce factura-pago de reforma.

### Muy recomendables

1. Recibos/facturas luz 2025.
2. Recibos/facturas agua 2025.
3. Facturas internet 2025.
4. Recibos comunidad 2025 o certificado administrador.
5. Condiciones particulares CASER y recibo imputable a 2025.
6. Nota simple postcompra.
7. Facturas de notaria, registro y gestoria.
8. Fotos antes/despues de la reforma.
9. Declaraciones responsables de inquilinos si se pretende defender vivienda habitual.

### No bloqueantes, pero utiles

1. Certificado eficiencia energetica.
2. Comunicaciones con inquilinos.
3. Justificantes de fianzas.
4. Documento explicando criterio de reparto renta/suministros.
5. Historico de declaraciones IRPF anteriores si el inmueble ya se declaro.

---

## Contradicciones y riesgos que el analista debe revisar si o si

| Riesgo | Estado | Accion |
|---|---|---|
| Historico contractual menciona Calle Antonio Cano, no Menendez Pidal | Critico | No usar como soporte directo de Menendez Pidal sin aclaracion |
| Seguro CASER declara residencia habitual, pero el uso actual es alquiler por habitaciones | Alto | Revisar poliza y posible actualizacion |
| Seguro declara 98 m2 frente a 81 m2 registrales/catastrales | Medio | Pedir explicacion a CASER/mediador |
| Seguro 2025 detectado 135,28 EUR frente a coste trianual aprox. 994-1.008 EUR | Alto | Definir criterio de imputacion 2025 |
| Agosto y septiembre 2025 sin ingresos recurrentes en base | Medio | Confirmar vacancia o error de clasificacion |
| Fianza 1.200 EUR mezclada con prorrata 212 EUR | Alto | Separar claramente renta vs fianza |
| Cobro agregado 1.200 EUR con suministros incluidos | Medio/Alto | Definir renta pura vs suministros |
| Hipoteca: cuota completa 2.646,24 EUR no es gasto fiscal completo | Critico | Usar solo intereses y gastos financieros deducibles |
| Reforma mezcla conservacion, mejora y redistribucion | Critico | Clasificar partida a partida |
| Anticipos Obramat pueden duplicar facturas finales | Critico | Netear pedidos/anticipos/facturas |
| Presupuestos usados como si fueran facturas | Critico | Excluir salvo factura/pago final |
| Contratos actuales incompletos o solo OCR habitacion 1 | Alto | Adjuntar todos los contratos actuales |

---

## Enfoque recomendado para pedir el analisis final

El analista debe entregar dos escenarios:

### Escenario conservador

Debe incluir solo:

- Ingresos 2025 trazables por banco.
- IBI 2025.
- Comunidad 2025.
- Agua/luz si hay soporte.
- Intereses hipotecarios 2025, no cuota completa.
- Seguro solo si se justifica el importe imputable a 2025.
- Reforma solo en la parte claramente documentada y fiscalmente defendible.
- Amortizacion solo si se calcula bien base suelo/construccion.

### Escenario ambicioso pero defendible

Puede incluir adicionalmente:

- Internet si se acredita que esta incluido en el alquiler.
- Mantenimiento de cuenta si la cuenta se dedica funcionalmente al inmueble.
- Parte de reforma defendible como reparacion/conservacion si hay factura + pago + descripcion.
- Mobiliario/equipamiento amortizable.
- Seguro prorrateado si se argumenta por devengo del seguro trianual.

No debe incluir:

- Cuota hipotecaria completa.
- Principal amortizado.
- Presupuestos sin factura.
- Anticipos duplicados.
- Facturas sin relacion clara con el inmueble.
- Gastos personales.
- Contratos de otro inmueble como soporte directo.

---

## Prompt recomendado para entregar junto al ZIP

Usar el prompt principal preparado previamente y anadir esta instruccion al inicio:

```markdown
Antes de analizar fiscalmente, revisa este manifest y verifica si el ZIP contiene todos los documentos marcados como imprescindibles. Si falta alguno, no rellenes el hueco: marca la partida como provisional, dudosa o excluible.

Si hay contradiccion entre un informe previo y un documento original, prevalece el documento original.

Si un informe previo resume un dato pero el documento original no esta en el ZIP, no lo trates como prueba plena; tratalo como soporte provisional.
```

---

## Preguntas que debe responder Jero antes del analisis final

1. En 2025, ¿el inmueble estuvo alquilado todos los meses o hubo vacancia real en agosto/septiembre?
2. ¿Los 212 EUR de prorrata de agosto estan ya incluidos dentro de los 10.825 EUR o hay que sumarlos aparte?
3. ¿La fianza de 1.200 EUR sigue viva, fue devuelta o se aplico a renta?
4. ¿Todos los contratos actuales son de Menendez Pidal?
5. ¿Todos los inquilinos usaban la habitacion como vivienda habitual o alguno era estancia temporal?
6. ¿El cobro de 1.200 EUR incluye suministros o es solo renta?
7. Si incluye suministros, ¿hay desglose contractual o es todo renta pactada?
8. ¿La cuenta 5436 se usa exclusivamente para el piso o tambien para gastos personales?
9. ¿Hay facturas de luz/agua/internet o solo extractos bancarios?
10. ¿El seguro CASER se pago de golpe, fraccionado o vinculado a la hipoteca?
11. ¿Existe certificado fiscal formal de intereses hipotecarios 2025?
12. ¿La reforma fue antes de iniciar el alquiler o durante el alquiler?
13. ¿Que parte de la reforma fue estrictamente reparacion de un piso deteriorado?
14. ¿Que parte fue redistribucion/mejora para aumentar rentabilidad por habitaciones?
15. ¿Existen pagos al contratista sin factura?
16. ¿Existen facturas sin justificante bancario de pago?
17. ¿Hay mobiliario/electrodomesticos no incluidos todavia en la tabla de reforma?
18. ¿Se pretende defender reduccion por alquiler de vivienda habitual o solo deducibilidad de gastos?
19. ¿Se quiere postura conservadora o se acepta un enfoque ambicioso pero defendible?
20. ¿Hay declaraciones IRPF anteriores donde ya se incluyera este inmueble?

---

## Conclusion operativa

El expediente esta suficientemente avanzado para pedir un analisis fiscal serio, pero no conviene lanzarlo solo con informes resumen.

Para que Claude o ChatGPT hagan un buen trabajo, hay que pasar:

1. documentos originales,
2. informes previos,
3. Excel clasificado,
4. extractos bancarios,
5. contratos actuales,
6. tabla de ocupacion,
7. tabla de cruce factura-pago,
8. este manifest.

El principal cuello de botella no es la compra ni la hipoteca. Lo que mas puede distorsionar el resultado final es:

- contratos/ocupacion,
- seguro,
- reforma,
- fianza/prorrata,
- y cruce real de facturas contra pagos.
