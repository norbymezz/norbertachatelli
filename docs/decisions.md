# Decisiones firmes

Este archivo registra únicamente decisiones ya adoptadas. Las ideas pendientes deben permanecer fuera de aquí hasta ser confirmadas.

## 2026-09-14 — Base del proyecto

- El motor vive principalmente en un único archivo HTML autosuficiente: `engine/base.html`.
- La representación visual usa HTML, SVG y JavaScript sin dependencias externas.
- El desarrollo es incremental: se modifica el motor existente, no se lo reconstruye para cada pedido.
- Los estados expresivos se describen mediante geometría y parámetros, no mediante objetos semánticos específicos.
- El tiempo se organiza en tres señales: clock físico, pulso derivado y escala lenta.
- Las transiciones son entidades conectables entre señales temporales y parámetros.
- Los ejemplos funcionales se guardan por separado en `examples/`.
