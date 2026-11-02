# Plan Sub-2

App web instalable con el plan de 22 semanas para el 15K MetLife (28 feb 2027) y la Media de Madrid (4 abr 2027).

- Web: https://leeyrees.github.io/plan-sub2/
- Los datos (registros, capturas, ajustes del plan y notas) viven en el repositorio privado `leeyrees/plan-sub2-datos`, que la app lee y escribe con la API de GitHub usando una clave de acceso guardada solo en el móvil. El formato está descrito en el README de ese repositorio.
- `index.html` lleva el plan, los ritmos y toda la app; `sw.js` permite instalarla y abrirla sin conexión; `manifest.webmanifest` e `icon-*.png` son para la pantalla de inicio.
