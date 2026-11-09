# Prompt Library con MkDocs

Este proyecto genera una pequeña biblioteca estática de prompts de IA en formato Markdown.

## Estructura

```text
.
├── mkdocs.yml
├── requirements.txt
├── README.md
└── docs/
    ├── index.md
    └── prompts/
        ├── index.md
        ├── plantilla-prompt.md
        ├── programacion/
        │   ├── README.md
        │   └── analisis-codigo.md
        ├── investigacion/
        │   ├── README.md
        │   └── resumen-investigacion.md
        ├── escritura/
        │   ├── README.md
        │   └── redaccion-contenido.md
        ├── analisis-de-datos/
        │   ├── README.md
        │   └── analisis-dataset.md
        └── productividad/
            ├── README.md
            └── planificacion-diaria.md
```

## Cómo iniciar

1. Instala MkDocs:

```bash
python -m pip install mkdocs
```

2. Ejecuta el sitio localmente:

```bash
python -m mkdocs serve
```

3. Genera la versión estática:

```bash
python -m mkdocs build
```

## Cómo añadir nuevos prompts

Crea un archivo `.md` dentro de la carpeta de la categoría que corresponda, por ejemplo:

```text
docs/prompts/programacion/nuevo-prompt.md
```

Y después enlázalo en el `README.md` de esa categoría o en el índice principal.

La idea es que tú puedas mantener una biblioteca de prompts en Markdown sin tener que administrar una web compleja ni un CMS.
