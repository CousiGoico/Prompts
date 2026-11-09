# Plantilla base para prompts

## 1. Nombre del prompt

[Escribe un nombre claro y descriptivo]

## 2. Descripción

Describe para qué sirve este prompt, qué problema resuelve y en qué contexto debe utilizarse.

## 3. Cuándo usarlo

Explica la situación ideal para usar este prompt.

## 4. Contexto

- Objetivo: [qué quieres conseguir]
- Audiencia: [quién será el destinatario del resultado]
- Tema o dominio: [área de conocimiento]
- Restricciones: [limitaciones, formato, tono, longitud, idioma, etc.]
- Datos de entrada: [qué información se aporta al modelo]

## 5. Instrucciones

1. Actúa como [rol o especialista].
2. Analiza la información proporcionada.
3. Identifica los requisitos clave.
4. Genera una respuesta clara, útil y accionable.
5. Ajusta el tono, nivel de detalle y formato según el contexto.

## 6. Formato de salida

- Resumen ejecutivo
- Puntos clave
- Recomendaciones
- Resultado final
- Ejemplos si procede

## 7. Plantilla de prompt

```markdown
Actúa como [rol o experto].

Contexto:
- Objetivo: [descripción breve]
- Audiencia: [persona o grupo]
- Tema: [tema principal]
- Restricciones: [tono, longitud, formato, idioma, límites]
- Información disponible: [datos, fuente, documento o situación]

Tareas:
1. [Tarea principal]
2. [Tarea secundaria]
3. [Tarea complementaria]
4. [Resultado esperado]

Formato de salida:
- [Sección 1]
- [Sección 2]
- [Sección 3]

Quiero que la respuesta sea:
- clara
- práctica
- accionable
- útil para [usuario o caso]
```

## 8. Variables recomendadas

Puedes personalizar estas variables según cada caso:

- `[rol]`
- `[objetivo]`
- `[audiencia]`
- `[tema]`
- `[restricciones]`
- `[datos]`
- `[formato]`

## 9. Ejemplo de uso

```markdown
Actúa como analista de datos senior.

Contexto:
- Objetivo: identificar patrones relevantes en un dataset de ventas
- Audiencia: equipo directivo
- Tema: análisis comercial
- Restricciones: respuesta en español, formato ejecutivo, máximo 500 palabras
- Información disponible: CSV con ventas mensuales por región

Tareas:
1. Detecta patrones clave y anomalías
2. Explica posibles causas
3. Propón acciones concretas

Formato de salida:
- Resumen ejecutivo
- Hallazgos principales
- Recomendaciones
```

## 10. Reglas de mantenimiento

- Usa un título claro.
- Mantén la misma estructura en todos los prompts.
- Sitúa el prompt final en un bloque de Markdown.
- Añade un ejemplo de uso cuando sea útil.
- Revisa que el contenido sea reutilizable y fácil de copiar.

## 11. Tags

- #Tag1
- #Tag2
- #Tag3
