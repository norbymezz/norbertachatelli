# Contexto del motor

> No reconstruir el motor desde cero. Leer primero `engine/base.html` y modificarlo incrementalmente. No anticipar catálogos de capacidades. Cuando una idea pueda implementarse, devolver una versión funcional.

## Principios

- El motor se construye por crecimiento incremental.
- Los personajes y objetos se representan mediante elementos geométricos SVG.
- Las conexiones entre elementos determinan relaciones espaciales y movimiento.
- Cada capacidad nueva debe integrarse con los elementos y parámetros existentes siempre que sea posible.
- Los ejemplos son archivos funcionales que muestran usos concretos del motor.

## Expresividad

> Traducir indicaciones humanas a geometría y parámetros de elementos existentes antes de crear conceptos semánticos nuevos. “Enojo”, “desafiante”, etc. no son objetos del motor; son configuraciones de elementos y conexiones.

## Tiempo y transiciones

> El motor dispone de un clock físico, un pulso derivado/configurable y una escala temporal más lenta. Las transiciones se pueden conectar a uno o varios parámetros y pueden aplicarse con ganancia, inversión u otras relaciones.

- `physical`: tiempo físico continuo entregado por el navegador.
- `pulse`: señal periódica derivada del tiempo físico.
- `slow`: escala temporal configurable más lenta.
- Una transición es una entidad conectable: toma una fuente temporal, aplica una relación y escribe uno o varios parámetros.
- La relación mínima admite ganancia, inversión mediante ganancia negativa y desplazamiento.
