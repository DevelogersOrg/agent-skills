---
name: odoo-implementation-methodology
description: "Orientar, analizar y revisar proyectos de implementación de Odoo según el manual oficial Implementation Methodology: fases, roles, decisiones, riesgos, adopción, desarrollos específicos, datos, go-live y ventas. Usar cuando se necesite localizar una regla o caso metodológico, evaluar una situación de proyecto o preparar una recomendación trazable. No usar como documentación funcional/técnica de una app ni como autorización para operar un Odoo real."
---

# Odoo Implementation Methodology

Usa esta skill como mapa hacia el manual oficial, no como sustituto del manual. Responde con la menor porción de contexto suficiente y conserva trazabilidad a capítulo y página.

## Fuente y vigencia

La fuente canónica es el PDF público de Odoo `Implementation-methodology-July-2024-v06.pdf` (82 páginas). El nombre publicado indica julio de 2024/v06, pero el PDF declara noviembre de 2020 y sus metadatos internos también son de noviembre de 2020. No presentes 2024 como fecha de redacción ni asumas que el contenido está alineado automáticamente con una versión concreta de Odoo.

Antes de afirmar que es la edición más reciente, o cuando la vigencia sea material, consulta [references/source-registry.md](references/source-registry.md) y verifica el enlace oficial. Las charlas oficiales posteriores pueden confirmar continuidad o aportar contexto, pero no reemplazan el texto del manual.

## Enrutamiento

1. Clasifica la consulta: principios/éxito, roles, fase, reto, decisión sobre personalización o datos, caso práctico, medición, preventa/ventas, o vigencia de fuentes.
2. Lee sólo la referencia necesaria:
   - Para estructura, fases, roles, criterios y páginas: [references/manual-map.md](references/manual-map.md).
   - Para reconocer un caso y aplicar la secuencia de decisión: [references/scenario-router.md](references/scenario-router.md).
   - Para versión, URLs, autoridad y límites de evidencia: [references/source-registry.md](references/source-registry.md).
3. Si el usuario pide detalle, consulta la página o sección indicada del manual oficial. No inventes contenido ausente del mapa ni atribuyas al manual una práctica derivada.
4. Separa la respuesta en: `Hechos del manual`, `Aplicación al caso`, `Supuestos o límites` y `Verificación propuesta`, ajustando el nivel de detalle a la pregunta.

## Reglas de interpretación

- Trata “a tiempo y dentro del presupuesto” como la definición central de éxito del manual, junto con la incorporación efectiva de usuarios; no la conviertas en permiso para omitir requisitos legales, seguridad, controles contables o continuidad operativa.
- Interpreta `keep it simple`, estándar primero, ciclos cortos y despliegue por fases como heurísticas fuertes. Exige una justificación de negocio y riesgo para apartarse de ellas.
- Distingue `qué/por qué` (necesidad y objetivo del cliente) de `cómo` (solución recomendada por el Project Leader mediante Odoo). La decisión debe seguir siendo desafiable y validable; no confundas liderazgo metodológico con autoridad contractual ilimitada.
- Antes de recomendar desarrollo específico, evalúa en este orden: necesidad para operar, retorno frente al coste total, magnitud del beneficio, alternativa estándar o cambio de proceso, y posibilidad de diferirlo hasta después del go-live.
- No copies automáticamente cifras históricas del manual a una estimación actual. Las proporciones de fases, costes de deuda técnica, tasas de éxito y hitos de carrera son referencias del documento, no benchmarks universales actuales.
- No confundas `ROI Analysis`, `GAP Analysis` y `Kick-Off`: el manual usa terminología parcialmente inconsistente. Explica el término encontrado y la fase funcional a la que se refiere.
- Señala cualquier tensión entre la metodología y el contexto: regulación, localización fiscal, auditoría, migración obligatoria, volumen, criticidad, integración, accesibilidad, privacidad o gobierno corporativo.
- No consultes ni modifiques un Odoo real por usar esta skill. Cualquier acceso a datos, configuración o producción requiere la autorización y el procedimiento del proyecto.

## Forma de la respuesta

Para una consulta puntual, incluye la sección/página y una recomendación breve. Para una evaluación de proyecto, produce una matriz con situación, criterio del manual, evidencia disponible, brecha, riesgo, recomendación y prueba de aceptación. Cuando una conclusión sea una adaptación profesional y no una afirmación textual del manual, márcala como `inferencia` o `recomendación`.
