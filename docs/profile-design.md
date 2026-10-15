# Diseño del perfil de 0ghost8

## Identidad visual

- Fondo de las piezas propias: `#0D1117`.
- Violeta: `#A78BFA` / `#8B5CF6`.
- Cian: `#67E8F9` / `#22D3EE`.
- El banner es un SVG propio, editable en `assets/ghost-banner.svg`.
- El texto principal sigue siendo HTML y Markdown compatibles con GitHub; no requiere JavaScript ni CSS externo.

## Integraciones

- [Skill Icons](https://github.com/tandpfun/skill-icons): tres grupos de tecnologías, con versiones claras y oscuras mediante `picture`. Los nombres también están en el texto alternativo.
- [Shields.io](https://shields.io/): botones de contacto, contexto y herramientas adicionales.
- [Readme Typing SVG](https://github.com/DenverCoder1/readme-typing-svg): una sola animación de texto, con el contenido equivalente en el atributo `alt`. Editar los mensajes en el parámetro `lines`, separados por punto y coma y codificados para URL.
- [Capsule Render](https://github.com/kyechan99/capsule-render): una onda decorativa al final, en los mismos colores.
- [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats): tarjetas SVG guardadas en el repositorio, en lugar de depender del servidor público en cada visita.

## Estadísticas

`.github/workflows/profile-cards.yml` genera las tarjetas una vez al día, a las 03:17 de Guatemala (09:17 UTC), al editar el README y al ejecutarse manualmente desde Actions. Los horarios de GitHub pueden retrasarse.

Usa únicamente el `GITHUB_TOKEN` temporal del workflow y datos públicos de `0ghost8`. No necesita un token personal ni muestra repositorios privados. Las acciones están fijadas a commits concretos.

La generación valida las tarjetas antes de publicarlas. Si la consulta falla, la última versión correcta permanece en el README. Los commits del bot cambian solo las tarjetas y no vuelven a disparar el workflow.

Las tarjetas no miden nivel técnico: muestran actividad pública y distribución de código por lenguaje. La cuenta escolar es independiente.

## Contenido

Conservar el nombre, centro educativo y datos de contacto proporcionados por Pablo. La edad y el estado de las prácticas se actualizan manualmente.

Solo enlazar proyectos cuyos repositorios públicos se hayan verificado. No inventar enlaces para Auto-Solver-GODTS, ElSurco o Mi Perfil Pablo.
