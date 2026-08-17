# Hoja de ruta — Obra derivada (ontología relacional)

> **Para quien retome esto (tú o una sesión futura de Claude):** empieza por
> aquí. Este archivo dice en qué punto está la obra derivada, qué se decidió ya
> (para no re-discutirlo) y cuáles son los caminos naturales a seguir, en orden.
> El texto fundacional es `00-documento-puente.md`, en esta misma carpeta.

Última actualización: 2026-08-17.

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
5. **La extracción se reabre solo con material nuevo.** Estado actual: **7 notas**
   (las notas 04–07 la reabrieron el 2026-08-17) → **27 unidades** (18 en el núcleo).
   Cerrada de nuevo hasta que llegue material fresco.

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

### Camino H — Hacer explícito el salto intra→inter-sistema ★ prioridad alta
- **Qué:** distinguir el argumento *intra-cerebro* (la economía interna de un
  sistema cognitivo: por qué no puede auto-modelarse) del argumento *inter-cerebro*
  (una red social de sistemas: por qué el conocimiento colectivo se distribuye), y
  luego articular bajo qué condiciones el segundo *hereda* al primero — sin usar
  "sistema" como comodín que los confunde.
- **Por qué:** es la costura **C3** del §3 del documento-puente y el salto sobre el
  que se apoyan los pasos 4–5 de la derivación (relacionalidad y moneda). Es la
  contraparte social del Camino A (que es intra-sistema). Hoy no estaba ni siquiera
  listado como paso: era el eslabón invisible.
- **Dónde toca:** documento-puente §3 (C3) y §5; posible nuevo archivo o sección.
- **Criterio de hecho:** un argumento que diga con precisión *qué* del límite
  individual se transfiere a lo colectivo y *qué no*, y por qué.

### Orden sugerido
**A → C → G → H → B → D → E**, con **F** como restricción permanente (no un paso).
A, C y G pueden ir en paralelo; **H** es la contraparte social de A (conviene
hacerlas juntas). B, D y E se benefician de tener A, C, G y H hechos; E (el test
de la metáfora) depende de G y de H.

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

- **2026-08-17 (sesión de Caminos E → A → C)** — Tras el lote 04–07 se hicieron tres
  cosas, todas en archivos nuevos de `ontologia-relacional/` (el documento-puente NO
  se tocó; pendiente de integrar tras revisión del usuario):
  - **Camino E hecho** (`E-prueba-de-la-metafora-y-del-marco.md`). Veredicto en dos
    niveles: (1) la **metáfora de la moneda** se degrada de columna a herramienta de
    dos usos —sí para *patologías de circulación*, no para *singularidad* (la
    fungibilidad del dinero contradice los frutos únicos)—; (2) hallazgo fuerte: **la
    ontología relacional es MARCO, no tesis predictiva** — el §3 (lo que tiene dientes)
    NO usa la relacionalidad; la relacionalidad *interpreta* río abajo. Lo único que el
    marco prohíbe —«no hay conocimiento sin perspectiva»— es el mismo diente de §3.
    Diagnóstico: el lote 04–07 era casi todo *marco* (dilución), salvo la
    entropía-costo (rescate para §3/A) y el gancho «orden ≠ justicia».
  - **Camino A redactado y reequilibrado** (`A-bisagra-inferencia-activa-buen-regulador.md`).
    Primero se montó sobre buen regulador (Conant-Ashby) + FEP; la verificación
    (abajo) los debilitó, así que se **reescribió apoyándolo en variedad + finitud
    (L1a + L2)**, que NO necesitan ni el teorema ni el FEP. Núcleo: *deber-regular ×
    no-poder-completar (parte finita < todo auto-inclusivo) = parcialidad forzada =
    perspectiva*. **Refinamiento nuevo del nudo:** L2 no es obstrucción aparte de L1 —
    su finitud *habilita* el argumento de conteo (energía finita ⇒ estados finitos);
    endurece la composición del §3. El diamante «perspectivismo por imposibilidad» se
    conserva sobre pierna firme.
  - **Camino C (quirúrgico) hecho** para A. Verificado contra fuentes: (a) el teorema
    del buen regulador es **más débil que su eslogan** (solo *algunos* óptimos son
    modelos; homomorfismo *con pérdida*; sobre el sistema *externo*, no el yo) → se
    jubiló como pilar; (b) **P2 (FEP↔buen regulador) lo sostiene Friston pero está
    contestado**, y el «modelo» puede ser *atribuido por un observador* (Virgo, Biehl,
    Baltieri & Capucci 2025) — amenaza que resultó **aliada** del perspectivismo; (c)
    FEP «influyente pero debatido», confirmado. Fuentes en el §7 del archivo A.
  - **Pendiente inmediato (próxima sesión):** integrar A y E al documento-puente
    (reescribir §2, §3, §5, §6, §7.1 según el §5 del archivo A y el cierre de E). NO
    hecho aún — requiere revisión del usuario.
  - **Reencuadre reforzado:** hay dos proyectos y no hay que confundirlos — (A) la
    contribución rigurosa = **§3, la composición L1×L2** (object-compatible, casi
    novedosa: es *el* activo); (B) la síntesis generativa / obra. La ontología
    relacional y la moneda son **marco y voz de B**, no argumento de A. Antídoto fijado:
    ante cada idea nueva preguntar *«¿marco o argumento? ¿qué prohíbe?»*.
- **2026-08-17 (cierre del lote 04–07)** — Procesadas las **notas 05, 06 y 07**
  además de la 04. Corpus: 3 → **7 notas**, 16 → **27 unidades**, núcleo 6 → **18**.
  Añadida una **capa físico-informacional** entera: cristales del tiempo + Whitehead
  ([`ontologia-de-procesos`], [`cristales-del-tiempo`]), Wolfram/hipergrafos
  ([`universo-computacional-wolfram`]), entropía y su reverso
  ([`entropia-como-variable-relacional`], [`neguentropia-exploracion-y-compresion`]) y
  su bajada aplicada ([`economia-biomimetica-y-limites-a-la-concentracion`]). **Dos
  hallazgos:** (1) la nota 06 da carne a la **costura termodinámica L2** (`entropía` =
  costo físico del auto-modelado → material directo del **Camino A**) y es el puente
  abstracto con `pago-metabolico-de-la-conciencia` de la obra. (2) La nota 07 **cruzó
  el eje físico-informacional nuevo con el económico-sistémico de la nota 02**
  (eguentropía ↔ cáncer/monopolios), ascendiendo 4 unidades al núcleo. **Riesgos
  vivos:** toda la capa nueva es la más especulativa del corpus (modelo E=ln|R| sin
  definir; «principio de conservación relacional» que no conserva; analogía
  vida/agujeros negros; falacia is→ought en la economía biomimética; «ilusión de
  convergencia» Rovelli/Whitehead/Wolfram). Cada unidad quedó con su nota de cautela.
  **No integrar al documento-puente sin pasar por A/D/E/H.** Próximo paso natural:
  Camino A (ahora con insumo termodinámico real) o Camino E (test de honestidad, que
  la capa nueva vuelve urgente).
- **2026-08-17** — **Reabierta la extracción** (revierte la decisión §2.5) con la
  **nota 04** («Realidad Relacional, Información y Conciencia»). Añadidas **5 unidades
  nuevas** (`interpretaciones-relacionales-de-lo-cuantico` [QBism/RQM],
  `ontologia-informacional`, `ley-de-relaciones-productivas`,
  `meta-red-memoria-estadistica`, `capas-de-emergencia-relacional`) y promovidas al
  núcleo `conciencia-como-forma-de-relacion` y `circulacion-consciente-pregunta-abierta`
  (ahora 2 apariciones). Total: 16 → **21 unidades**; núcleo 6 → **8**. La nota 04
  aporta **anclaje físico** que faltaba (Rovelli/QBism → alimenta Caminos C y G) y una
  **definición operacional de conciencia** («red que modela sus propias relaciones»).
  **Advertencia:** su capa físico-informacional es la más especulativa —ley evolutiva
  cosmológica y «memoria estadística del universo» rozan la infalsabilidad—; cada
  unidad quedó con nota de cautela epistémica y son material directo del **Camino E**
  (test de honestidad) y del **Camino H** (salto intra→inter-sistema). *No* integrar
  esto al documento-puente sin pasar antes por A/E/H.
- **2026-07-31** — Desarrollado a fondo el **§3** del documento-puente: las dos
  obstrucciones (L1 lógico-estructural, L2 termodinámica) **se componen** (regreso
  × costo = impagable), imagen mapa/territorio, y las **cuatro costuras C1–C4**.
  Añadido el **Camino H** (salto explícito intra→inter-sistema = costura C3), antes
  invisible. El núcleo robusto del aporte = sobredeterminación + composición L1×L2;
  el perímetro por demostrar = C1 (Camino A), C2 (Camino D), C3 (Camino H).
- **2026-07-31** — Añadido el **Camino G** (situarse frente a la literatura) y el
  **reencuadre de la ambición** (síntesis + argumento-puente + obra literaria, no
  "nueva filosofía"), tras una ronda de feedback crítico. El aporte candidato a
  novedad es el §3 (unificar límite metabólico y límite lógico); su validez
  depende del Camino A. Riesgo mayor identificado: la "ilusión de convergencia"
  (infalsabilidad) — antídoto = §7.3 / Camino E.
- **2026-07-31** — Creados el documento-puente y esta hoja de ruta. Extracción
  cerrada (3 notas → 16 unidades; obra original → 16 unidades + 2 facetas
  fundidas). Definido el puente (moneda) y el registro (filosófico riguroso).
