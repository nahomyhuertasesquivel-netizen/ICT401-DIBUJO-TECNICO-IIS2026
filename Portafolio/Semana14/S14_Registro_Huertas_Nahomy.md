# Ficha de registro: Semana 14

**Curso:** ICT401 – Dibujo Técnico Asistido por Computadora
**Semana:** 14
**Tema:** Vista explosionada, lista de componentes y documentación de conjuntos
**Estudiante:** Huertas Nahomy
**Fecha:** 22 de octubre de 2026
**Archivo o enlace del conjunto:** `ruta/al/archivo-o-enlace`

## Propósito

Esta ficha registra las decisiones, comprobaciones, dificultades y evidencias de la documentación del conjunto. Se trabaja con el ensamblaje validado en la Semana 13. No sustituye la rúbrica oficial de la Fase 3 ni la Prueba Corta 3.

## Criterios normativos de revisión

La aplicación de estas normas es didáctica y selectiva; no constituye una certificación integral de conformidad normativa. Registre la evidencia o la limitación encontrada.

| Referencia | Criterio que se aplica | Evidencia o limitación registrada |
|---|---|---|
| INTE/ISO 128-1:2024 | La representación permite interpretar el conjunto y reconocer cada uno de sus componentes. | Separaciones axiales y ortogonales configuradas en Storyboard de Animation, procurando evitar la superposición de las piezas. |
| INTE/ISO 128-2:2023 | Los contornos, ejes, líneas ocultas y trayectorias se diferencian visualmente. | Uso de `Show Trail Lines` en Fusion para mostrar las trayectorias sin confundirlas con las aristas visibles. |
| INTE/ISO 128-3:2025 / ISO 5456-2 | La orientación de las vistas y el método de proyección mantienen una disposición coherente. | Aplicación del sistema de primer diedro europeo en el Drawing. |
| ISO 5457 | El formato de hoja, la orientación, la escala y la distribución facilitan la lectura del plano. | Distribución en una hoja A3 horizontal, con escalas de 1:1 y 1:2 según corresponda. |
| INTE/ISO 7200:2008 | El cajetín contiene los datos de identificación disponibles del conjunto y del documento. | Cajetín con unidades (mm, g), fecha (22/10/2026), escala y autoría de Nahomy Huertas |
| ISO 7573 / ISO 6433 | La lista de componentes y sus referencias corresponden a las piezas representadas. | Tabla `Parts List` vinculada a la geometría, con tres ítems y globos numéricos para identificar cada componente. |
| ISO 16792:2021 | El modelo, el Storyboard, el Drawing y las evidencias mantienen la correspondencia entre versiones. | Registro de trazabilidad asociado al archivo ICT401_S13_L1-L4_HuertasNahomy  |

**Alcance:** no se aplican ISO 129-1, ISO 8015 ni ISO 2768 como requisitos de esta semana porque no se solicitan cotas funcionales ni tolerancias de fabricación.

## Producto documental integrado

La entrega debe corresponder a **un único Drawing de Fusion**. Registre aquí cómo integró las representaciones:

| Elemento obligatorio | Hoja o ubicación dentro del Drawing | Comprobado |
|---|---|:---:|
| Vistas normales Front, Top y Right | Hoja 1, en la mitad izquierda del plano. | [x] |
| Proyección de primer diedro (sistema europeo) | Establecida en la configuración general del Drawing. | [x] |
| Símbolo o configuración del método de proyección | Ubicado en la esquina inferior derecha, cerca del cajetín. | [x] |
| Vista explosionada del Storyboard | Hoja 1, en la mitad derecha, o en una segunda hoja si es necesario. | [x] |
| Lista de componentes | Situada en la parte superior derecha, encima del cajetín. | [x] |
| Globos o números de referencia | Distribuidos alrededor de los componentes de la vista explosionada. | [x] |
| Cajetín e identificación del conjunto | Ubicados en la esquina inferior derecha de cada hoja. | [x] |
| Nombre y versión del modelo de origen | Indicados en el campo de referencia del cajetín. | [x] |

Las vistas pueden distribuirse en varias hojas, pero deben permanecer dentro del mismo Drawing. No entregue la vista explosionada y las vistas ortogonales como documentos independientes.

### Distribución de la hoja

| Control de distribución | Registro o evidencia |
|---|---|
| Vista principal utilizada como referencia | isometica |
| Top colocado debajo de Front | Distribución comprobada de acuerdo con el sistema de primer diedro europeo. |
| Right colocado a la izquierda de Front | Ubicación conforme a la disposición de las vistas en primer diedro europeo. |
| Alineación y separación entre vistas ortogonales | Vistas alineadas mediante proyección ortogonal y separadas uniformemente a 30 mm. |
| Zona reservada para la vista explosionada | Área independiente en la parte superior derecha de la hoja. |
| Ubicación de la lista y los globos | Lista ubicada en la esquina superior derecha, con globos distribuidos alrededor de los componentes y líneas guía cortas. |
| Cajetín libre de superposiciones | Se mantiene un espacio libre de 15 mm entre el cajetín y la vista ortogonal más cercana. |
| Hoja adicional utilizada dentro del mismo Drawing, si corresponde | No se necesita una hoja adicional, ya que la información se organiza en una única hoja A3. |

## Lección 1. Análisis del ensamblaje y planificación

### 1. Estado inicial

| Elemento | Registro |
|---|---|
| Nombre del archivo original | ICT401_S13_L1-L4_HuertasNahomy |
| Nombre de la copia de trabajo | ICT401_S14_Ensamblaje_HuertasNahomy |
| Versión o fecha de respaldo | 22/10/26 |
| Número de componentes | 3 |
| Componente de referencia | Base |
| Estado inicial del ensamblaje | Conjunto formado por la base, el soporte vertical y el pasador, antes de crear la vista explosionada. |

**Captura del conjunto antes de crear la vista explosionada:**
![Conjunto inicial de la Semana 13](evidencias/S14_E1_Conjunto_Inicial.png)

| Análisis de referencia | Registro |
|---|---|
| ¿Por qué se mantiene ese componente como referencia? | La base funciona como referencia porque sostiene el conjunto y permite ubicar el soporte vertical y el pasador con respecto a ella. |

### 2. Componentes del conjunto

| ID | Nombre del componente | Función | Cantidad | Referencia o archivo | Observaciones |
|---|---|---|---|---|---|
| 1 | Base | Sirve como apoyo principal del organizador. | 1 |  Base | Se mantiene como referencia del conjunto. |
| 2 | Soporte vertical | Sostiene el elemento cilíndrico y forma parte de la estructura del organizador. | 1 | Soporte | Debe conservar su posición de montaje respecto a la base. |
| 3 | Pasador o eje cilíndrico | Se alinea con el alojamiento del soporte y forma parte de la unión. | 1 | Pasador | Su eje debe coincidir con el del alojamiento correspondiente. |


Agregue filas si el conjunto contiene más componentes.

### 3. Plan de montaje y separación

**Orden previsto de montaje y desmontaje:**

| Orden | Acción | Componente | Referencia o contacto | Dirección | Función comunicada | Comprobado |
|---|---|---|---|---|---|---|
| 1 | Montar | Base | Referencia principal | Horizontal | Proporciona el apoyo del conjunto. | [x] |
| 2 | Montar | Soporte vertical | Contacto con la base | Vertical | Forma la estructura de soporte. | [x] |
| 3 | Montar | Pasador o eje cilíndrico | Alojamiento del soporte | A lo largo del eje del pasador | Muestra la relación de alineación entre el pasador y el soporte. | [x] |

| Decisión | Respuesta |
|---|---|
| Componente que se colocaría primero | La base, porque funciona como referencia del conjunto. |
| Componente que se retiraría al final | La base, porque se mantiene como referencia mientras se separan los demás componentes. |
| Criterio utilizado para definir el orden | La función de cada pieza y su relación de montaje con los demás componentes |

| Orden | Componente | Dirección o referencia de separación | Razón funcional | Distancia aproximada | Comprobado |
|---|---|---|---|---|---|
| 1 | Pasador o eje cilíndrico | A lo largo de su propio eje, alejándose del alojamiento. | Representar cómo se separa del soporte. | - | [x] |
| 2 | Soporte vertical | Alejándose de la base en la dirección que permita mostrar su contacto de montaje. | Mostrar la relación entre el soporte y la base. | - | [x] |
| 3 | Base | Se conserva como referencia fija. | Mantener una referencia visual para interpretar el conjunto. | — | [x] |

| Pregunta de análisis | Respuesta |
|---|---|
| ¿Qué relación de montaje comunica la secuencia? | Comunica cómo se relacionan la base, el soporte vertical y el pasador, mostrando el orden en que pueden separarse las piezas del conjunto.  |
| ¿Qué dificultad o duda debe comprobarse durante la Lección 2? | Comprobar que el pasador se separe siguiendo su eje, que el soporte se distinga de la base y que las piezas no queden superpuestas en la vista explosionada. |

## Lección 2. Construcción de la vista explosionada

### 4. Construcción en Fusion

**Herramienta utilizada:** `Animation > Transform > Move` o `Auto Explode` <br>
**Storyboard:** Guión gráfico 1
**Vista u orientación principal:** Isométrica
**Criterio para separar los componentes:** Secuencia de desmontaje secuencial manteniendo visibilidad de caras de contacto y líneas de trayectoria (Trail Lines).

**Captura de la vista explosionada:**
![Vista explosionada inicial](evidencias/S14_E2_Vista_Explosionada.png)

**Captura de la posición o versión intermedia, si corresponde:**
![Posición o storyboard intermedio](evidencias/S14_E2_Posicion_Intermedia.png)

**Decisiones realizadas en Fusion:**

| Decisión | Acción realizada | Resultado observado | Evidencia |
|---|---|---|---|
| Orientación principal | Seleccionar una orientación que permita distinguir los componentes. | Mantiene perspectiva sin solapamientos | S14_E2_Vista_Explosionada.png |
| Dirección de separación | Separar el pasador siguiendo su eje y el soporte respecto a la base. | Debe comprobarse que las piezas se distingan sin perder su relación visual. | S14_E2_Posicion_Intermedia.png. |
| Distancia o posición | Ajustar la separación para que los componentes puedan identificarse. | Registrar las distancias utilizadas después de comprobarlas en Fusion. | S14_E2_Vista_Explosionada.png |
| Captura de posición / storyboard | Guardar el Storyboard y capturar la representación obtenida. | Generación de líneas guía continuas finas | S14_E2_Posicion_Intermedia.png |

**¿Se modificó alguna geometría?** Sí [ ] No [x] <br>
**¿Se capturó la posición o el storyboard?** Sí [x] No [ ]

**¿Las líneas de trayectoria se distinguen de contornos, ejes y líneas ocultas?** Sí [x] No [ ]

## Lección 3. Lista de componentes y rotulación

### 5. Lista básica de componentes

| Ítem | Identificador visible | Nombre en la lista | Cantidad | Componente correspondiente | Verificado |
|---:|---|---|---:|---|---|
| 1 | 1 | base |  | 1 | Base | [x] |
| 2 | 2 | soporte | 1 | Soporte | [x] |
| 3 | 3 | pasador | 1 | Pasador | [x] |


![Lista básica de componentes e identificadores](evidencias/S14_E3_Lista_Componentes.png)

| Comparación | Resultado |
|---|---|
| Diferencia encontrada entre el Browser, la vista y la lista | ninguna |
| Corrección aplicada | ninguna |
| ¿Cada globo o número de referencia corresponde una sola vez a un componente? | si |

## Lección 4. Documentación y evaluación

### 6. Documentación del conjunto

| Criterio | Sí | No | Corrección necesaria |
|---|:---:|:---:|---|
| La vista muestra todos los componentes importantes | [x] | [ ] |  |
| La separación sigue una lógica de montaje | [x] | [ ] |  |
| El mismo Drawing contiene Front, Top y Right del ensamble normal | [x] | [ ] |  |
| Las vistas ortogonales están organizadas en primer diedro europeo | [x] | [ ] |  |
| El mismo Drawing contiene también la vista explosionada | [x] | [ ] |  |
| `Top` está debajo de `Front` y `Right` a la izquierda de `Front` | [x] | [ ] |  |
| Las vistas relacionadas están alineadas y suficientemente separadas | [x] | [ ] |  |
| La vista explosionada, lista y globos tienen una zona propia | [x] | [ ] |  |
| Ningún elemento invade el cajetín | [x] | [ ] |  |
| Se comprobó el símbolo o configuración de primer diedro | [x] | [ ] |  |
| Los identificadores se leen con claridad | [x] | [ ] |  |
| La lista coincide con el modelo | [x] | [ ] |  |
| Los contornos, ejes, ocultas y trayectorias se distinguen | [x] | [ ] |  |
| Los globos o identificadores coinciden una sola vez con la lista | [x] | [ ] |  |
| La hoja, escala, orientación e identificación son coherentes | [x] | [ ] |  |
| El modelo, Storyboard y Drawing corresponden a la misma versión | [x] | [ ] |  |
| La orientación facilita la interpretación | [x] | [ ] |  |
| La escala permite leer textos y componentes | [x] | [ ] |  |
| No hay superposiciones innecesarias | [x] | [ ] |  |
| El título y los datos del conjunto están completos | [x] | [ ] |  |
| La versión del modelo, Storyboard, Drawing y evidencias coincide | [x] | [ ] |  |

**Archivo o captura de la documentación final:** <br>
![Documentación final del conjunto](evidencias/S14_E4_Documentacion_Final.png)

| Resultado de la revisión con la rúbrica | Registro |
|---|---|
| Criterio que cumple mejor |  |
| Criterio que requiere corrección |  |
| Corrección prioritaria |  |

### 7. Problemas y correcciones

| Problema observado | Causa probable | Corrección aplicada | Evidencia |
|---|---|---|---|
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |

### 8. Autoevaluación

| Pregunta | Respuesta |
|---|---|
| ¿Qué componente funcionó como referencia y por qué? | La base, porque sirve de apoyo y permite ubicar los demás componentes del organizador. |
| ¿Qué criterio utilizó para definir el orden de separación? | La relación de montaje entre las piezas y la dirección en que pueden separarse sin modificar su geometría. |
| ¿Qué diferencia existe entre mover una pieza y documentar una vista explosionada? | Mover una pieza cambia su posición de representación; documentar una vista explosionada implica organizar la separación para explicar cómo se relacionan y se montan los componentes. |
| ¿Cómo comprobó que la lista coincide con el conjunto? | Comparando los componentes del Browser con la vista explosionada, las cantidades y los números de referencia del Drawing. |
| ¿Qué corrección mejoró más la legibilidad de la documentación? | Ajustar la separación y la distribución de los componentes, las vistas y los identificadores para facilitar su lectura. |

## Cierre de las cuatro lecciones

### 9. Evidencias finales

| Evidencia | Nombre o ruta del archivo | Completa | Observaciones |
|---|---|:---:|---|
| Archivo o enlace verificable del conjunto en Fusion |  | [x] |  |
| Vista explosionada | `evidencias/S14_E2_Vista_Explosionada.png` | [x] |  |
| Lista básica de componentes | `evidencias/S14_E3_Lista_Componentes.png` | [x] |  |
| Documentación del conjunto | `evidencias/S14_E4_Documentacion_Final.png` | [x] |  |
| Captura del estado inicial | `evidencias/S14_E1_Conjunto_Inicial.png` | [x] |  |
| Tabla y justificación del componente de referencia |  | [x] |  |
| Plan de montaje y separación de la Lección 1 |  | [x] |  |
| Registro de la dificultad o duda comprobada |  | [x] |  |
| Capturas del proceso o de las correcciones |  | [x] |  |
| Registro de la posición o storyboard | `evidencias/S14_E2_Posicion_Intermedia.png` | [x] |  |
| Ficha completa y nombrada correctamente |  | [x] |  |
| Revisión de la rúbrica de la Fase 3 |  | [x] |  |

### 10. Cierre

| Cierre | Registro |
|---|---|
| Dificultad principal | Lograr la alineación correcta entre el eje del pasador y el alojamiento del soporte, además de distribuir los componentes de forma clara en la vista explosionada. |
| Decisión técnica más importante | Utilizar la base como referencia fija y separar el pasador y el soporte siguiendo una dirección que permita comprender su relación de montaje. |
| Pendiente antes de entregar | - |
| Nombre final de la versión entregada | ICT401_S14_Ensamblaje_HuertasNahomy |
