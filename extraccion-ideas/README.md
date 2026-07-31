# Extracción de ideas

Repositorio-herramienta para el proyecto filosófico-literario en curso
(**MENTEMONEDA / La Luna Que Todos Vemos**) y su obra derivada más rigurosa
(**ontología relacional**).

No es una obra en sí: es el andamiaje que alimenta a ambas. Su función es
**extraer las unidades conceptuales** de las notas crudas y **contar su
recurrencia** para distinguir lo que es *núcleo* de lo que es *ocurrencia*.

## Estructura

```
extraccion-ideas/
├── notas-crudas/     Documentos pegados tal cual (chats, borradores, transcripciones)
├── unidades/         Una idea conceptual por archivo .md
└── indice.md         Tabla de todas las unidades: estado + recurrencia
```

## Flujo de trabajo

1. Se pegan documentos en `notas-crudas/` (sin editar, tal cual).
2. Se analiza cada documento y se extraen las **unidades conceptuales distintas**.
3. Si una idea ya existe con otro nombre, **no se duplica**: se agrega la nueva
   aparición a la unidad existente.
4. Se actualiza `indice.md` con estado y conteo de recurrencia.

### Fase actual

Solo **extracción y conteo de recurrencia**. No se propone estructura de libro
ni capítulos todavía.

## Formato de una unidad

Ver `unidades/_PLANTILLA.md`.
