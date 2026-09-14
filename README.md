# Norberta Chatelli — Cartoon Engine

Motor incremental de animación basado en HTML, SVG y JavaScript, sin dependencias.

## Regla de trabajo

Antes de modificar el motor:

1. Leer [CONTEXT.md](CONTEXT.md).
2. Leer [engine/base.html](engine/base.html).
3. Modificar el archivo vivo de forma incremental.
4. Entregar una versión funcional.
5. Registrar en [docs/decisions.md](docs/decisions.md) sólo las decisiones ya firmes.

No reconstruir el motor desde cero ni anticipar un catálogo completo de capacidades.

## Estructura

- `engine/base.html`: archivo vivo y ejecutable del motor.
- `examples/`: ejemplos funcionales derivados del motor.
- `CONTEXT.md`: reglas esenciales para continuar el trabajo.
- `docs/decisions.md`: decisiones estables, no ideas sueltas.

## Uso

Abrir `engine/base.html` o cualquier archivo de `examples/` directamente en un navegador.
