# Norberta Chatelli — Cartoon Engine

Motor incremental de animación basado en HTML, SVG y JavaScript, sin dependencias.

## Ver ejemplos

| Ejemplo | Ejecutar | Código |
|---|---|---|
| Tres rostros en distintas orientaciones discutiendo | [▶ Ver animación](https://htmlpreview.github.io/?https://github.com/norbymezz/norbertachatelli/blob/main/examples/three-face-angles-arguing.html) | [Ver código](examples/three-face-angles-arguing.html) |
| Dos rostros de perfil discutiendo por turnos | [▶ Ver animación](https://htmlpreview.github.io/?https://github.com/norbymezz/norbertachatelli/blob/main/examples/two-profiles-arguing.html) | [Ver código](examples/two-profiles-arguing.html) |
| Turnos alternados con dos rostros blancos y dos negros | [▶ Ver animación](https://htmlpreview.github.io/?https://github.com/norbymezz/norbertachatelli/blob/main/examples/two-fixed-knights-perspective.html) | [Ver código](examples/two-fixed-knights-perspective.html) |
| Persona recorriendo una cuadrícula 3×3 | [▶ Ver animación](https://htmlpreview.github.io/?https://github.com/norbymezz/norbertachatelli/blob/main/examples/perspective-grid-route.html) | [Ver código](examples/perspective-grid-route.html) |
| Dos personas dándose la mano | [▶ Ver animación](https://htmlpreview.github.io/?https://github.com/norbymezz/norbertachatelli/blob/main/examples/two-people-handshake.html) | [Ver código](examples/two-people-handshake.html) |

> Cada ejemplo nuevo debe agregarse a esta tabla con un vínculo ejecutable y otro al código fuente.

## Regla de trabajo

Antes de modificar el motor:

1. Leer [CONTEXT.md](CONTEXT.md).
2. Leer [engine/base.html](engine/base.html).
3. Modificar el archivo vivo de forma incremental.
4. Entregar una versión funcional.
5. Registrar en [docs/decisions.md](docs/decisions.md) sólo las decisiones ya firmes.
6. Agregar cada salida funcional a la tabla **Ver ejemplos** de este README.

No reconstruir el motor desde cero ni anticipar un catálogo completo de capacidades.

## Estructura

- `engine/base.html`: archivo vivo y ejecutable del motor.
- `examples/`: ejemplos funcionales derivados del motor.
- `CONTEXT.md`: reglas esenciales para continuar el trabajo.
- `docs/decisions.md`: decisiones estables, no ideas sueltas.

## Uso

Usar los vínculos **Ver animación** para ejecutar los ejemplos desde el navegador. Los vínculos **Ver código** abren los archivos correspondientes en GitHub.
