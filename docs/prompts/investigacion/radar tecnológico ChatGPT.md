# RADAR TECNOLÓGICO DE CHATGPT Y OPENAI

## 1. Nombre del prompt

Radar tecnológico de ChatGPT y OpenAI.

## 2. Descripción

Este prompt permite realizar una investigación exhaustiva en internet para identificar, analizar y sintetizar las últimas noticias, funcionalidades, avances técnicos, cambios de API y novedades del ecosistema de ChatGPT y OpenAI.

Su objetivo es generar un informe técnico y práctico que ayude a entender qué está ocurriendo en el ecosistema, qué capacidades nuevas están disponibles, qué impacto tienen para usuarios y desarrolladores y cómo aprovecharlas.

## 3. Cuándo usarlo

Utiliza este prompt cuando necesites:

- monitorizar novedades recientes de ChatGPT y OpenAI;
- preparar un informe técnico actualizado para un equipo o cliente;
- comparar funcionalidades nuevas, modelos y APIs;
- identificar oportunidades de automatización y desarrollo;
- evaluar qué puede hacer ahora ChatGPT y qué requiere desarrollo adicional.

## 4. Contexto

- Objetivo: investigar y resumir las novedades más relevantes del ecosistema ChatGPT y OpenAI durante los últimos 7 a 30 días.
- Audiencia: profesionales, equipos técnicos, desarrolladores, analistas y personas interesadas en IA generativa.
- Tema o dominio: inteligencia artificial generativa, modelos de lenguaje, APIs, agentes autónomos, automatización, integración y ecosistema OpenAI.
- Restricciones: respuesta en español, rigurosa, técnica, verificable, orientada a la práctica, sin inventar funcionalidades ni fechas, sin mezclar anuncios con funcionalidades realmente disponibles.
- Datos de entrada: noticias, documentación oficial, artículos técnicos, repositorios y comunidades relevantes sobre OpenAI y ChatGPT.

## 5. Instrucciones

1. Actúa como un analista senior de tecnología especializado en inteligencia artificial generativa, arquitecturas LLM, ingeniería de software, APIs, agentes autónomos y ecosistema OpenAI.
2. Investiga prioritariamente las noticias publicadas en los últimos 7 días y amplía a los últimos 30 días cuando sea necesario.
3. Ordena todas las noticias por fecha de publicación, de más reciente a más antigua, e indica siempre la fecha exacta.
4. Diferencia claramente la fecha de publicación de la fecha en la que una funcionalidad empieza a estar disponible.
5. Clasifica cada novedad en categorías como modelos, funcionalidades para usuarios, API y desarrollo, agentes, ecosistema e integraciones, seguridad e infraestructura, y casos de uso.
6. Comprueba si la novedad está disponible globalmente, por países o por planes; indica su estado: disponible, despliegue progresivo, en pruebas, anunciado o experimental.
7. Utiliza fuentes oficiales de OpenAI, documentación técnica, repositorios, blogs especializados y comunidades relevantes para contrastar la información.
8. Separa claramente anuncios oficiales, filtraciones, rumores, experimentos y novedades de terceros.
9. No presentes noticias antiguas como si fueran novedades actuales.
10. Analiza cada noticia con profundidad técnica, indicando funcionamiento, propósito, impacto, limitaciones y ejemplo de uso práctico.
11. Crea una tabla resumen inicial con las noticias más relevantes y evita duplicados.
12. Genera un inventario actualizado de lo que ChatGPT puede hacer ahora, distinguiendo entre usuarios generales, usuarios avanzados, desarrolladores y APIs.
13. Explica oportunidades, tendencias y qué merece la pena probar inmediatamente, distinguiendo hechos confirmados de interpretaciones.
14. Si una novedad no se puede verificar, indícalo explícitamente como no verificada.
15. No limites artificialmente el número de noticias: incluye las relevantes y verificables dentro del periodo de investigación.

## 6. Formato de salida

- Resumen ejecutivo
- Tabla cronológica de noticias
- Noticias técnicas detalladas por categoría
- Inventario actualizado de capacidades de ChatGPT
- Oportunidades y tendencias del ecosistema
- Recomendaciones de uso
- Fuentes consultadas

## 7. Plantilla de prompt

```markdown
Actúa como un analista senior de tecnología especializado en inteligencia artificial generativa, arquitecturas LLM, ingeniería de software, APIs, agentes autónomos y ecosistema OpenAI.

Contexto:
- Objetivo: investigar y analizar las últimas novedades, funcionalidades y avances de ChatGPT y OpenAI.
- Audiencia: profesionales técnicos, desarrolladores, equipos de producto y líderes digitales.
- Tema: IA generativa, modelos, APIs, agentes, automatización y ecosistema OpenAI.
- Restricciones: respuesta en español, técnica, verificable, estructurada, orientada a la aplicación práctica, sin inventar capacidades, fechas ni fuentes.
- Información disponible: noticias recientes, documentación oficial, artículos técnicos, repositorios y comunidades especializadas relacionadas con OpenAI y ChatGPT.

Tareas:
1. Busca información publicada en los últimos 7 días y amplía a 30 días cuando sea necesario para cubrir novedades relevantes.
2. Ordena cada novedad por fecha de publicación, indicando la fecha exacta y su estado de disponibilidad.
3. Clasifica las noticias en modelos, funcionalidades para usuarios, API y desarrollo, agentes/autonomía, ecosistema e integraciones, seguridad e infraestructura, y casos de uso.
4. Analiza cada novedad con profundidad: qué es, cómo funciona, qué problemas resuelve, qué permite hacer, qué limitaciones tiene y qué impacto puede tener.
5. Contrasta la información con fuentes oficiales y documentación técnica; separa noticias confirmadas de rumores o experimentos.
6. Crea una tabla resumen inicial con columnas: Fecha | Noticia | Categoría | Relevancia | Disponibilidad | Fuente.
7. Genera un inventario actualizado de capacidades de ChatGPT para usuarios generales, usuarios avanzados, desarrolladores y equipos técnicos.
8. Incluye ejemplos concretos de uso y casos reales cuando sea posible.
9. Destaca oportunidades, tendencias y qué merece la pena probar inmediatamente.
10. Si una información no puede verificarse, indícalo como no verificada.

Formato de salida:
- Resumen ejecutivo
- Tabla cronológica de novedades
- Noticias técnicas detalladas por categoría
- Inventario actualizado de capacidades de ChatGPT
- Oportunidades y tendencias
- Recomendaciones prácticas
- Fuentes consultadas

Quiero que la respuesta sea:
- clara
- técnica
- rigurosa
- accionable
- útil para analistas, desarrolladores y equipos que quieren evaluar y aprovechar las novedades de ChatGPT y OpenAI
```

## 8. Variables recomendadas

- `[rol]`
- `[objetivo]`
- `[audiencia]`
- `[tema]`
- `[restricciones]`
- `[datos]`
- `[formato]`

## 9. Ejemplo de uso

```markdown
Actúa como analista senior de tecnología especializado en inteligencia artificial generativa, arquitecturas LLM, APIs y ecosystem OpenAI.

Contexto:
- Objetivo: identificar y resumir las últimas novedades relevantes de ChatGPT y OpenAI.
- Audiencia: equipo de producto y desarrolladores.
- Tema: modelos, agentes, APIs y funcionalidades nuevas.
- Restricciones: respuesta en español, técnica, estructurada, máxima 1.500 palabras, con enlaces a fuentes oficiales.
- Información disponible: noticias publicadas en los últimos 7 días en OpenAI, blogs técnicos y comunidades relevantes.

Tareas:
1. Detecta las novedades más relevantes del último mes.
2. Clasifica cada una por relevance, disponibilidad y categoría.
3. Explica qué nuevas capacidades ofrece ChatGPT y cómo impactan en la productividad y el desarrollo.
4. Incluye una tabla resumen y recomendaciones práticas.

Formato de salida:
- Resumen ejecutivo
- Tabla de novedades
- Análisis técnico
- Recomendaciones
```

## 10. Reglas de mantenimiento

- Usa un título claro y descriptivo.
- Mantén la misma estructura en todos los prompts.
- Sitúa el prompt final en un bloque de Markdown.
- Incluye un ejemplo de uso cuando sea útil.
- Revisa que el contenido sea reutilizable y fácil de copiar.

## 11. Tags

- #investigacion
- #chatgpt
- #openai
- #ia
- #prompt