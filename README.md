# Generador de PTD

Prompt e instrucciones del proyecto **PTD** (Plan de Transformación Digital), migrado desde el proyecto "PTD" de Claude.

## Descripción

Generador de PTD: transforma información de una empresa (documento adjunto o texto) en un Plan de Transformación Digital exhaustivo, presentado en formato JSON puro, siguiendo un esquema estricto (diagnóstico inicial, madurez digital, buyer persona, mapa de empatía, experiencia de cliente, modelo de negocio, KPIs, plan de implantación, etc.).

## Contenido

- [`PROMPT.md`](./PROMPT.md): instrucciones completas del system prompt usado para generar el PTD.
- [`schema.json`](./schema.json): esquema JSON de salida que debe seguir cada PTD generado.

## Uso

Usar el contenido de `PROMPT.md` como system prompt (o instrucciones de proyecto) en el LLM de tu elección, adjuntando el documento o texto de la empresa a analizar donde indica `[INSERTAR DOCUMENTO O TEXTO AQUÍ]`.
