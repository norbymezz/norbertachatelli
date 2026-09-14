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

## 2026-09-14 — Escenas pregrabadas como guías

- Una escena terminada sigue siendo un HTML/SVG autosuficiente; Uizador no la genera de nuevo ni necesita convertirla en video.
- Los ejemplos destinados a guía pueden aceptar `?embed=1` para mostrar solamente el escenario y `?autoplay=0` para quedar detenidos en el primer estado.
- El mensaje `{"type":"uizador-guide","action":"start|restart|pause|reset"}` controla el clock cuando la escena está embebida.
- `examples/friends-for-record-front-back.html` es el primer caso conectado mediante este contrato.
