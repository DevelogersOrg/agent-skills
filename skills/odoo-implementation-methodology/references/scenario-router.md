# Router de situaciones y casos

## Uso

Identifica la decisión real, localiza el precedente más cercano, compara sus factores con el contexto actual, consulta las páginas indicadas y propone una acción verificable. Un caso del manual orienta; no sustituye el juicio profesional.

## Matriz de enrutamiento

| Señal | Preguntas diagnósticas | Páginas | Resultado esperado |
|---|---|---:|---|
| Estado del proyecto | ¿Usuarios operan? ¿fecha/presupuesto? ¿alcance imprescindible? | 8–13, 23, 31–38 | Estado contra éxito, fase y riesgos. |
| Plazo imposible | ¿Qué fecha es externa? ¿qué puede quedar estándar o diferirse? ¿quién decide? | 27–30 | Reencuadre transparente, alcance mínimo y condiciones. |
| Nadie decide | ¿SPoC tiene tiempo y autoridad? ¿cada decisión vuelve al comité? | 18–20 | Corregir gobierno o SPoC. |
| Demasiados participantes | ¿Quién expresa necesidades y quién decide? | 15–20, 44, 63 | Reducir ciclo decisor; expertos puntuales. |
| Desarrollo específico | ¿Es operativo? ¿ROI total? ¿volumen? ¿alternativa? ¿puede esperar? | 32–33, 45–55, 61–62 | Estándar, workaround, intercambio de alcance, backlog o especificación. |
| Módulo comunitario | ¿Quién mantiene, prueba y actualiza? ¿sigue siendo necesario? | 51, 53–55 | Evaluar deuda total, no sólo instalación. |
| Historial completo | ¿Obligación? ¿frecuencia de consulta? ¿archivo accesible? ¿valor futuro? | 31–32, 46–48 | Maestros/saldos y archivo; excepción justificada. |
| Datos sucios bloquean salida | ¿Son operables? ¿qué riesgo legal/contable existe? ¿pueden limpiarse después? | 31–32 | Controles y plan posterior sin buscar perfección. |
| Falta documentación | ¿Existe documentación estándar? ¿qué procedimiento es propio? ¿SPoC lo domina? | 33, 48 | Cliente redacta procedimiento; Project Leader valida. |
| Usuarios resistentes | ¿Conocen beneficios? ¿han probado? ¿sponsor y SPoC apoyan? | 41–43, 56–58 | Demo, práctica, involucramiento y respaldo. |
| Go-live en duda | ¿Flujos críticos probados? ¿usuarios entrenados? ¿plan de respuesta? | 34–35, 63–64 | Readiness por riesgo; no retraso reflejo. |
| Petición nueva en ciclo | ¿Afecta fecha/presupuesto? ¿qué se elimina a cambio? | 33, 62 | Diferir o intercambiar alcance. |
| Segunda fase | ¿Qué demuestra el uso real? ¿impacto frente a facilidad? | 36–38 | Repriorización y matriz de oportunidades. |
| Especificación | ¿Necesidad y razón? ¿solución Odoo? ¿restricciones y pruebas? | 32, 45–46 | Especificación breve, visual y verificable. |
| Proyecto grande o político | ¿Hace falta Project Director/steering? ¿cómo preservar ciclos cortos? | 16–19, 24–26, 74 | Gobierno ejecutivo sin dispersar decisión diaria. |
| Preventa | ¿Quién decide? ¿cómo compra? ¿vio demo? ¿ROI? ¿estándar? | 70–75 | Venta simple, transparente y por fases. |
| Actualidad | ¿Cambió el PDF, el producto o la plantilla? | `source-registry.md` | Afirmación fechada y trazable. |

## Casos como precedentes

| Caso | Páginas | Principio transferible | No generalizar |
|---|---:|---|---|
| Frédéric desafía solicitudes | 12 | Fricción temprana puede proteger valor de largo plazo. | Que satisfacción no importe nunca. |
| Empresa pública, 3000+ usuarios | 17 | SPoC, demo semanal, estándar y decisores reducen latencia. | Eliminar todo gobierno en proyectos regulados. |
| Dos manufactureras / SPoC | 20 | Autoridad y confianza importan tanto como disponibilidad. | Que el CEO nunca pueda ser SPoC. |
| Electronics123 | 28 | Condiciones explícitas y alcance estándar hicieron viable un caso extremo. | Nueve días como benchmark. |
| Implementación fallida vs. exitosa | 30 | Fijar desde Kick-Off un umbral claro para desarrollo. | Que capacidad de pago justifique personalización. |
| Casual Cushions | 43 | Preguntas y pruebas pueden preparar mejor que aceptación pasiva. | Que resistencia siempre sea positiva. |
| Ibbeo | 46–48 | Maestros y saldos pueden bastar para iniciar; historial puede diferirse. | Ignorar obligaciones fiscales o auditoría. |
| Magento | 50 | Mantener temporalmente el método previo y validar integración tras go-live. | Que una integración nunca sea crítica. |
| Reporte Excel/KPI | 50–51 | Hallar el objetivo real puede eliminar el artefacto pedido. | Que los informes existentes carezcan de valor. |
| Automatización de tareas | 51–52 | Contrastar volumen ahorrado con coste total. | Decidir por una estimación aislada. |
| Calendario | 52 | Explorar servicios existentes antes de crear un conector. | Introducir terceros sin evaluar seguridad. |
| Bioulvax | 52–53 | Volver al estándar mejoró adopción tras personalizar para una perspectiva. | Que estándar siempre cubra el negocio. |
| Mecatis | 53–55 | Revalidar cada módulo al migrar; varios eran reemplazables. | Retirar módulos sin inventario, pruebas y reversión. |
| Minerex | 56–57 | Sin aceptación local, patrocinio remoto no basta. | Que viajar sea siempre la solución. |
| Quiz 1: mejora semanal | 61 | Diferir mejora no esencial protege el primer go-live. | Que cuatro horas semanales nunca justifiquen desarrollo. |
| Quiz 2: doble aprobación | 61–62 | Una política puede ser más adaptable que código en empresa pequeña. | Sustituir controles regulatorios por correo. |
| Quiz 3: objeción del CFO | 62 | Volver al alcance y diferir o intercambiar prioridad. | Desatender un riesgo financiero nuevo. |
| Quiz 4: reunión amplia | 63 | Uno o dos Project Leaders suelen bastar; expertos según necesidad. | Reducir representación exigida por gobierno. |
| Quiz 5: temor al go-live | 63–64 | Transparencia y respuesta rápida generan confianza. | Salir sin umbral de operabilidad. |

## Secuencia de decisión

1. ¿Cuál es el objetivo, la necesidad y la evidencia del problema?
2. ¿Qué mínimo permite operar legalmente, con seguridad y control?
3. ¿Cuál es la solución estándar más simple y qué cambio de proceso requiere?
4. ¿Qué coste total, beneficio, volumen y riesgo tiene apartarse del estándar?
5. ¿Es imprescindible antes del go-live o puede validarse después?
6. ¿Quién decide, quién valida y qué evidencia demostrará que funciona?

## Salida

Usa cuatro bloques: `Hechos del manual`, `Aplicación al caso`, `Supuestos o límites` y `Verificación propuesta`. Cita capítulo/página y marca como inferencia cualquier adaptación no formulada por el manual.
