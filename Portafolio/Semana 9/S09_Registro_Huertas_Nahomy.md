# ICT401 · Semana 9 — Registro de interpretación y reconstrucción 3D

14 al 19 de septiembre de 2026.

- Estudiante: Nahomy Marcela Huertas Esquivel
- Grupo: 60
- Carpeta o proyecto de Fusion Cloud con acceso docente: [Respuesta]
- Copias personales: `ICT401_S09_P1_Apellido_Nombre`, `ICT401_S09_P2_Apellido_Nombre`, `ICT401_S09_P3_Apellido_Nombre`.

## Instrucciones

Copie esta plantilla a `Portafolio/semana09/` y guárdela como `S09_Registro_Apellido_Nombre.md`. Sustituya `Apellido_Nombre` por un apellido y un nombre sin espacios ni tildes. Complete cada `[Respuesta]`, agregue las imágenes solicitadas en la misma carpeta y haga commit.

Conserve siempre la estrategia inicial. Si modifica una decisión durante el modelado, no borre lo anterior: describa qué cambió, qué evidencia del plano o del modelo motivó la corrección y qué elemento paramétrico modificó.

X = ancho, Y = profundidad, Z = altura. Trabaje en milímetros. Cuando compare vistas, mantenga Front, Top y Right con orientación coherente y cámara ortográfica.

---

## P1 — Del plano a la estrategia de modelado

### P1.1 · Dimensiones generales identificadas antes de abrir Fusion

- X total: 70mm
- Y total: 40mm
- Z total: 40mm

### P1.2 · Características geométricas identificadas

| Característica | Descripción | Vista(s) que la definen | Dimensiones asociadas |
|---|---|---|---|
| 1 | Base rectangular | Frontal, Superior y Derecha | 70 × 40 × 20 mm |
| 2 | Resalte posterior izquierdo | Frontal, Superior y Derecha | 30 × 20 × 40 mm |
| 3 | Posición del resalte | Superior y Frontal | Ubicado en la parte posterior izquierda |
| 4 | Altura final de la pieza | Derecha y Frontal | 40 mm |

### P1.3 · ¿Qué plano de boceto utilizará primero y por qué?

Utilizaré el plano XY (TSuperior) porque permite definir el ancho y la profundidad de la pieza, además de ubicar correctamente el resalte.

### P1.4 · Estrategia inicial de modelado

1. Crear un boceto en el plano XY tomando como referencia la vista Superior.
2. Dibujar la base con sus dimensiones de 70 × 40 mm.
3. Definir en el mismo boceto la posición y dimensiones del resalte.
4. Extruir la base y luego crear el resalte hasta alcanzar las alturas indicadas.
5. Comprobar el modelo comparando las vistas Frontal, Superior y Derecha
   
### P1.5 · Después de comprobar en Fusion, ¿qué parte de la estrategia funcionó y qué tuvo que corregir?

La estrategia de comenzar con la vista superior funcionó para definir correctamente el ancho, la profundidad y la posición del resalte. Tuve que corregir la altura del resalte al comparar el modelo con las vistas del plano.

### P1.6 · ¿Qué vista o dimensión permitió detectar la corrección?

La vista Front permitió detectar la corrección, ya que al compararla con el modelo se pudo verificar la altura total de 40 mm y la altura del resalte. Esto permitió identificar que era necesario ajustar la altura para que coincidiera correctamente con las dimensiones indicadas en el plano.

### Evidencias P1

Modelo parcial o final en orientación pictórica, con nombre del diseño y ViewCube visibles.

![P1: Modelo](S09_P1_Modelo_Apellido_Nombre.png)

Captura donde se vea el Sketch, dimensión u operación que mejor representa la estrategia seguida.

![P1: Estrategia](S09_P1_Estrategia_Apellido_Nombre.png)

---

## P2 — Dos estrategias para una misma pieza

### P2.1 · Resuma la estrategia A

Consiste en construir en el plano XZ el perfil frontal completo en L, con 72 mm de ancho, 36 mm de altura total y una base de 28 mm de altura, extruirlo 36 mm de profundidad y posteriormente crear la perforación vertical pasante de 12 mm, ubicada según el centro indicado en Superior.

### P2.2 · Resuma la estrategia B

Consiste en construir primero la base desde un boceto en el plano XY, con 72 mm de ancho y 36 mm de profundidad, y extruirla hasta la altura de 28 mm. Luego se crea la torre izquierda mediante un segundo boceto y una segunda extrusión Join hasta alcanzar la altura total de 36 mm. Finalmente, se realiza la perforación vertical pasante de 12 mm, cuyo centro está indicado en Top como (14, 18).

### P2.3 · ¿Ambas estrategias pueden producir la misma geometría? Justifique.

Sí, ambas estrategias pueden producir la misma geometría final de 72 × 36 × 36 mm, con una base de 28 mm de altura y una perforación pasante de 12 mm ubicada en el centro (14, 18). La diferencia está en la forma de construirla: la estrategia A parte del perfil frontal completo, mientras que la estrategia B construye primero la base, después la torre y finalmente la perforación.

### P2.4 · Compare las estrategias

| Criterio | Estrategia A | Estrategia B | ¿Cuál considera mejor y por qué? |
|---|---|---|---|
| Número de operaciones | Un boceto del perfil en L de 72 × 36 mm, con base de 28 mm, una extrusión de 36 mm y una perforación 12 mm. | [Respuesta] | [Respuesta] |
| Claridad de intención de diseño | Define desde el inicio el perfil escalonado de 72 mm de ancho y 36 mm de altura, con la base de 28 mm. | [Respuesta] | [Respuesta] |
| Facilidad de edición | [Para cambiar las dimensiones principales, como los 72 mm de ancho o los 28 mm de altura de la base, se modifica el Sketch principal. El agujero 12 mm se modifica aparte. | El cuerpo principal depende del perfil en L y de la extrusión de 36 mm; la perforación se agrega después. | [Respuesta] |
| Dependencia entre operaciones | El cuerpo principal depende del perfil en L y de la extrusión de 36 mm; la perforación se agrega después. | [Respuesta] | [Respuesta] |
| Correspondencia con el plano | Se relaciona directamente con Front: 72 mm de ancho, 36 mm de altura y 28 mm de base; Top aporta la posición y diámetro del agujero Ø12 mm. | [Respuesta] | [Respuesta] |

### P2.5 · Si cambia una dimensión principal de la pieza, ¿qué estrategia sería más fácil de modificar? Explique qué Sketch u operación tendría que editar.

[Respuesta]

### P2.6 · ¿Cuál estrategia usaría finalmente y por qué?

[Respuesta]

### Evidencias P2

Captura del historial/timeline y del modelo obtenido con la estrategia seleccionada.

![P2: Estrategia seleccionada](S09_P2_Estrategia_Apellido_Nombre.png)

---

## P3 — Plano → modelo → plano

### P3.1 · Antes de modelar, describa la pieza en una frase técnica

[Respuesta]

### P3.2 · Dimensiones y características clave

| Elemento | Valor o descripción | Vista(s) de donde se obtiene |
|---|---|---|
| X total | [Respuesta] | [Respuesta] |
| Y total | [Respuesta] | [Respuesta] |
| Z total | [Respuesta] | [Respuesta] |
| Característica 1 | [Respuesta] | [Respuesta] |
| Característica 2 | [Respuesta] | [Respuesta] |
| Característica 3 | [Respuesta] | [Respuesta] |

### P3.3 · Estrategia inicial

1. [Respuesta]
2. [Respuesta]
3. [Respuesta]
4. [Respuesta]
5. [Respuesta]

### P3.4 · Verificación de vistas

| Vista | ¿Coincide con el plano? | Contorno/característica comprobada | Corrección realizada |
|---|---|---|---|
| Front | [Respuesta] | [Respuesta] | [Respuesta] |
| Top | [Respuesta] | [Respuesta] | [Respuesta] |
| Right | [Respuesta] | [Respuesta] | [Respuesta] |

### P3.5 · Verificación dimensional

| Dimensión crítica | Valor del plano | Valor medido en Fusion | Elemento medido | ¿Coincide? |
|---|---|---|---|---|
| 1 | [Respuesta] | [Respuesta] | [Respuesta] | [Respuesta] |
| 2 | [Respuesta] | [Respuesta] | [Respuesta] | [Respuesta] |
| 3 | [Respuesta] | [Respuesta] | [Respuesta] | [Respuesta] |
| 4 | [Respuesta] | [Respuesta] | [Respuesta] | [Respuesta] |

### P3.6 · ¿Qué cambió entre su estrategia inicial y el modelo final?

[Respuesta]

### P3.7 · Si tuviera que cambiar una dimensión principal, ¿qué Sketch, dimensión u operación editaría?

[Respuesta]

### Evidencias P3

Modelo final en orientación pictórica, con nombre y ViewCube visibles.

![P3: Modelo final](S09_P3_Modelo_Apellido_Nombre.png)

Montaje de Front, Top y Right del modelo para compararlos con el plano.

![P3: Vistas](S09_P3_Vistas_Apellido_Nombre.png)

Captura de una comprobación dimensional con `Inspect > Measure`.

![P3: Medicion](S09_P3_Medicion_Apellido_Nombre.png)

---

## Reflexión final

La diferencia principal entre reconstruir una pieza en Semana 8 y reconstruirla desde un plano en Semana 9 es:

[Respuesta]

Antes de abrir Fusion, la información mínima que debo extraer de un plano es:

[Respuesta]

Una estrategia de modelado es mejor que otra cuando:

[Respuesta]

La comprobación final más importante para asegurar que el modelo corresponde al plano es:

[Respuesta]

## Checklist

- [ ] Registré la estrategia inicial de P1 antes de comprobar en Fusion.
- [ ] Comparé dos estrategias en P2 y justifiqué mi selección.
- [ ] Reconstruí P3 a partir del plano sin usar un modelo 3D de referencia.
- [ ] Comparé Front, Top y Right contra el plano.
- [ ] Verifiqué al menos cuatro dimensiones críticas en P3.
- [ ] Documenté las correcciones sin borrar mis decisiones iniciales.
- [ ] Las cinco imágenes se visualizan correctamente en GitHub.
- [ ] Los modelos P1–P3 están disponibles en Fusion Cloud con acceso docente.
- [ ] Completé la reflexión final.

Commit sugerido: `S09 ejercicios Fusion Apellido Nombre`.

Corrección posterior: `S09 correccion Fusion Apellido Nombre`.
