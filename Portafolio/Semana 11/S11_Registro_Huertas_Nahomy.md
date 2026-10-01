# ICT401 · Semana 11 — Registro de cortes, secciones, detalles y tolerancias

28 de septiembre al 3 de octubre de 2026.

- Estudiante: Nahomy Marcela Huertas Esquivel
- Grupo: 60
- Carpeta o proyecto de Fusion Cloud con acceso docente: Nahomy Huertas
- Drawing o modelo de referencia de Semana 10: ICT401_S10_P4_Huertas_Nahomy
- Modelo utilizado: P4

## Instrucciones

Copie esta plantilla a `Portafolio/semana11/` y guárdela como `S11_Registro_Apellido_Nombre.md`. Sustituya `Apellido_Nombre` por un apellido y un nombre sin espacios ni tildes. Complete cada `[Respuesta]`, agregue las imágenes solicitadas en la misma carpeta y publique los cambios mediante un commit.

Conserve las decisiones iniciales y documente las correcciones. No borre una interpretación anterior: explique qué cambió, qué evidencia motivó el cambio y cómo verificó el resultado.

Trabaje sobre un modelo o plano desarrollado en Semana 10. Use milímetros, orientación coherente y una cámara ortográfica. La ficha es un registro de proceso: complete cada sección durante la lección, no al final de memoria.

**Entornos de Fusion:** `Design` es el espacio para abrir y revisar el modelo 3D; `Drawing` es el espacio para crear y editar el plano técnico. P1 se realiza en `Design`; P2 es un croquis de planificación y no crea todavía el plano definitivo; P3, P4 y P5 se realizan principalmente en `Drawing`. Solo se regresa a `Design` para verificar que el plano corresponda con el modelo.

**Continuidad con Semana 10:** reutilice el `Drawing` de Semana 10 con sus vistas `Front`, `Top` y `Right`. Semana 11 no consiste en generar nuevamente las tres vistas desde cero, sino en agregar y verificar el corte o la sección, el rayado, el detalle ampliado y la tolerancia introductoria cuando corresponda. Si el `Drawing` de Semana 10 está incompleto o contiene errores, corríjalo como requisito previo y registre la corrección; no convierta la generación de vistas en la actividad central de esta semana.

## P1 — ¿Cuándo conviene cortar?

**Propósito:** decidir si un corte o una sección comunica mejor una característica interior que una vista ordinaria con líneas ocultas.

**Entorno:** Fusion, espacio `Design`. No se crea ni se modifica todavía el `Drawing`.

### P1.0 · Pasos en Fusion

1. Abra en Fusion el diseño de Semana 10 y permanezca en el espacio `Design`.
2. Seleccione el componente o cuerpo que documentará. No cambie dimensiones ni operaciones.
3. Use el ViewCube para observar `Front`, `Top` y `Right`.
4. Para observar el interior, use `Inspect > Section Analysis` sobre una cara o plano adecuado. Esta sección de análisis sirve para decidir y no es todavía una vista de `Drawing`.
5. Tome `S11_P1_Modelo_Apellido_Nombre.png` con modelo 3D, nombre del diseño y ViewCube visibles.
6. Prepare `S11_P1_Comparacion_Apellido_Nombre.png` como una sola lámina con tres recortes del espacio `Design`: vista ordinaria, vista con líneas ocultas y resultado de `Inspect > Section Analysis`.
7. Agregue las etiquetas `ordinaria`, `ocultas` y `sección` con un editor de imágenes, o escríbalas sobre una impresión y fotografíela. No use `Drawing` en P1.

### P1.1 · Modelo utilizado

- Nombre del diseño en Fusion: [Respuesta]
- Pieza de referencia y semana de origen: Pieza trabajada previamente en semana 9, utilizada como base para continuar el plano técnico de Semana 11.
- Características interiores observadas: [Respuesta]

### P1.2 · Análisis de vistas

| Característica | Vista donde aparece | ¿Se comunica claramente? | Problema detectado |
|---|---|---|---|
| Perforación cilíndrica | Vista superior | Sí | En otras vistas se representa principalmente mediante líneas ocultas. |
| Profundidad de la perforación | Vista frontal | No en su totalidad | Las líneas ocultas dificultan visualizar directamente su profundidad. |
| Cambio de nivel | Vista frontal | Sí | Se observa claramente el cambio de nivel de la pieza. |
| Cavidad rectangular interior | Vista superior/frontal | No en su totalidad | 	Parte de la geometría interior queda representada mediante líneas ocultas. |

### P1.3 · Comparación de alternativas

| Alternativa | Ventaja | Limitación |
|---|---|---|
| Vista ordinaria | Permite conservar la forma exterior de la pieza de manera sencilla. | Las características interiores no se observan directamente. |
| Vista con líneas ocultas | Permite representar agujeros y elementos internos sin modificar la vista. | Puede generar varias líneas discontinuas y dificultar la interpretación. |
| Vista seccionada | Muestra directamente las características interiores y las superficies atravesadas. | Requiere definir correctamente el plano y la dirección de observación. |

### P1.4 · Decisión de representación

- Tipo de representación elegido: Vista seccionada mediante un corte completo.
- Vista desde la que se realizará: Vista frontal.
- Posición aproximada del plano de corte: Plano vertical ubicado de manera que atraviese la zona central de la perforación cilíndrica y la cavidad interior.
- Justificación técnica: Elegí una vista seccionada porque permite mostrar directamente las características interiores de la pieza, especialmente la perforación y la cavidad rectangular de esta manera se reduce la cantidad de líneas ocultas y se facilita la interpretación de la geometría interior y el corte permite además identificar mediante rayado las superficies que son atravesadas por el plano de corte.

### Evidencias P1

**Qué debe contener cada imagen:**

- `S11_P1_Modelo_Huertas_Nahomy.png`: captura de Fusion en el espacio `Design`, con el modelo 3D utilizado, nombre del diseño, ViewCube y característica interior que se analizará.
- `S11_P1_Comparacion_Huertas_Nahomy.png`: comparación entre una vista ordinaria, la alternativa con líneas ocultas y la propuesta de sección. Debe mostrar qué información queda oculta y por qué la sección sería más clara.

Una captura aislada del modelo no demuestra la comparación solicitada.

P1 no requiere crear un `Drawing`; la decisión se registra antes de pasar a la documentación técnica.

![P1: Modelo](S11_P1_Modelo_Apellido_Nombre.png)

![P1: Comparación](S11_P1_Comparacion_Apellido_Nombre.png)

## P2 — Plano de corte y sección

**Propósito:** planificar el plano de corte, la dirección de observación, la identificación y el rayado antes de aplicarlos en Fusion. P2 es un croquis de planificación; todavía no se edita el `Drawing` definitivo.

**Entorno:** se consulta el modelo en Fusion, espacio `Design`, pero el resultado de P2 es un croquis o esquema de trabajo. La sección definitiva se creará en P3, en `Drawing`.

### P2.0 · Pasos de planificación

1. En Fusion, espacio `Design`, abra el mismo modelo utilizado en P1 y confirme la característica que debe atravesar el corte.
2. Confirme qué característica debe atravesar el corte. No active todavía `Section View`.
3. Sobre una copia de la vista, una impresión o una hoja, dibuje la línea del plano de corte.
4. Coloque las flechas en la dirección de observación y repita la identificación, por ejemplo `A-A`.
5. Dibuje la sección esquemática, rayando únicamente las superficies atravesadas y dejando vacías las cavidades.
6. Guarde `S11_P2_CroquisCorte_Apellido_Nombre.png` como fotografía/escaneo del croquis o como captura de `Design` anotada.
7. Guarde `S11_P2_Seccion_Apellido_Nombre.png` como la sección esquemática rayada. No presente todavía una captura del `Drawing` como evidencia P2.

### P2.1 · Elementos del corte

| Elemento | Decisión aplicada |
|---|---|
| Vista donde se indica el corte | Vista de Superior o Vista Frontal |
| Posición del plano de corte | Longitud a lo largo del eje central de la pieza, atravesando el centro del agujero cilíndrico y la cavidad interior |
| Dirección de observación | Perpendicular al plano de corte, apuntando hacia la mitad posterior/interior que contiene las características a exponer  |
| Identificación | [A–A, con letras mayúsculas en los extremos del plano |
| Tipo de corte o sección | Corte total |



### P2.2 · Rayado

- ¿Qué superficies quedan cortadas?: Las paredes sólidas de material que atraviesa directamente el plano de corte
- ¿Qué superficies no deben rayarse?: Las cavidades, agujeros, muescas vacías y espacios de aire interiores que no contienen material sólido.
- ¿Cómo diferenció zonas o componentes adyacentes?: Cambiando la inclinación de las líneas de rayado o modificando el espaciado entre ellas para cada zona/pieza distinta
- ¿Qué separación utilizó entre las líneas de rayado?: Un espaciado uniforme y equidistante (aproximadamente entre 1.5 mm y 3 mm), proporcional al tamaño de la superficie cortada
- ¿Cómo evitó que el rayado invadiera textos o cotas?: Interrumpiendo el rayado alrededor del texto o cifra de cota, dejando una ventana en blanco despejada para mantener la legibilidad

### P2.3 · Diferencia conceptual

Explique con sus palabras la diferencia entre un corte y una sección.

[Respuesta]

### P2.4 · Correcciones

| Problema detectado | Corrección aplicada | Motivo de la corrección |
|---|---|---|
| [Respuesta] | [Respuesta] | [Respuesta] |
| [Respuesta] | [Respuesta] | [Respuesta] |

### Evidencias P2

**Qué debe contener cada imagen:**

- `S11_P2_CroquisCorte_Apellido_Nombre.png`: croquis de planificación basado en el modelo consultado en `Design`, con vista de origen, línea del plano de corte, flechas de observación y letras de identificación.
- `S11_P2_Seccion_Apellido_Nombre.png`: sección resultante identificada, superficies rayadas, cavidades sin rayado y zonas adyacentes diferenciadas cuando corresponda.

Un dibujo sin flechas, letras o rayado no demuestra el procedimiento completo.

Estas evidencias no tienen que ser capturas del espacio `Drawing`; el `Drawing` se trabaja en P3.

![P2: Croquis del corte](S11_P2_CroquisCorte_Apellido_Nombre.png)

![P2: Sección identificada](S11_P2_Seccion_Apellido_Nombre.png)

## P3 — Corte o sección en Fusion

**Propósito:** integrar el corte o la sección al Drawing de Semana 10 y comprobar su correspondencia con el modelo.

**Entorno:** Fusion, espacio `Drawing`. Aquí se crea la `Section View` o vista de sección definitiva. Se cambia a `Design` únicamente para verificar la correspondencia con el modelo 3D.

### P3.0 · Pasos en Fusion

1. Abra el archivo de `Drawing` de Semana 10 y confirme que conserva las vistas `Front`, `Top` y `Right` generadas en Semana 10. La tarea de Semana 11 no es volver a generarlas. Si no existe un `Drawing`, desde el diseño use `File > New Drawing > From Design` como recuperación del requisito de Semana 10.
2. En `Drawing`, seleccione la vista que debe generar la sección.
3. Ejecute la herramienta `Section View` desde la barra de creación del `Drawing`.
4. Dibuje la línea de corte siguiendo el croquis P2 y confirme la dirección de observación.
5. Coloque la vista resultante, conserve la identificación y revise el rayado generado por Fusion.
6. Edite la vista para corregir escala, separación, identificación o visibilidad de líneas. No dibuje rayado manual sobre el plano.
7. Cambie a `Design`, compare la sección con la cavidad real y tome la captura de verificación.
8. Regrese a `Drawing`, aplique correcciones y tome la captura del plano.

### P3.1 · Configuración

- Drawing utilizado: [Respuesta]
- Espacio de trabajo utilizado: `Drawing`
- Herramienta utilizada: `Section View`
- Vista de origen: [Respuesta]
- Tipo de corte: [Respuesta]
- Escala: [Respuesta]
- Identificación: [Respuesta]
- Dirección de observación: [Respuesta]

### P3.2 · Verificación con el modelo

| Elemento | ¿Coincide con el modelo? | Evidencia o corrección |
|---|---|---|
| Cavidad o agujero | [Respuesta] | [Respuesta] |
| Ranura o escalón | [Respuesta] | [Respuesta] |
| Contorno exterior | [Respuesta] | [Respuesta] |
| Superficies rayadas | [Respuesta] | [Respuesta] |
| Líneas visibles | [Respuesta] | [Respuesta] |

### P3.3 · Líneas ocultas

- ¿Qué líneas ocultas dejaron de ser necesarias?: [Respuesta]
- ¿Qué líneas visibles debieron conservarse?: [Respuesta]
- ¿Detectó alguna contradicción entre vistas?: [Respuesta]
- ¿Cómo verificó la dirección de observación?: [Respuesta]

### P3.4 · Errores y correcciones

| Error detectado | Evidencia que lo reveló | Corrección aplicada |
|---|---|---|
| [Respuesta] | [Respuesta] | [Respuesta] |
| [Respuesta] | [Respuesta] | [Respuesta] |

### Evidencias P3

**Qué debe contener cada imagen:**

- `S11_P3_PlanoSeccion_Apellido_Nombre.png`: captura de Fusion en el espacio `Drawing`, con las vistas de Semana 10, corte o sección incorporado, identificación, rayado y cotas legibles.
- `S11_P3_ModeloVerificacion_Apellido_Nombre.png`: captura del mismo modelo en el espacio `Design`, orientado para comprobar la cavidad, agujero, ranura o escalón representado.

La segunda imagen debe permitir comparar modelo y plano, no solo mostrar una pantalla genérica de Fusion.

![P3: Plano con sección](S11_P3_PlanoSeccion_Apellido_Nombre.png)

![P3: Verificación con modelo](S11_P3_ModeloVerificacion_Apellido_Nombre.png)

## P4 — Detalle ampliado y tolerancia introductoria

**Propósito:** ampliar una zona que no se lee con claridad e interpretar una tolerancia dimensional sencilla, únicamente cuando exista una justificación.

**Entorno:** Fusion, espacio `Drawing`. El detalle y la tolerancia se agregan al plano; no se modifica la geometría del modelo en `Design`.

### P4.0 · Pasos en Fusion

1. Abra el `Drawing` de P3 y permanezca en ese espacio de trabajo.
2. Seleccione la vista que contiene la característica difícil de leer.
3. Ejecute `Detail View`, encierre la zona y coloque la vista ampliada.
4. Asigne la letra de referencia y establezca la escala del detalle.
5. Agregue o edite la dimensión en el `Drawing`.
6. Configure una tolerancia únicamente si existe una razón funcional o una indicación explícita del ejercicio.
7. Si aplica una tolerancia, abra las propiedades de la dimensión, active la presentación disponible y registre valor nominal, límite superior e inferior.
8. Si no aplica una tolerancia, conserve la dimensión nominal y escriba la justificación.
9. Tome las tres capturas desde `Drawing`: zona de origen, detalle ampliado y dimensión/tolerancia.

### P4.1 · Detalle ampliado

- Zona seleccionada: [Respuesta]
- Motivo de la ampliación: [Respuesta]
- Letra asignada: [Respuesta]
- Escala del detalle: [Respuesta]
- Vista de origen: [Respuesta]
- Herramienta utilizada en `Drawing`: `Detail View`
- Espacio de trabajo utilizado: `Drawing`

### P4.2 · Tolerancia introductoria

- Dimensión nominal: [Respuesta]
- Tolerancia aplicada: [Respuesta]
- Límite superior: [Respuesta]
- Límite inferior: [Respuesta]
- Motivo funcional o indicación del enunciado: [Respuesta]

**Criterio de cálculo:** en la fórmula `D_min = D_N - T_inf`, `T_inf` se registra como magnitud positiva de la desviación inferior. Si la desviación se escribe con signo, por ejemplo `-0,10 mm`, el límite se calcula como `D_N + (-0,10 mm)`.

### P4.3 · Interpretación

Interprete el ejemplo didáctico `20 ± 0,1 mm`.

- Valor nominal: [Respuesta]
- Valor máximo permitido: [Respuesta]
- Valor mínimo permitido: [Respuesta]

### P4.4 · Decisión técnica

¿La tolerancia era necesaria para este plano? Justifique sin inventar requisitos de fabricación.

[Respuesta]

### Evidencias P4

**Qué debe contener cada imagen:**

- `S11_P4_ZonaDetalle_Apellido_Nombre.png`: captura del `Drawing` con la zona de origen encerrada o señalada con una letra.
- `S11_P4_Detalle_Apellido_Nombre.png`: detalle creado en el `Drawing`, con letra de referencia y escala.
- `S11_P4_Tolerancia_Apellido_Nombre.png`: dimensión nominal y tolerancia aplicada en el `Drawing`, o anotación que explique por qué se mantuvo solo la dimensión nominal.

No basta con escribir una tolerancia sin justificarla.

![P4: Zona de detalle](S11_P4_ZonaDetalle_Apellido_Nombre.png)

![P4: Detalle ampliado](S11_P4_Detalle_Apellido_Nombre.png)

![P4: Tolerancia](S11_P4_Tolerancia_Apellido_Nombre.png)

## P5 — Plano final y verificación

**Propósito:** revisar el plano completo mediante la rúbrica y preparar la Prueba Corta 2.

**Entorno:** la revisión y las correcciones se realizan principalmente en Fusion, espacio `Drawing`. Se cambia a `Design` para comparar el plano final con el modelo 3D y luego se vuelve a `Drawing` para corregir o guardar.

### P5.0 · Pasos en Fusion

1. En `Drawing`, abra la versión que conserva las vistas `Front`, `Top` y `Right`, además del corte o la sección de P3 y el detalle de P4.
2. Compruebe vistas, identificación, dirección de observación, rayado, líneas ocultas, cotas, detalle y tolerancia.
3. Cambie a `Design` y compare cada característica interior con el modelo 3D.
4. Regrese a `Drawing`, corrija el plano y guarde la versión final en Fusion Cloud.
5. Tome `S11_P5_PlanoFinal_Apellido_Nombre.png` mostrando el `Drawing` completo, el nombre del diseño y la información legible.
6. Prepare `S11_P5_Verificacion_Apellido_Nombre.png` como una sola imagen con un recorte del plano final y otro del modelo verificado, etiquetados `Drawing` y `Design`.
7. Complete el checklist y registre qué cambió, qué evidencia motivó el cambio y cómo verificó el resultado.

### P5.1 · Lista de comprobación

- [ ] El corte atraviesa la característica relevante.
- [ ] La dirección de observación es correcta.
- [ ] Las letras y flechas son coherentes.
- [ ] El rayado representa únicamente superficies cortadas.
- [ ] Las áreas adyacentes se diferencian.
- [ ] Se eliminaron líneas ocultas innecesarias.
- [ ] Las cotas siguen siendo legibles.
- [ ] El detalle tiene letra y escala.
- [ ] La tolerancia está justificada o se documentó por qué no se agregó.
- [ ] El plano coincide con el modelo 3D.
- [ ] No hay superposiciones ni información redundante.

### P5.2 · Revisión por pares

| Criterio revisado | Observación recibida | Corrección realizada |
|---|---|---|
| Corte o sección | [Respuesta] | [Respuesta] |
| Rayado | [Respuesta] | [Respuesta] |
| Detalle | [Respuesta] | [Respuesta] |
| Tolerancia | [Respuesta] | [Respuesta] |
| Legibilidad | [Respuesta] | [Respuesta] |

### P5.3 · Preparación para la Prueba Corta 2

- Una situación en la que conviene una sección: [Respuesta]
- Diferencia entre corte y sección: [Respuesta]
- Función del rayado: [Respuesta]
- Función de las flechas del plano de corte: [Respuesta]
- Significado de una tolerancia bilateral: [Respuesta]

### Evidencias P5

**Qué debe contener cada imagen:**

- `S11_P5_PlanoFinal_Apellido_Nombre.png`: captura final de Fusion en el espacio `Drawing`, con vistas, corte o sección, rayado, cotas, detalle y tolerancia cuando corresponda, sin superposiciones importantes.
- `S11_P5_Verificacion_Apellido_Nombre.png`: comparación final entre el plano en `Drawing` y el modelo 3D en `Design`, con una orientación que permita comprobar la geometría representada.

Estas imágenes deben respaldar el checklist y las correcciones registradas en la ficha.

![P5: Plano final](S11_P5_PlanoFinal_Apellido_Nombre.png)

![P5: Verificación final](S11_P5_Verificacion_Apellido_Nombre.png)

## Reflexión final

### 1. ¿Por qué fue necesario utilizar un corte o una sección?

[Respuesta]

### 2. ¿Qué diferencia existe entre corte y sección?

[Respuesta]

### 3. ¿Qué característica fue más difícil de representar?

[Respuesta]

### 4. ¿Qué corrección mejoró más la legibilidad del plano?

[Respuesta]

### 5. ¿Qué aprendí sobre tolerancias introductorias?

[Respuesta]

## Referencia de Fusion

Para los comandos del software consulte la documentación oficial vigente de Autodesk Fusion sobre los espacios `Design` y `Drawing`, `Inspect > Section Analysis`, `Section View`, `Detail View` y edición de dimensiones: <https://help.autodesk.com/view/fusion360/ENU/>.

## Cierre de la ficha

- [ ] Completé las respuestas de P1 a P5.
- [ ] Incorporé las evidencias con la nomenclatura solicitada.
- [ ] Las imágenes se visualizan correctamente desde GitHub.
- [ ] El modelo y el Drawing están disponibles en Fusion Cloud con acceso docente.
- [ ] Documenté las correcciones sin borrar decisiones iniciales.
- [ ] Publiqué los últimos cambios en GitHub.

Commit sugerido: `S11 ejercicios cortes secciones Apellido Nombre`.

Corrección posterior: `S11 correccion plano seccion Apellido Nombre`.
