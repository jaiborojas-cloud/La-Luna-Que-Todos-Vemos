# Hoja de ruta — Obra derivada (ontología relacional)

> **Para quien retome esto (tú o una sesión futura de Claude):** empieza por
> aquí. Este archivo dice en qué punto está la obra derivada, qué se decidió ya
> (para no re-discutirlo) y cuáles son los caminos naturales a seguir, en orden.
> El texto fundacional es `00-documento-puente.md`, en esta misma carpeta.

Última actualización: 2026-07-31.

---

## 1. Cómo retomar en 60 segundos

El proyecto tiene **tres piezas** dentro del repo `La-Luna-Que-Todos-Vemos`:

| Pieza | Dónde | Qué es |
|---|---|---|
| **Obra original** | `capitulos/`, `docs/`, `recursos/`, `CLAUDE_CONTEXT.md` | *La Luna Que Todos Vemos* / MENTEMONEDA. Neuro-poético-existencial. Ya escrita (parcial). |
| **Repo-herramienta** | `extraccion-ideas/` | Extracción de ideas que alimenta a las dos obras. NO es una obra. Ver sus `indice.md` (notas) e `indice-obra.md` (obra). |
| **Obra derivada** | `ontologia-relacional/` ← *estás aquí* | La obra "más rigurosa". Fundada en `00-documento-puente.md`. En estado embrionario. |

**Estado de la obra derivada:** existe su columna argumentativa (el documento-
puente) y esta hoja de ruta. **No hay capítulos, ni estructura de libro, ni
prosa desarrollada todavía.** El siguiente trabajo es §4 de este archivo.

---

## 2. Decisiones ya tomadas (NO re-litigar sin motivo)

1. **Son dos obras distintas, casi disjuntas.** Solo 4 de las 16 unidades de las
   notas aparecen en la obra original. La derivada es *sistémica/epistémica*; la
   original es *neuro-poético-existencial*.
2. **El puente entre ambas es la metáfora de la moneda:** abstracta en las notas
   (`mente-como-denominacion-moneda-cognitiva`), encarnada en la obra
   (`pago-metabolico-de-la-conciencia`).
3. **Registro de la obra derivada: filosófico riguroso.** Argumentación formal,
   citas reales, y la regla de oro (abajo).
4. **La obra derivada vive en carpeta propia** (`ontologia-relacional/`), separada
   del repo-herramienta de extracción.
5. **La extracción está cerrada** para el material actual (3 notas + la obra).
   Reabrir solo si aparece material nuevo.

## 3. Reglas permanentes del proyecto

- **Regla de oro (rigor):** toda afirmación se marca como **literal** /
  **demostrable** / **tesis argumentada** / **analógica**. Ninguna puede citarse
  con el estatuto de otra. (Ver la tabla del §6 del documento-puente.)
- **La moneda ilumina, no demuestra.** Si un pasaje usa la metáfora como si fuera
  mecanismo, está fuera de rigor.
- **Los commits los hace el usuario, a mano.** Claude no commitea salvo que se le
  pida explícitamente.
- **No proponer estructura de libro / capítulos** hasta que la columna
  argumentativa esté sólida y verificada (es decir, hasta cerrar buena parte del
  §4).
- **Verificar antes de publicar:** las referencias del documento-puente son
  atribuciones estándar SIN cotejar contra ediciones originales (ver §4, camino C).

---

## 4. Caminos naturales a seguir (en orden de prioridad)

Cada camino es independiente; pueden tomarse de a uno. El "criterio de hecho" dice
cuándo considerarlo terminado.

### Camino A — Formalizar la bisagra inferencia activa → "buen regulador" ★ prioridad alta
- **Qué:** demostrar (o acotar) bajo qué condiciones un sistema de inferencia
  activa (Friston) hereda el límite de Conant-Ashby (todo buen regulador es un
  modelo del sistema → auto-modelado completo imposible).
- **Por qué:** es el eslabón HOY MÁS DÉBIL y el de mayor rédito. Si se sostiene,
  el "nudo" (§3 del documento-puente) pasa de *síntesis argumentada* a algo mucho
  más firme, y con ello todo el edificio.
- **Dónde toca:** documento-puente §2, §3 y §7.1.
- **Criterio de hecho:** un argumento escrito, con sus supuestos explícitos, que
  diga qué se demuestra y qué queda como tesis.

### Camino B — Desarrollar el "nudo" como primer capítulo real
- **Qué:** convertir el §3 del documento-puente (micro y macro son el mismo
  límite: termodinámica ↔ lógica) en un capítulo completo y autónomo.
- **Por qué:** es el corazón conceptual y el mejor punto de entrada al libro;
  obliga a poner a prueba la claridad de la tesis central.
- **Dónde toca:** nuevo archivo `ontologia-relacional/01-el-nudo.md`.
- **Criterio de hecho:** un capítulo que un lector filosófico pueda leer solo y
  seguir el argumento sin haber leído las notas.
- **Depende de:** idealmente, avanzar antes el Camino A.

### Camino C — Verificar y afinar las referencias
- **Qué:** cotejar con búsqueda web / fuentes las citas del documento-puente
  (ediciones, páginas, formulación exacta). Prioridad: **Conant-Ashby (1970)** y
  **el alcance real que Friston reclama** para el principio de energía libre
  (marco influyente pero debatido).
- **Por qué:** el rigor prometido exige que las fuentes resistan escrutinio.
- **Dónde toca:** documento-puente, sección "Referencias" y nota de verificación.
- **Criterio de hecho:** cada referencia con edición/página confirmada y cada
  atribución con su formulación exacta.

### Camino D — Precisar "emergencia" de la realidad compartida
- **Qué:** dar un criterio operacional que distinga la realidad compartida
  emergente de un simple promedio estadístico de percepciones.
- **Por qué:** hoy "emergencia" hace trabajo pesado sin definición fuerte (§7.2).
- **Dónde toca:** documento-puente §4; unidad `conocimiento-distribuido`.
- **Criterio de hecho:** una definición que permita decir qué contaría como
  contraejemplo.

### Camino E — Poner a prueba la propia metáfora monetaria
- **Qué:** responder: ¿qué explica la teoría relacional CON la moneda que no
  explique SIN ella? Si nada, es ornamento; si algo, nombrarlo.
- **Por qué:** es el test de honestidad del puente entero (§7.3).
- **Dónde toca:** documento-puente §5 y §7.3.
- **Criterio de hecho:** una lista de lo que la metáfora añade (o la decisión
  justificada de degradarla a recurso expositivo).

### Camino F — La conciencia (dejar como pregunta abierta, gestionada)
- **Qué:** NO resolver por metáfora. Mantener y desarrollar las vías de
  `circulacion-consciente-pregunta-abierta` como problema abierto declarado.
- **Por qué:** el documento explica incompletud y distribución, no *por qué hay
  experiencia*. Colarlo por analogía rompería la regla de oro.
- **Dónde toca:** documento-puente §7.4; unidades `circulacion-consciente-...`,
  `conciencia-como-forma-de-relacion`.
- **Criterio de hecho:** que siga marcado como abierto y no se contamine con los
  otros pisos.

### Camino G — Situarse frente a la literatura ★ prioridad alta
- **Qué:** posicionar el proyecto frente a los vecinos más cercanos y decir, para
  cada uno, *en qué coincide y en qué se separa*. Mínimo obligado: **Simondon**
  (la relación precede a los términos), **Karen Barad** (los relata no preexisten
  a las relaciones), **Thomas Metzinger** (*Being No One*: no hay self completo,
  solo un modelo fenoménico del self — el vecino más cercano), **Ladyman & Ross**
  (realismo estructural óntico), **Luhmann** (punto ciego del sistema que se
  auto-observa), **Whitehead**, **Hofstadter** (*strange loops*) y **Nāgārjuna**
  (originación dependiente). Simmel ya está en el documento-puente.
- **Por qué:** cada pilar del proyecto (relación primaria, límites del
  autoconocimiento, cognición distribuida, cerebro predictivo, moneda relacional)
  ya está muy poblado. La originalidad NO está en los ladrillos, solo en la
  construcción. Sin este posicionamiento, el primer lector informado desarma el
  proyecto como "otra versión de la ontología relacional". Con él, se vuelve *tu*
  ontología relacional. Es además insumo directo del Camino E (qué añade tu
  versión = §7.3).
- **Dónde toca:** nuevo archivo `ontologia-relacional/02-estado-de-la-cuestion.md`;
  retroalimenta documento-puente §5 y §7.3.
- **Criterio de hecho:** para cada autor/tradición, una línea "coincide en X / me
  separo en Y", y una frase final que nombre el diferencial propio.

### Orden sugerido
**A → C → G → B → D → E**, con **F** como restricción permanente (no un paso).
A, C y G pueden ir en paralelo. B se beneficia de tener A, C y G hechos; E (el
test de la metáfora) depende de G.

> **Reencuadre de la ambición (2026-07-31):** el objetivo NO es "una filosofía
> nueva" (los pilares ya existen), sino **(a)** una síntesis con voz propia,
> **(b)** un argumento-puente concreto que se sostiene o no (Camino A), y **(c)**
> una obra literaria singular (la original, `capitulos/`). Ese encuadre es
> defendible; "nueva filosofía" expone el proyecto a ser desarmado. Ojo: la obra
> *original* puede ser más original —como literatura filosófica— que la derivada;
> no dejar que la derivada le robe la energía.

---

## 5. Índice rápido de archivos (para no buscar)

- `ontologia-relacional/00-documento-puente.md` — tesis vertebral (leer primero).
- `ontologia-relacional/HOJA-DE-RUTA.md` — este archivo.
- `extraccion-ideas/indice.md` — 16 unidades de las notas (ontología relacional).
- `extraccion-ideas/indice-obra.md` — 16 unidades de la obra original.
- `extraccion-ideas/unidades/` y `unidades-obra/` — las unidades individuales.
- `extraccion-ideas/notas-crudas/` — las 3 notas fuente.

## 6. Bitácora (añadir una línea por sesión, lo más reciente arriba)

- **2026-07-31** — Añadido el **Camino G** (situarse frente a la literatura) y el
  **reencuadre de la ambición** (síntesis + argumento-puente + obra literaria, no
  "nueva filosofía"), tras una ronda de feedback crítico. El aporte candidato a
  novedad es el §3 (unificar límite metabólico y límite lógico); su validez
  depende del Camino A. Riesgo mayor identificado: la "ilusión de convergencia"
  (infalsabilidad) — antídoto = §7.3 / Camino E.
- **2026-07-31** — Creados el documento-puente y esta hoja de ruta. Extracción
  cerrada (3 notas → 16 unidades; obra original → 16 unidades + 2 facetas
  fundidas). Definido el puente (moneda) y el registro (filosófico riguroso).
