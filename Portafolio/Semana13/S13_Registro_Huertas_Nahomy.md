# ICT401 · Semana 13 — Registro de ensamblaje básico

12 al 17 de octubre de 2026.

- Estudiante: Nahomy Huertas Esquivel
- Grupo: 60
- Proyecto de Fusion Cloud con acceso docente: Nahomy Huertas
- Nombre del diseño de ensamblaje: ICT401_S13_L1_Huertas_Nahomy
- Piezas base utilizadas: ICT401_S13_01_Base_100x70x10, ICT401_S13_02_Soporte_60x70x40 y ICT401_S13_03_Pasador_D16x80.
- Fecha de trabajo de laboratorio: 15/10/2026

## Instrucciones

Utilice esta plantilla en `Portafolio/semana13/` y guárdela como `S13_Registro_Apellido_Nombre.md`. Sustituya `Apellido_Nombre` por un apellido y un nombre sin espacios ni tildes. Complete cada `[Respuesta]` durante las cuatro lecciones prácticas y agregue las imágenes solicitadas junto con la ficha.

La sesión virtual del miércoles se dedica a la revisión oral del Proyecto Integrador. Este registro corresponde únicamente a las cuatro lecciones prácticas de laboratorio. La actividad es formativa y no sustituye las evaluaciones oficiales posteriores.

Trabaje con las piezas base proporcionadas por la persona docente. Si todavía no se han distribuido, use las imágenes PNG y las dimensiones de esta ficha para construirlas. No modifique los archivos originales ni oculte un componente para evitar una interferencia. Si su versión de Fusion utiliza otro nombre de comando, escriba el nombre real utilizado y describa su función.

Ayuda oficial de Fusion: [Fusion Help](https://help.autodesk.com/view/fusion360/ENU/), sección `Assemblies`.

## Conjunto de trabajo

Dimensiones nominales de referencia: base maciza `100 x 70 x 10 mm`; soporte de `60 mm` de ancho, `70 mm` de alto y `40 mm` de fondo, con alojamiento pasante `diametro 16 mm`; pasador `diametro 16 x 80 mm`.

![Ensamblaje básico de referencia](ICT401_S13_Ensamblaje_Basico.png)

### Posicionamiento exacto

El soporte se centra sobre la base, no se coloca en una esquina:

- Margen lateral: `20 mm` a cada lado, porque `(100 - 60) / 2 = 20 mm`.
- Margen frontal y posterior: `15 mm` a cada lado, porque `(70 - 40) / 2 = 15 mm`.
- Cara inferior del soporte coincidente con la cara superior de la base.
- Relación base-soporte: `Rígida (Rigid)`.
- Centro del alojamiento: `40 mm` desde la cara inferior del soporte y `30 mm` desde cada lado del soporte.
- Pasador: coaxial con el alojamiento, centrado en el espesor de la pared y con relación `Revolute (Revoluta)`.
- Si la pared mide `10 mm`, el pasador de `80 mm` sobresale aproximadamente `35 mm` a cada lado.

No registre una distancia desde una esquina para ubicar el pasador. Su posición queda definida por el centro del alojamiento.

| Componente | Nombre en Fusion | Función dentro del conjunto | Observación inicial |
|---|---|---|---|
| Base | [Respuesta] | [Respuesta] | [Respuesta] |
| Soporte vertical | [Respuesta] | [Respuesta] | [Respuesta] |
| Eje o pasador | [Respuesta] | [Respuesta] | [Respuesta] |

## Comandos bilingues de Fusion

| Accion | Ruta o comando | Resultado esperado |
|---|---|---|
| Crear diseño | `Archivo > Nuevo diseño (File > New Design)` | Diseño vacío y proyecto confirmado en el Panel de datos. |
| Insertar pieza | `Insertar en el diseño actual (Insert into Current Design)` | Componente visible en el Navegador. |
| Fijar base | Clic derecho en Navegador > `Fijar (Ground)` | La base no se desplaza ni gira. |
| Relacionar soporte | `Ensamblar > Unión (Assemble > Joint)` > `Rígida (Rigid)` | El soporte queda unido a la base. |
| Relacionar pasador | `Ensamblar > Unión (Assemble > Joint)` > `Revoluta (Revolute)` | El pasador gira alrededor de su eje. |
| Probar relación | Clic derecho en la unión > `Animar unión (Drive Joint)` | Se comprueba el movimiento permitido. |
| Revisar interferencias | `Inspeccionar > Interferencia (Inspect > Interference)` > `Calcular (Compute)` | Se identifican cuerpos que ocupan el mismo volumen. |
| Editar relación | Clic derecho en la relación > `Editar (Edit)` | Se corrige origen, orientación, tipo o desplazamiento. |

Registre en cada lección qué componente seleccionó, qué comando utilizó y qué resultado observó. No se considera suficiente escribir solo el nombre de la herramienta.

## L1 — Reconocimiento de piezas y componente base

### Diagnóstico

- ¿Qué pieza funcionará como base y por qué?:  La pieza base 100 × 70 × 10 mm porque sirve como apoyo para el soporte y mantiene estable el ensamblaje.
- ¿Qué superficies de la base y del soporte podrían entrar en contacto?: La superficie superior de la base y la superficie inferior del soporte.
- ¿Qué eje o alojamiento utilizará el pasador?: [Respuesta]
- ¿Qué movimiento estaba libre antes de aplicar relaciones?: [Respuesta]
- ¿Qué orientación inicial seleccionó y por qué?: [Respuesta]

### Estado inicial

| Comprobación | Resultado |
|---|---|
| Base insertada como componente | [Sí/No + explicación] |
| Base fija o establecida como referencia | [Sí/No + comando] |
| Soporte insertado | [Sí/No] |
| Eje o pasador disponible | [Sí/No] |
| Nombres identificables en el navegador | [Sí/No] |

### Evidencia L1

`S13_PiezasBase_Apellido_Nombre.png`: captura del ensamblaje con la base y el soporte visibles, el navegador de componentes abierto y los nombres identificables.

![L1: piezas base](S13_PiezasBase_Apellido_Nombre.png)

## L2 — Relaciones entre componentes

### Decisiones

| Relación | Componentes o geometrías vinculadas | Movimiento que elimina | Movimiento que conserva | Resultado |
|---|---|---|---|---|
| 1 | [Respuesta] | [Respuesta] | [Respuesta] | [Respuesta] |
| 2 | [Respuesta] | [Respuesta] | [Respuesta] | [Respuesta] |

- Comando o herramienta utilizada: [Respuesta]
- ¿Por qué esa relación representa la intención del conjunto?: [Respuesta]
- ¿La orientación del soporte quedó correcta?: [Sí/No + explicación]
- ¿Qué movimiento debe conservar el eje?: [Respuesta]
- ¿Qué movimiento inesperado observó y cómo lo corrigió?: [Respuesta]

### Evidencia L2

`S13_Relaciones_Apellido_Nombre.png`: captura del navegador de componentes y de la relación aplicada, con el conjunto orientado para leer la posición del soporte y del eje.

![L2: relaciones](S13_Relaciones_Apellido_Nombre.png)

## L3 — Revisión de interferencias

- Herramienta utilizada: [Respuesta]
- Componentes comparados: [Respuesta]
- ¿Se encontró una interferencia?: [Sí/No]
- Ubicación de la condición: [Respuesta]
- ¿Se trata de interferencia, contacto previsto o separación intencional?: [Respuesta]
- Causa probable: [Respuesta]
- ¿Qué efecto tendría sobre el funcionamiento del conjunto?: [Respuesta]

| Componente A | Componente B | Zona revisada | Resultado | Evidencia |
|---|---|---|---|---|
| [Respuesta] | [Respuesta] | [Respuesta] | [Respuesta] | [Respuesta] |

### Evidencia L3

`S13_Interferencia_Apellido_Nombre.png`: captura del análisis o de la zona problemática, con los componentes involucrados identificables.

![L3: interferencia](S13_Interferencia_Apellido_Nombre.png)

## L4 — Corrección, verificación y cierre

### Registro de corrección

- Problema seleccionado: [Respuesta]
- Corrección prevista antes de modificar: [Respuesta]
- Componente o relación modificada: [Respuesta]
- Cambio aplicado: [Respuesta]
- Resultado del segundo análisis: [Respuesta]
- ¿La base continúa estable?: [Sí/No]
- ¿El soporte conserva su orientación?: [Sí/No]
- ¿El eje conserva el movimiento esperado?: [Sí/No]
- Versión o nombre final en Fusion Cloud: [Respuesta]

| Comprobación final | Resultado | Evidencia o explicación |
|---|---|---|
| Componentes visibles y nombrados | [Conforme/No conforme] | [Respuesta] |
| Relaciones comprensibles | [Conforme/No conforme] | [Respuesta] |
| Movimiento esperado | [Conforme/No conforme] | [Respuesta] |
| Interferencia revisada | [Conforme/No conforme] | [Respuesta] |
| Corrección documentada | [Conforme/No conforme] | [Respuesta] |

### Evidencia L4

`S13_Correccion_Apellido_Nombre.png`: captura comparativa o lámina con el estado problemático y el estado corregido, ambos etiquetados.

![L4: corrección](S13_Correccion_Apellido_Nombre.png)

## Checklist de cierre

- [ ] Las tres piezas base corresponden al conjunto indicado.
- [ ] La base está fija o definida como referencia.
- [ ] Los componentes tienen nombres identificables.
- [ ] Cada relación aplicada tiene una intención explicable.
- [ ] El movimiento permitido corresponde a la función del conjunto.
- [ ] Se ejecutó una revisión de interferencias.
- [ ] La interferencia o ausencia de interferencia quedó interpretada.
- [ ] La corrección quedó registrada antes y después.
- [ ] El ensamblaje fue guardado en Fusion Cloud.
- [ ] La ficha y las imágenes utilizan la nomenclatura solicitada.
- [ ] No se adelantaron vistas explosionadas ni listas de componentes.

## Reflexión final

1. ¿Qué diferencia encontró entre insertar piezas y construir un ensamblaje con relaciones?: [Respuesta]
2. ¿Qué relación fue más difícil de definir y por qué?: [Respuesta]
3. ¿Cómo distinguió una interferencia de un contacto previsto?: [Respuesta]
4. ¿Qué comprobará en Semana 14 antes de generar una vista explosionada o una lista de componentes?: [Respuesta]

## Revisión docente

- Observación sobre componentes y nombres: [Respuesta]
- Observación sobre relaciones: [Respuesta]
- Observación sobre interferencias: [Respuesta]
- Corrección sugerida: [Respuesta]
- Estado del registro: [Pendiente/Completo]
## Checklist de cierre

- [ ] Las tres piezas base corresponden al conjunto indicado.
- [ ] La base está fija o definida como referencia.
- [ ] Los componentes tienen nombres identificables.
- [ ] Cada relación aplicada tiene una intención explicable.
- [ ] El movimiento permitido corresponde a la función del conjunto.
- [ ] Se ejecutó una revisión de interferencias.
- [ ] La interferencia o ausencia de interferencia quedó interpretada.
- [ ] La corrección quedó registrada antes y después.
- [ ] El ensamblaje fue guardado en Fusion Cloud.
- [ ] La ficha y las imágenes utilizan la nomenclatura solicitada.
- [ ] No se adelantaron vistas explosionadas ni listas de componentes.

## Reflexión final

1. ¿Qué diferencia encontró entre insertar piezas y construir un ensamblaje con relaciones?: [Respuesta]
2. ¿Qué relación fue más difícil de definir y por qué?: [Respuesta]
3. ¿Cómo distinguió una interferencia de un contacto previsto?: [Respuesta]
4. ¿Qué comprobará en Semana 14 antes de generar una vista explosionada o una lista de componentes?: [Respuesta]

## Revisión docente

- Observación sobre componentes y nombres: [Respuesta]
- Observación sobre relaciones: [Respuesta]
- Observación sobre interferencias: [Respuesta]
- Corrección sugerida: [Respuesta]
- Estado del registro: [Pendiente/Completo]
