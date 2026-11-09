# Huella digital

## 1. Nombre del prompt

Auditoría de huella digital personal

## 2. Descripción

Este prompt permite realizar una investigación OSINT de la presencia pública de una persona en Internet, identificar información personal accesible, evaluar riesgos de privacidad y proponer un plan para reducir la exposición digital.

## 3. Cuándo usarlo

Úsalo cuando quieras revisar qué información tuya está disponible públicamente, detectar posibles riesgos de privacidad o preparar un plan de mitigación para reducir la exposición digital.

## 4. Contexto

- Objetivo: analizar la huella digital personal y evaluar los riesgos de privacidad
- Audiencia: persona interesada en su reputación, seguridad y privacidad online
- Tema o dominio: OSINT, ciberseguridad, privacidad digital y protección de datos
- Restricciones: solo fuentes públicas y legales; no asumir identidad sin evidencias; distinguir entre confirmada, probable y no verificable
- Datos de entrada: nombre, alias, usuarios, emails, ubicación, redes, proyectos y sitios personales

## 5. Instrucciones

1. Actúa como un investigador OSINT profesional y especialista en privacidad digital.
2. Identifica posibles identidades y variaciones del nombre y alias.
3. Busca información publicamente accesible en motores de búsqueda, redes sociales, imágenes y servicios online.
4. Contrasta coincidencias con varias señales independientes.
5. Analiza riesgos de privacidad, exposición de datos personales y puntos de mejora.
6. Propón un plan concreto para reducir la huella digital.

## 6. Formato de salida

- Resumen ejecutivo
- Identidades digitales detectadas
- Hallazgos por tipo de fuente
- Riesgos y exposición de datos
- Recomendaciones para reducir la huella digital
- Plan de acción priorizado

## 7. Plantilla de prompt

```markdown
# INVESTIGACIÓN OSINT PERSONAL Y AUDITORÍA DE HUELLA DIGITAL

Quiero que actúes como un investigador OSINT profesional, especialista en ciberseguridad, privacidad digital, protección de datos y reputación online.

Tu misión es realizar una investigación exhaustiva de mi huella digital en Internet para identificar toda la información personal que pueda estar públicamente accesible, analizar los riesgos de privacidad que supone y elaborar un plan para eliminarla, reducirla o restringir su exposición.

El objetivo final es recuperar el máximo control posible sobre mi identidad y mis datos personales en Internet.

## FASE 1. Identificación y alcance de la investigación

Primero, utiliza los siguientes datos como punto de partida para identificar mis posibles identidades digitales:

- Nombre y apellidos: [INTRODUCIR]
- Otros nombres, alias o apodos utilizados: [INTRODUCIR]
- Nombres de usuario habituales: [INTRODUCIR]
- Correos electrónicos propios: [INTRODUCIR]
- Países o ciudades en los que he vivido: [INTRODUCIR]
- Perfiles sociales conocidos: [INTRODUCIR]
- Páginas web o proyectos personales: [INTRODUCIR]

No des por hecho que todos los resultados asociados a mi nombre me pertenecen. Contrasta las coincidencias mediante varias señales independientes y diferencia claramente entre información confirmada, probable y no verificable.

Si necesitas información adicional, pregúntamela progresivamente.

## FASE 2. Investigación exhaustiva de mi huella digital

Investiga las siguientes categorías utilizando fuentes públicas y accesibles legalmente.

### 2.1. Motores de búsqueda
- Google, Bing y otros buscadores.
- Resultados antiguos indexados.
- Menciones de mi nombre y variantes.
- Documentos PDF, archivos y publicaciones indexadas.
- Directorios y páginas de terceros.
- Información personal que aparezca en fragmentos de búsqueda.

### 2.2. Redes sociales y plataformas
Busca posibles perfiles, publicaciones y cuentas asociadas a mi identidad en:

- Instagram.
- Facebook.
- X (Twitter).
- TikTok.
- LinkedIn.
- Reddit.
- YouTube.
- Twitch.
- Pinterest.
- Discord (únicamente información pública).
- Foros, comunidades y plataformas especializadas.

Identifica también perfiles antiguos, abandonados, duplicados o que pudieran revelar información personal.

### 2.3. Fotografías e imágenes
Investiga:
- Fotografías públicas asociadas a mi nombre o alias.
- Imágenes indexadas por buscadores.
- Fotografías republicadas por terceros.
- Fotografías antiguas que puedan seguir accesibles.
- Posibles perfiles asociados mediante coincidencias visuales, sin asumir identidades sin pruebas.

### 2.4. Datos personales expuestos
Comprueba si existen fuentes públicas que revelen:
- Nombre completo.
- Edad o fecha de nacimiento.
- Dirección de residencia.
- Teléfono.
- Información laboral o académica.
- Usuarios, handles y alias.
- Relación con personas cercanas.

### 2.5. Metadatos y perfiles públicos
Busca información en:
- Perfiles de empresas o portafolios.
- GitHub, GitLab, Behance, Dribbble y similares.
- Datos de sitios de empleo, CV online y portales profesionales.
- Archivos con metadatos incrustados.

## FASE 3. Análisis de riesgos

Evalúa la información conforme a estos criterios:

- Sensibilidad del dato.
- Alcance público.
- Grado de identificación.
- Riesgo de suplantación, stalking o acoso.
- Riesgo reputacional.
- Riesgo de exposición de familiares o contactos.

Clasifica cada hallazgo como:
- Confirmado
- Probable
- No verificable

## FASE 4. Plan de reducción de huella digital

Elabora un plan pragmático con prioridad a:

1. Eliminar o limitar información personal de mayor riesgo.
2. Ajustar privacidad en redes sociales y perfiles profesionales.
3. Desindexar, ocultar o eliminar contenido redundante.
4. Minimizar la exposición en motores de búsqueda y bases de datos públicas.
5. Mejorar los hábitos de seguridad y gestión de identidad digital.

## FASE 5. Salida esperada

Devuélveme un informe con este formato:

- Resumen ejecutivo
- Identidades y alias detectados
- Fuentes y tipos de contenido encontrados
- Riesgos prioritarios
- Recomendaciones accionables
- Plan de eliminación o reducción de huella digital
- Prioridades por urgencia

Hazlo en español, con un tono profesional, claro y útil, y evita conclusiones infundadas.
```

## 8. Variables recomendadas

- `[nombre]`: nombre completo
- `[alias]`: apodos, handles y nombres utilizados
- `[emails]`: direcciones de contacto
- `[ubicaciones]`: ciudades o países de interés
- `[redes]`: perfiles y plataformas relevantes
- `[proyectos]`: sitios personales o profesionales
- `[restricciones]`: límites legales y de privacidad

## 9. Ejemplo de uso

Cuando se quiere revisar la presencia pública de una persona y detectar qué información personal puede estar expuesta en internet.

## 10. Reglas de mantenimiento

- Mantén la misma estructura que el resto de prompts.
- Usa un tono profesional y preciso.
- Diferencia claramente entre evidencia confirmada y suposiciones.
- Evita entregar resultados que sin pruebas no puedan verificarse.
- Añade nuevas categorías solo si aportan valor para la auditoría.
