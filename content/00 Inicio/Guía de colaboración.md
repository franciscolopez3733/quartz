# Guía de colaboración

## Cómo contribuir

1. Lee [[Akasa-Puspa]] y los criterios editoriales.
2. Elige una nota en gris `[[Nombre]]` que aún no exista.
3. Crea la nota en su carpeta correspondiente (02 Personajes, 03 Lugares, etc.) usando la plantilla de `90 Plantillas/`.
4. Escribe lo mínimo viable: 2 líneas + Apariciones. No hace falta completarla entera.

## Licencia

Todo el contenido de la enciclopedia se publica bajo **CC BY-SA 4.0** salvo las obras originales de Aguilera & Redal, que mantienen su copyright.

## Flujo

```
LIBRO
│
▼
RESUMEN DETALLADO
│
├── [[Personaje]]
├── [[Planeta]]
├── [[Organización]]
├── [[Nave]]
├── [[Tecnología]]
└── [[Acontecimiento]]
│
▼
ENTRADAS ENCICLOPÉDICAS
│
▼
CONEXIONES ENTRE ELLAS
│
▼
ENCICLOPEDIA
```

## Publicación web

Este vault está preparado para Quartz (Hugo). Para publicar:

1. Clonar repo
2. `npx quartz build`
3. `npx quartz sync`

Ver README.md en la raíz.
