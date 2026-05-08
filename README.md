# Asistente Redactor

Suite de skills de Claude Code para asistir la redacción de contenido. No genera posts completos — interviene en pasos específicos del proceso: titulares, estructuras, reescrituras, párrafos de apertura, etc.

## Filosofía

El asistente actúa como copiloto, no como autor. El redactor mantiene el control creativo; el skill reduce la fricción en los momentos donde más cuesta arrancar o pulir.

## Estructura

```
asistente-redactor/
├── blog/
│   └── SKILL.md          # Skill para contenido de blog
├── BRAND-VOICE.md        # Voz, tono y restricciones editoriales
├── EXAMPLES.md           # Ejemplos de referencia por formato
└── DESIGN.md             # Guía visual/editorial de la marca
```

## Skills disponibles

| Skill | Descripción |
|-------|-------------|
| `blog` | Asiste la redacción de posts: titulares, estructura, aperturas, reescrituras |

## Cómo usar

Cada carpeta contiene un `SKILL.md` que define el comportamiento del skill. Para invocarlo desde Claude Code:

```
/blog
```

## Contexto compartido

Todos los skills leen `BRAND-VOICE.md` y `EXAMPLES.md` para mantener consistencia de voz entre formatos.
