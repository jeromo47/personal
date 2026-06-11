# Extracción lote documental Menéndez Pidal 2026-03 v1

## Lote analizado
Documentos recibidos y revisados:
- `2026-03_Recibo_cuota_hipoteca_Menedez_Pidal---2141aa04-3688-40e3-af2e-ebf5f8ad4542.pdf`
- `2026-03_Certificado_deuda_pendiente_Menedez_Pidal---025b6727-7932-4965-b5fe-3194da09d5d1.pdf`
- `Escritura_de_hipoteca---7e7b67c4-a1d5-4cd8-ae6c-943bcb298de5.pdf`
- `Compraventa---75fc99d8-d1b4-43cd-bb5b-3ce7aa5f9711.pdf`

Objetivo:
- extraer información durable
- decidir nombre / utilidad / encaje documental
- dejar ya material listo para fiscalidad, control patrimonial y búsquedas futuras

---

## 1. Recibo cuota hipoteca marzo 2026
### Documento
- Fecha valor: `27/03/2026`
- Préstamo / contrato: `2103 0871 37 0500029574`
- Titular: `Jerónimo Molina Caparrós`
- Cuenta de adeudo: `ES93 2103 5970 12 0030005436`

### Datos útiles extraídos
- **Saldo anterior:** `50.907,32 €`
- **Nuevo saldo:** `50.794,19 €`
- **Tipo aplicado:** `2,7500 %`
- **Cuota total:** `220,52 €`
- **Capital amortizado en esa cuota:** `113,13 €`
- **Intereses de esa cuota:** `107,39 €`
- **Periodo liquidado:** `27/02/2026` a `27/03/2026`

### Utilidad
Muy útil como prueba real de:
- cuota efectiva
- reparto real capital/interés en fecha concreta
- cuenta asociada al préstamo
- permanencia del tipo fijo del `2,75 %` en marzo 2026

---

## 2. Certificado deuda pendiente marzo 2026
### Documento
- Fecha del saldo certificado: `29/03/2026`
- Préstamo: `21030871370500029574`
- Importe concedido: `54.000,00 €`
- Titular: `Jerónimo Molina Caparrós`
- DNI: `76631414Z`
- Finca hipotecada: **finca número `909`**
- Registro: `Almería-5`

### Datos económicos extraídos
- **Capital pendiente:** `50.794,19 €`
- **Intereses:** `7,65 €`
- **Intereses devengados diariamente:** `3,84 €`
- **Demoras devengadas diariamente:** `0,00 €`
- **Comisión / compensación por reembolso anticipado:** `126,99 €`
- **Liquidación para cancelar a fecha valor 29/03/2026:** `50.928,83 €`
- **Próxima amortización / liquidación:** `27/04/2026`

### Dato técnico muy valioso
El propio certificado explica que la pérdida financiera calculada asciende a:
- **`212,31 €`**

pero la comisión aplicable queda limitada a:
- **`126,99 €`**

### Utilidad
Muy útil para:
- fijar capital pendiente real a marzo 2026
- verificar consistencia con recibo de cuota
- entender coste de cancelación anticipada en periodo con comisión todavía vigente

---

## 3. Escritura de hipoteca, puntos durables ya extraídos
### Identificación
- Tipo: **escritura de préstamo hipotecario**
- Fecha: **`27/07/2023`**
- Notario: **Javier Fernández Carratalá**
- Lugar: **Alhama de Almería**
- Número de protocolo: **`1318`**

### Partes
- Acreedor: **Unicaja Banco, S.A.**
- Prestatario / hipotecante: **Jerónimo Molina Caparrós**
- DNI: **`76631414Z`**
- Email indicado en escritura: **`jmolinacaparros@gmail.com`**

### Datos financieros clave
- **Principal:** `54.000,00 €`
- **Cuenta de pago / abono del préstamo:** `ES93 2103 5970 12 0030005436`
- **Plazo:** `360 meses`
- **Cuotas:** `360` con periodicidad mensual
- **Cuota inicial del primer periodo:** `220,52 €`
- **Primer periodo de interés:** `36 meses` a **`2,750 %` fijo**
- **Luego:** `Euribor 1 año + 1,750 pp`
- El tipo nunca puede ser negativo
- **TAE variable:** `5,351 %`
- **Comisión de apertura:** exenta

### Reembolso anticipado
- durante los **3 primeros años**:
  - comisión por pérdida financiera con límite del **`0,250 %`** del capital reembolsado anticipadamente
- si dentro de ese plazo la operación fuese por novación/subrogación hacia fijo en determinados supuestos:
  - límite del **`0,05 %`**
- tras los 3 primeros años:
  - **sin compensación ni comisión**

### Dato técnico fino
- la escritura fija para el cálculo de pérdida financiera un **diferencial IRS de `-0,704`**

### Utilidad
Documento nuclear para:
- condiciones legales del préstamo
- trazabilidad del préstamo con la cuenta `5436`
- defender cómo funciona el tipo, cuota, reembolso y comisiones

---

## 4. Compraventa, puntos durables ya extraídos
### Identificación
- Tipo: **escritura de compraventa**
- Fecha: **`27/07/2023`**
- Número de protocolo: **`1317`**

### Comprador
- **Jerónimo Molina Caparrós**

### Inmueble
- **Calle Menéndez Pidal 52, Almería**
- Descripción: **vivienda tipo I**
- Superficie construida: **`81,48 m²`**
- Superficie útil: **`66,31 m²`**
- Registro de la Propiedad: **Almería nº 5**
- **Finca registral:** `909`
- **Referencia catastral:** `9383002WF4798S0058SY`

### Estado transmitido
- libre de cargas
- libre de arrendatarios y ocupantes según la escritura
- destino declarado por comprador: **vivienda habitual**

### Precio
- **Precio total compraventa:** `64.000,00 €`
- **Entrega previa:** `3.200,00 €`
- **Resto por cheque / pago:** `60.800,00 €`
- En la escritura aparece vinculada la cuenta `0030005436` como anexo justificativo de pago

### Valor de referencia catastral en escritura
- **`71.350,88 €`**

### Utilidad
Documento nuclear para:
- fijar adquisición
- precio de compra
- identificación fina del inmueble
- encaje registral/catastral

---

## 5. Conclusiones prácticas del lote
### Lo más valioso que añade este lote
1. **Confirma con prueba real la cuota hipotecaria y su reparto capital/interés.**
2. **Confirma el capital pendiente real en marzo 2026: `50.794,19 €`.**
3. **Conecta de forma robusta inmueble, finca registral 909, referencia catastral y préstamo Unicaja.**
4. **Fija precio de compra del inmueble en `64.000,00 €`.**
5. **Confirma cuenta operativa central `ES93...5436`** tanto para compraventa como para hipoteca.

---

## 6. Propuesta de renombrado útil
Si luego quieres ordenarlo bien en tu carpeta del piso, yo usaría esta convención:

### Hipoteca
- `2023-07-27_escritura_hipoteca_unicaja_menendez_pidal_54k.pdf`
- `2023-07-13_fein_hipoteca_unicaja_menendez_pidal_54k.pdf`
- `2026-03-27_recibo_cuota_hipoteca_unicaja_menendez_pidal.pdf`
- `2026-03-29_certificado_deuda_pendiente_hipoteca_unicaja_menendez_pidal.pdf`

### Adquisición
- `2023-07-27_escritura_compraventa_menendez_pidal_52_finca_909.pdf`

---

## 7. Propuesta de ubicación documental
### Carpeta sugerida
Dentro de:
- `/home/jero/cloud/02_proyectos/patrimonio_personal_jero/00_input/`

crearía o usaría:
- `hipoteca_menendez_pidal/`
- `compra_menendez_pidal/`

Ejemplo:
- `00_input/hipoteca_menendez_pidal/2023-07-27_escritura_hipoteca_unicaja_menendez_pidal_54k.pdf`
- `00_input/hipoteca_menendez_pidal/2026-03-27_recibo_cuota_hipoteca_unicaja_menendez_pidal.pdf`
- `00_input/hipoteca_menendez_pidal/2026-03-29_certificado_deuda_pendiente_hipoteca_unicaja_menendez_pidal.pdf`
- `00_input/compra_menendez_pidal/2023-07-27_escritura_compraventa_menendez_pidal_52_finca_909.pdf`

---

## 8. Qué guardaría como dato durable fuera del PDF
### Para notas generales del piso
- finca registral `909`
- referencia catastral `9383002WF4798S0058SY`
- precio compra `64.000,00 €`
- hipoteca Unicaja `54.000,00 €`
- cuota inicial `220,52 €`
- tipo fijo inicial `2,750 %` durante 36 meses
- cuenta operativa asociada `5436`
- capital pendiente a `29/03/2026`: `50.794,19 €`

### Para fiscalidad
- recibo marzo 2026: capital `113,13 €`, intereses `107,39 €`
- certificado cancelación marzo 2026: total cancelación `50.928,83 €`
- escritura compraventa: precio adquisición `64.000,00 €`

---

## 9. Siguiente paso recomendado
Con este lote ya compensa hacer dos cosas:
1. **crear ficha maestra del inmueble** con adquisición + hipoteca + fiscalidad
2. **actualizar la base fiscal 2025** con un criterio más fino de intereses hipotecarios, usando FEIN + recibos reales como soporte provisional hasta localizar certificado anual bancario
