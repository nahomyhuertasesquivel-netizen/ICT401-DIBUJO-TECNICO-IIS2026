# Ficha de registro: Laboratorio Integrador II-B

**Curso:** ICT401 – Dibujo Técnico Asistido por Computadora
**Semana:** 16
**Laboratorio:** Integrador II-B
**Valor del laboratorio:** 10 %
**Estudiante o equipo:** Huertas Nahomy
**Proyecto:** Organizador de escritorio para libros y cuadernos
**Fecha:** 05 de noviembre de 2026
**Versión inicial:** `hgvfh`
**Versión evaluada:** `nombre_proyecto_v__`

## Propósito y alcance

Esta ficha registra la evidencia del Laboratorio Integrador II-B: integración del modelo, ensamblaje, documentación, exportaciones, tolerancias introductorias y control dimensional básico.

La ficha **no sustituye la entrega de la Fase 4 del Proyecto Integrador**, cuyo valor oficial es 7 % y cuyos requisitos se definen en su propia rúbrica. Algunas evidencias pueden reutilizarse si cumplen ambos propósitos, pero deben conservarse separados el registro del laboratorio y la entrega de la fase.

No se evalúan mediante esta ficha la fabricación física, la metrología avanzada, los procesos completos de manufactura ni la presentación final de la Semana 17.

## Instrucciones

1. Complete la ficha durante las cuatro lecciones.
2. Registre la versión exacta del proyecto utilizada.
3. Conserve una copia de respaldo antes de modificar o exportar.
4. Registre el propósito, formato y comprobación de cada archivo de salida.
5. No invente tolerancias cuando no estén indicadas.
6. Cada medición debe incluir característica, unidad, método y limitación.
7. Use nombres o rutas verificables para las evidencias.

Los textos que comienzan con **Ejemplo:** muestran el nivel de detalle esperado. Sustitúyalos por los datos reales de su proyecto; no los copie como resultados propios.

### Ruta general en Fusion

1. Abra el **Data Panel**, localice el proyecto y abra el diseño vigente.
2. En el **Browser**, confirme componentes, cuerpos y el componente raíz.
3. Revise **Document Settings > Units** y anote las unidades activas.
4. Para el plano, abra el **Drawing** correspondiente y revise sus hojas.
5. Para medir, utilice **Inspect > Measure** y seleccione caras, aristas, puntos o diámetros.
6. Para exportar, utilice **File > Export** cuando el formato esté disponible. Para STL, seleccione el cuerpo o componente y use **Save As Mesh**.
7. Si una orden tiene otro nombre, use el buscador de comandos y registre la orden equivalente.

## Lección 1. Auditoría del proyecto y documentación

| Elemento | Registro |
|---|---|
| Archivo o enlace principal |  `Data Panel > Proyecto > ICT404_PROY_F03_NahomyHuertas` |
| Versión revisada |  `ICT404_PROY_F03_NahomyHuertas` |
| Fecha de la versión |  `23-10-2026` |
| Unidades del proyecto | `mm` |
| Plano o Drawing utilizado |  `ICT401_PROY_F04_NahomyHuertas Dibujo`  |
| Ensamblaje utilizado, si corresponde |  `ICT404_PROY_F03_NahomyHuertas` |
| Lista básica de componentes, si corresponde | `Parts List` con 2 componentes |
| Ubicación del respaldo inicial |  `Proyecto_v04_respaldo_Huertas_Nahomy` |
| Problema prioritario encontrado | N/A |

### Revisión de coherencia

| Control | Sí | No | N.A. | Evidencia o corrección |
|---|:---:|:---:|:---:|---|
| El modelo y la documentación corresponden a la misma versión. | [x] | [ ] | [ ] | El modelo 3D y el plano técnico corresponden a la versión final del organizador. |
| El plano contiene las vistas, cotas y datos que corresponden. | [x] | [ ] | [ ] | Se incluyen las vistas superior, frontal, derecha y explosionada, con sus dimensiones correspondientes. |
| El cajetín o identificación está completo según la plantilla. | [x] | [ ] | [ ] | Se incluye el nombre del proyecto, autoría, fecha y escala. |
| La lista coincide con el ensamblaje, cuando corresponde. | [x] | [ ] | [ ] | La lista de materiales coincide con las dos piezas que conforman el organizador. |
| La orientación y la escala son coherentes. | [x] | [ ] | [ ] | Drawing en mm y escala 1:1 |

**Captura del estado inicial:** `evidenciasS16_E1_Estado_Inicial.png`  

**Corrección prioritaria antes de exportar:**

## Lección 2. Exportaciones y comprobación de archivos

En Fusion, seleccione primero el objeto correcto en el **Browser**. No exporte todo el proyecto si solo se solicita una pieza o un componente.

| Formato | Propósito | Configuración relevante | Archivo generado | Comprobado |
|---|---|---|---|:---:|
| STL | Obtener el modelo 3D para impresión. | Exportación de la geometría en formato STL, unidades mm. | `ICT401_PROY_F04_ARCHIVO STL.stl` | [x] |
| STEP | Compartir el modelo 3D y conservar su geometría. | Exportación del modelo en formato STEP. | `ICT404_PROY_F04_ARCHIVO STEP.step` | [x] |
| DXF | Permitir la edición e intercambio del plano técnico. | Exportación del Drawing en formato DXF. | `ICT401_PROY_F04_ARCHIVO DXF.dxf` | [x] |
| PDF | Presentar la documentación técnica del organizador. | Exportación del Drawing con sus vistas, cotas y escala. | `ICT401_PROY_F04_ARCHIVO PDF.pdf` | [x] |
| Otro | No se generaron otros formatos adicionales. | No aplica. | No aplica. | [N.A] |

Marque `N.A.` cuando un formato no corresponda al proyecto y justifique la decisión.

### Comprobación de cada salida

| Archivo | Geometría | Unidades | Escala/orientación | Versión | Ubicación | Resultado |
|---|:---:|:---:|:---:|:---:|---|---|
| `ICT401_PROY_F04_ARCHIVO PDF.pdf` | [x] | [x] | [x] | [x] | `salidas/` | Plano técnico legible con sus vistas y cotas. |
| `ICT401_PROY_F04_ARCHIVO DXF.dxf` | [x] | [x] | [x] | [x] | `salidas/` | Archivo editable del plano técnico. |
| `ICT404_PROY_F04_ARCHIVO STEP.step` | [x] | [x] | [x] | [x] | `salidas/` | Modelo 3D exportado con sus dos piezas. |
| `ICT401_PROY_F04_ARCHIVO STL.stl` | [x] | [x] | [x] | [x] | `salidas/` | Modelo 3D preparado para impresión. |

**Archivo o captura de comprobación:** `evidencias/S16_E2_Exportaciones.png`  
**Discrepancia encontrada:**  No se encontraron discrepancias durante la comprobación de los archivos
**Corrección aplicada:** N.A 

## Lección 3. Tolerancias y control dimensional básico

En Fusion, la ruta de comprobación es **Design > Inspect > Measure**. En el resultado de la medición deben poder reconocerse la geometría seleccionada y la unidad.

No agregue una tolerancia que no esté indicada en el plano, la rúbrica o la instrucción correspondiente.

| Característica | Dimensión nominal | Tolerancia | Límite inferior | Límite superior | Valor observado | Unidad |
|---|---:|---:|---:|---:|---:|---|
| Altura de la barra de retención | 17,5 | +0,5 / -0,2 | 17,3 | 18,0 | 17,5 | mm |

### Método y resultado

| Característica | Herramienta o método | Resultado | Limitación de la comprobación |
|---|---|---|---|
| Altura de la barra de retención | `Inspect > Measure`, medición de distancia | Conforme | Permite revisar la dimensión nominal, pero no garantiza el cumplimiento de la tolerancia en una pieza fabricada. |

**Ejemplo de cálculo, si corresponde:**

**Captura o referencia de la medición:** `evidencias/S16_E3_Control_Dimensional.png`  
**¿Qué valor o criterio no pudo comprobarse?**

## Lección 4. Integración y cierre del laboratorio

Después de corregir, guarde la versión evaluada desde **File > Save** o la orden equivalente. Compruebe que el archivo exportado y la ficha se refieran a esa misma versión.

### Correcciones finales

| Problema | Acción aplicada | Resultado | Evidencia |
|---|---|---|---|
| Ejemplo: PDF con escala incorrecta | Corregir escala del Drawing y exportar de nuevo | PDF revisado en 4 hojas | `S16_E4_PDF_v04.png` |
|  |  |  |  |
|  |  |  |  |

### Checklist del Laboratorio II-B

- [ ] La versión del modelo y la documentación coincide.
- [ ] El plano final fue revisado.
- [ ] La lista básica coincide con el ensamblaje, cuando corresponde.
- [ ] Cada archivo exportado tiene un propósito registrado.
- [ ] Las salidas fueron revisadas fuera del comando de exportación.
- [ ] Se registraron unidades, escala, orientación y versión.
- [ ] Se realizó al menos una comprobación dimensional básica.
- [ ] Las tolerancias introductorias fueron interpretadas sin inventar valores.
- [ ] Se registraron discrepancias y correcciones.
- [ ] La versión evaluada fue respaldada.
- [ ] La ficha está completa.

### Evidencias finales del laboratorio

| Evidencia | Nombre o ruta | Completa | Observaciones |
|---|---|:---:|---|
| Estado inicial y auditoría | `evidencias/S16_E1_Estado_Inicial.png` | [ ] |  |
| Exportaciones y comprobación | `evidencias/S16_E2_Exportaciones.png` | [ ] |  |
| Control dimensional | `evidencias/S16_E3_Control_Dimensional.png` | [ ] |  |
| Plano final o documentación |  | [ ] |  |
| Lista básica, si corresponde |  | [ ] |  |
| Archivo de respaldo |  | [ ] |  |
| Ficha completa |  | [ ] |  |

## Separación de la Fase 4

**¿Qué producto o archivo adicional exige la rúbrica de la Fase 4?**

**¿Qué evidencia de esta ficha puede reutilizarse en la Fase 4?**

**¿Qué requisito de la Fase 4 todavía no está cubierto por esta ficha?**

## Cierre reflexivo

**¿Qué exportación requirió más comprobación y por qué?**

**¿Qué diferencia encontró entre el valor nominal, la tolerancia y el valor observado?**

**¿Qué corrección mejoró la confiabilidad del producto técnico?**

**¿Qué limitación debe comunicar antes de considerar terminada la Fase 4?**
