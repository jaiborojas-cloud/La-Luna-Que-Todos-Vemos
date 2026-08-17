# Camino A — Por qué el auto-modelo completo es imposible (y la perspectiva, obligada)

> **Qué salda esto.** La costura **C1** del §3 del documento-puente. La versión previa
> de este archivo apoyaba el argumento en el teorema del buen regulador (Conant-Ashby)
> y el FEP (Friston). La **verificación del 2026-08-17 (§7)** mostró que esas dos
> piezas son más débiles y más contestadas de lo que se cita popularmente. Esta
> reescritura **reequilibra**: el peso recae ahora en una **ruta robusta de variedad y
> finitud** que no necesita ni el buen regulador ni el FEP; esas dos pasan a
> **corroboración externa**, citadas con su disputa. El diamante — «no hay conocimiento
> sin perspectiva, por imposibilidad» — se conserva, sobre una pierna más firme.
>
> Estatuto: síntesis argumentada. Núcleo casi-demostrable + corroboración contestada,
> deslindados.

---

## 0. El resultado, en una frase

> Un sistema finito que persiste **debe** regular aquello de lo que depende
> (necesidad); si eso lo incluye a él, un modelo **completo** de sí mismo exigiría que
> una parte propia tuviera tanta variedad como el todo que la contiene —imposible por
> conteo (imposibilidad)—. Lo único que puede sostener es un modelo **con pérdida**: y
> un modelo con pérdida *es* una compresión con punto de vista. **La perspectiva no es
> una elección ni una carencia: es el residuo obligado de existir siendo finito y
> parte de lo que debes conocer.**

---

## 1. La columna robusta (L1a + L2): variedad y finitud

Tres pasos, ninguno depende del FEP ni de la lectura fuerte del buen regulador.

**Paso 1 — Persistir exige regular (variedad requerida, Ashby 1956).** Para mantener
sus variables esenciales dentro de rango frente a las perturbaciones de aquello de lo
que depende, un sistema necesita al menos tanta variedad como la que debe absorber:
`V(regulador) ≥ V(perturbación)` para anular la variación. Solo la variedad absorbe
variedad. *Estatuto: demostrable (teoría de control).*

**Paso 2 — El caso auto-inclusivo (dónde muerde).** En un sistema que actúa y planifica,
las causas que debe regular **lo incluyen a él**: sus propios estados y acciones son
parte de aquello que debe anticipar. Un modelo *completo* de ese todo tendría que ser
una parte propia (el modelo vive dentro del sistema) con variedad ≥ la del todo
—incluida la del propio modelo—. *Estatuto: tesis motivada; acota el alcance a
sistemas agentes auto-modeladores (cerebros, colectivos que se representan). No es
para «cualquier sistema»: eso es honestidad, no debilidad.*

**Paso 3 — La imposibilidad, por conteo, y por qué necesita L2.** Para un sistema
**finito**, una parte propia tiene estrictamente menos estados distinguibles que el
todo (casillero): no hay representación *fiel/inyectiva* del todo en la parte. Luego el
auto-modelo completo es imposible. *Estatuto: demostrable para el caso finito.*

> **La finitud no es gratis — la paga L2.** Un sistema *infinito* podría poner una
> parte propia en biyección con el todo (Dedekind), y el conteo no mordería. ¿Qué
> garantiza que un cerebro sea finito? El **presupuesto de energía libre finito (L2)**:
> energía finita ⇒ número finito de estados físicamente distinguibles ⇒ el casillero
> aplica. Por eso **L2 no es una obstrucción *aparte* de L1: es su premisa.** Sin
> termodinámica, la obstrucción de conteo ni siquiera arranca. Esto **endurece** la
> composición del §3 más de lo que el documento reclamaba (era «estructura × precio»;
> es, además, «precio *habilita* estructura»).

---

## 2. El motor (el payoff filosófico)

La fuerza no está en la imposibilidad sola —eso sería «otra prueba de incompletud»—
sino en la **tensión entre deber y no poder**:

- **Debe** regular lo que lo sostiene, o deja de existir (Paso 1). Modelar/regular no
  es opcional: es la condición de persistir.
- **No puede** completar el modelo del todo auto-inclusivo (Paso 3).

**Deber regular + no poder completar = parcialidad forzada.** Y aquí converge un
hallazgo de la verificación: el único «modelo» que el teorema del buen regulador
garantiza es un **homomorfismo con pérdida** (§7). Es decir: tanto por el lado de la
variedad (finitud) como por el lado del teorema, lo forzado es lo mismo — un modelo
**con pérdida, parcial**. Y un modelo parcial de aquello que te incluye *es una
compresión con punto de vista*: una **perspectiva**.

> No hay «vista desde ningún lugar» no por decreto filosófico (Kant, Nagel,
> perspectivismo), sino porque **el único auto-modelo que un ser finito y auto-incluido
> puede sostenerse es parcial.** El perspectivismo, aquí, se *deriva* de una
> imposibilidad; no se postula. Ese es el diferencial frente a los vecinos (Metzinger
> aporta el sin-yo-completo pero no la finitud termodinámica; Luhmann aporta el punto
> ciego pero como propiedad de la observación, no derivado de recursos). → Camino G.

De aquí, la derivación del §3 (parcialidad → complementariedad → distribución →
relacionalidad) **arranca con su primer paso ganado**, no supuesto.

---

## 3. La corroboración externa (buen regulador + FEP) — citada con su disputa

Estas piezas **ya no cargan peso**; corroboran y dan la instanciación biológica. Se
presentan con su estatuto real (verificado en §7), sin inflarlas.

**Teorema del buen regulador (Conant & Ashby, 1970).** Enunciado popular: «todo buen
regulador de un sistema debe ser un modelo de ese sistema». *Uso honesto:* la prueba
solo garantiza que *algunos* reguladores óptimos son modelos, y que el modelo es un
**homomorfismo con pérdida** del sistema **externo** regulado. Lo aprovechamos **solo**
en esa forma débil —que la regulación óptima corresponde a un modelo *parcial*—, que
resulta *convergente* con nuestro Paso 3. **No** lo usamos para el salto al
auto-modelado: ese salto lo hace nuestro Paso 2, no el teorema.

**Principio de energía libre / inferencia activa (Friston, 2010).** Da la instanciación
física: el cerebro persiste minimizando energía libre variacional (cota superior de la
sorpresa), y Friston mismo enlaza esto con el buen regulador y la variedad requerida.
*Uso honesto:* es «influyente pero debatido» en su alcance (Bruineberg et al.; Colombo
& Wright). Lo tomamos como **modelo biológico plausible de L2** (auto-sostenerse cuesta
y ese costo es finito), no como ley que funde el argumento.

**El giro que era amenaza y es aliado.** La reformulación de Virgo, Biehl, Baltieri &
Capucci (2025) sostiene que «tener un modelo» **no es propiedad intrínseca del sistema,
sino algo que un observador le atribuye**. Lejos de hundirnos, esto *refuerza* el
diamante: no hay vista desde ningún lugar **ni siquiera** sobre la pregunta «¿tiene este
sistema un modelo?». El perspectivismo alcanza a la meta-descripción.

---

## 4. Libro de cuentas (qué es qué)

| Pieza | Estatuto | Carga |
|---|---|---|
| Variedad requerida (Ashby) | **Demostrable** | Portante |
| L1a: parte propia finita no modela fielmente el todo | **Demostrable** (finito) | **Portante** |
| L2 licencia la finitud que L1a necesita | **Tesis-refinamiento** (candidata fuerte) | Portante |
| Paso 2: el agente debe regular un todo que lo incluye | **Tesis** motivada (acota alcance) | Portante |
| Motor: deber-regular × no-poder-completar → perspectiva | **Síntesis** | **El corazón** |
| Buen regulador = modelo (forma fuerte del eslogan) | **Débil / no sostenida por su prueba** | *Descartada como pilar* |
| Buen regulador ⇒ modelo *con pérdida* del sistema externo | **Demostrable** (forma débil) | Corroboración |
| P2: FEP instancia optimalidad de Conant-Ashby | **Tesis de Friston, contestada** | Corroboración |
| Modelo como atributo observador-dependiente (2025) | **Resultado publicado** | Aliado del diamante |

**Qué se demostró:** dado que un agente finito deba regular un todo que lo incluye, el
auto-modelo *completo* es imposible y el sostenible es *parcial* → perspectiva. Esto no
depende de las piezas que la verificación debilitó.

**Qué queda como tesis:** el Paso 2 (que el agente deba regular un todo auto-inclusivo)
y el refinamiento L2⇒finitud. Son los flancos honestos, mucho más defendibles que los
anteriores (P2/P4).

**Qué lo falsaría:** exhibir un agente finito que se auto-modele **completa y
fielmente** (contra el conteo — muy difícil), o desacoplar la persistencia de toda
regulación de lo que incluye al agente (contra el Paso 1–2).

---

## 5. Qué cambia en el documento-puente

- **§2:** presentar la **ruta de variedad+finitud (L1a)** como la forma *más robusta*
  del límite estructural — no depende de Gödel, del regreso ni del FEP. Rebajar el
  teorema del buen regulador a su forma débil verificada (homomorfismo con pérdida,
  sobre el sistema externo).
- **§3 / C1:** sustituir «promesa, no teorema» por el **motor de §2 de este archivo**
  (deber × no-poder → perspectiva) y por el **refinamiento L2⇒L1a** (endurece la
  composición). C1 pasa de invisible-débil a *acotada, verificada y explícita*.
- **§6 (tabla de estatutos):** corregir la fila del buen regulador (hoy dice
  «Demostrable»; es demostrable solo en forma débil) y añadir el estatuto contestado
  del FEP↔buen regulador.
- **§7.1 (agenda):** lo que resta ya no es «todo C1»; es concretamente **el Paso 2**
  (justificar la auto-inclusión regulatoria) y **verificar el refinamiento L2⇒finitud**.

---

## 6. (reservado)

---

## 7. Verificación contra fuentes (Camino C, hecha el 2026-08-17)

Cita confirmada: **Conant, R. C. & Ashby, W. R. (1970).** "Every good regulator of a
system must be a model of that system." *International Journal of Systems Science*,
**1**(2), 89–97. DOI 10.1080/00207727008920220.

**Hallazgo 1 — El teorema es más débil que su eslogan.**
- La prueba **no sostiene plenamente el título**: muestra que *algunos* reguladores
  óptimos son modelos, no que *todo* buen regulador lo sea (crítica de Wentworth).
- La correspondencia es un **homomorfismo con pérdida**, no isomorfismo → el modelo es
  intrínsecamente **parcial** (*a favor nuestro*).
- Es sobre el **sistema externo regulado**, no sobre el yo → extender a auto-modelado no
  es corolario del teorema. Por eso **movimos el peso a L1a** y jubilamos la ruta del
  regreso (L1b) como pilar.

**Hallazgo 2 — P2 (FEP↔buen regulador): de Friston, pero contestado y con giro.**
- *A favor:* Friston enlaza explícitamente FEP con el teorema y la variedad requerida
  («un organismo se vuelve modelo de su entorno al minimizar energía libre… consistente
  con el teorema del buen regulador»). No es invención nuestra.
- *El giro:* Virgo, Biehl, Baltieri & Capucci (2025) — el «modelo» es **atribuido por un
  observador, no intrínseco** («models are not a mere property of the system but are
  imposed on it from outside»; «the model might be trivial»). Socava la lectura de
  modelo interno fuerte, pero es **aliado** del perspectivismo (§3).

**Hallazgo 3 — El FEP es "influyente pero debatido", confirmado.** Bruineberg et al.,
"The Emperor's New Markov Blankets"; Colombo & Wright; Biehl et al. (corrigendum). Tema
FEP↔modelo interno **vivo en 2025** (Phil. Trans. R. Soc. A, "A 'good' regulator may
provide a world model"; "A Bayesian Interpretation of the Internal Model Principle").

**Fuentes:**
- Good regulator theorem — https://en.wikipedia.org/wiki/Good_regulator_theorem
- Virgo, Biehl, Baltieri & Capucci (2025), *A good regulator theorem for embodied
  agents* — https://arxiv.org/abs/2508.06326
- "Fixing the Good Regulator Theorem" (Wentworth) —
  https://www.alignmentforum.org/posts/Dx9LoqsEh3gHNJMDk/fixing-the-good-regulator-theorem
- Baez, "The Internal Model Principle" —
  https://johncarlosbaez.wordpress.com/2016/01/27/the-good-regulator-theorem/
- "Modelling ourselves…" (Synthese) —
  https://link.springer.com/article/10.1007/s11229-021-03140-5
- Phil. Trans. R. Soc. A (2025), *A 'good' regulator may provide a world model* —
  https://doi.org/10.1098/rsta.2025.0007
