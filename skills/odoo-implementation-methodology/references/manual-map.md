# Mapa del manual oficial

Este mapa permite localizar conocimiento; los detalles y ejemplos completos pertenecen al PDF oficial. Las páginas son las numeradas por el propio documento y coinciden con el PDF.

## Modelo mental central

La metodología optimiza una implementación para incorporar usuarios a una solución operable dentro del plazo y presupuesto. Lo hace reduciendo ciclos de decisión, concentrando responsabilidad, privilegiando estándar y entregas cortas, entrenando temprano al representante del cliente y aplazando lo no imprescindible. El mecanismo no es “cumplir una lista de requisitos”, sino transformar objetivos y necesidades en una solución simple que pueda ponerse en producción y evolucionar después.

Cadena causal del manual:

`objetivos y dolor -> ROI/alcance -> expectativas y roles -> ciclos cortos -> validación/formación -> go-live -> aprendizaje real -> segundo despliegue y oportunidades`

## 1. Introducción y conceptos clave — pp. 5–7

**Preguntas que responde:** propósito de la metodología, responsabilidad principal, simplicidad, personas y control de calidad.

- La implementación se presenta como cambio organizacional, no sólo instalación de software.
- Prioridad del Project Leader: plazo y presupuesto.
- Cliente: define necesidad y razón (`qué/por qué`). Project Leader/producto: propone el modo de resolverla (`cómo`).
- La demanda se desafía comparando beneficio y coste.
- Simplicidad: menos reuniones/papel, menos partes decisoras, mínimo desarrollo y presencialidad sólo cuando aporta a adopción o formación.
- El Project Leader combina resolución de problemas, negocio y producto; los expertos revisan momentos críticos.
- Cláusula de cierre: el sentido común prevalece sobre reglas mecánicas.

## 2. Qué es un proyecto exitoso — pp. 8–13

**Criterio principal:** usuarios incorporados en Odoo a tiempo y dentro del presupuesto.

- El desarrollo específico no define el éxito y puede aumentar plazo, coste, mantenimiento y complejidad.
- La satisfacción durante el proyecto es volátil y depende del rol; sirve como señal de motivación/atención, no como KPI único del Project Leader.
- Vender más servicios antes del go-live puede debilitar confianza y aumentar riesgo. El manual favorece fases: lo imprescindible primero; mejoras después.
- El caso de Frédéric ilustra una tensión aceptada: desafiar solicitudes puede producir fricción de corto plazo y confianza de largo plazo.

**Límite de uso:** no interpretar esta prioridad como autorización para degradar seguridad, cumplimiento, calidad esencial o viabilidad operativa.

## 3. Roles — pp. 14–21

| Rol | Responsabilidad según el manual | Cuándo escalar o comprobar |
|---|---|---|
| Project Leader | Punto principal; integra dirección de proyecto, análisis de negocio y conocimiento de producto; planifica, configura, migra datos, desafía demandas y especifica desarrollos. | Si carece de autoridad, conocimiento, capacidad o independencia para decidir. |
| Project Director | Mantiene informados y comprometidos a decisores; supervisa eficiencia y desbloquea proyectos grandes/políticos. | Proyectos grandes, entorno político, steering committee. |
| App Expert | Revisión externa y profunda de una app/industria, especialmente durante análisis de brechas. | Complejidad alta, duda funcional o desarrollo significativo. |
| Developer | Implementa sólo cuando el negocio requiere desarrollo; añade pruebas automatizadas. | Cuando estándar/Studio/proceso no cubren la necesidad operativa justificada. |
| SPoC | Copropietario del éxito; reúne necesidades, aprende Odoo, decide, coordina agenda, impulsa cambio, entrena y da primer soporte. | Comprobar disponibilidad y autoridad real. |
| Key users | Expertos de dominio; ayudan a definir, probar y validar. | No convertirlos en comité decisor disperso. |
| Sponsor | Objetivos y apoyo ejecutivo; normalmente CEO/CFO. | Falta de respaldo, conflicto de prioridades o resistencia. |
| Steering committee | Prioridades, metodología y seguimiento en proyectos grandes. | Mantenerlo en gobierno/decisión; evitar que sustituya ciclos operativos ágiles. |

En la fila SPoC, comprueba siempre dos condiciones simultáneas: disponibilidad y autoridad real. Sustituye o eleva el problema si cada decisión vuelve al CEO o a un comité.

**Caso, p. 20:** dos implementaciones similares muestran que disponibilidad sin autoridad no basta; la confianza del CEO y la capacidad de decidir aceleraron la segunda etapa.

## 4. Fases de implementación — pp. 22–38

### Distribución orientativa — p. 23

| Fase | Referencia del manual | Objetivo |
|---|---:|---|
| ROI Analysis | 10% | Retorno, fases, presupuesto y factibilidad. |
| Kick-Off | 5% en la tabla; el texto de p. 27 pide al menos 10% | Alinear metodología, expectativas, plan, SPoC y cambio. |
| Implementation | 80% | Ciclos de análisis, configuración/desarrollo, validación y formación. |
| Go-Live | 5%; nota: 10–15% en proyectos grandes | Formación final, transición y corrección rápida. |
| Second deployment | Variable | Repriorizar mejoras tras experiencia real. |

La contradicción 5%/10% del Kick-Off existe en el propio manual; no la ocultes ni “corrijas” sin una fuente posterior.

### ROI Analysis — pp. 24–26

- En proyectos grandes se vende antes del compromiso completo; el manual cita entre 3 y 50 días. En proyectos muy pequeños (menos de cuatro meses), se integra en el Kick-Off.
- Entregables: beneficios/ahorros, presupuesto y plan, mapa necesidad-función, POC de flujos clave y estrategia de cambio.
- Secuencia: objetivos/riesgos con decisores; entrevistas por departamento; documentar retorno y fases; peer review funcional/técnica; cierre y demo.
- Durante entrevistas se observa el proceso actual, documentos, distribución del tiempo, volúmenes y puntos de dolor. La situación actual define el mínimo operable mejor que una lista aspiracional.
- El Project Leader propone una solución preferida y clasifica opcionales; el cliente la desafía.
- Desarrollo: separar lo imprescindible antes de producción de lo diferible al segundo despliegue.

### Project Kick-Off — pp. 27–30

- Generar adhesión, alinear visión/metodología, comprobar factibilidad, finalizar plan, formar al SPoC y activar estrategia de cambio.
- Resolver pronto plazos imposibles, malentendidos y falta de involucramiento.
- Confirmar que las personas correctas disponen de tiempo, conocimiento y autoridad.
- No prometer facilidad, fechas irreales ni funciones complejas. Gestionar expectativas con transparencia.
- Caso Electronics123, p. 28: una fecha extrema sólo fue viable con alcance estándar y decisión concentrada; es un ejemplo, no un plazo objetivo generalizable.
- Caso comparativo, p. 30: aceptar desarrollos por capacidad de pago generó deuda y retraso; establecer desde el inicio el criterio `must-have sin workaround` evitó unas 100 horas estimadas en ese proyecto.

### Implementation — pp. 31–34

- Mantener avance visible con ciclos cortos y entregas semanales; solución configurada y validada progresivamente.
- Project Leader configura Odoo y puede usar Studio sin desarrollo de código.
- SPoC/key users preparan datos; Project Leader o Developer importa según volumen/complejidad.
- No retrasar producción por una limpieza perfecta si el negocio ya operaba con esos datos; planificar limpieza posterior con control de riesgo.
- Importar datos maestros y evitar historial completo salvo justificación.
- Especificación de desarrollo: necesidad, solución funcional, pistas técnicas y escenarios de prueba. Developer implementa y automatiza pruebas; Project Leader prueba integración; SPoC valida negocio.
- SPoC/key users realizan pruebas finales, autorizan go-live, forman usuarios y redactan documentación interna con terminología propia.
- Cambios dentro de un ciclo sólo si no dañan fecha/presupuesto; de lo contrario se difieren o intercambian por otro requisito.
- Presencialidad se usa para desbloqueo, adopción, formación o resistencia, no por defecto.

### Go-Live — pp. 34–35

- Riesgos típicos: flujos no probados y usuarios insuficientemente entrenados.
- Formación práctica: el usuario ejecuta el flujo; no basta una conferencia.
- Revisión adicional de áreas riesgosas porque key users no son testers profesionales.
- Crear impulso, responder rápido y confirmar que se abandonó de hecho el sistema anterior.
- El manual desaconseja retrasar automáticamente: una nueva fecha introduce pérdida de motivación, nuevas solicitudes y repetición de migraciones. Recomienda salir pronto aunque no sea perfecto, siempre que sea operable.

### Second Deployment y Progress Report — pp. 36–38

- Aproximadamente un mes después, revisar el backlog no crítico con evidencia de uso real. El manual afirma como observación típica que parte importante de lo previsto deja de ser necesaria y surgen prioridades nuevas.
- El Progress Report conversa con alta dirección sobre ampliación de valor, no sólo sobre el alcance inicial.
- Matriz de oportunidades: evitar (bajo impacto/difícil), afinar (bajo impacto/fácil), game changers (alto impacto/difícil), quick wins (alto impacto/fácil).
- Registrar oportunidades desde el día uno y presentar pocas observaciones de alto impacto, sustentadas.

## 5. Retos de implementación — pp. 40–59

### Adopción y resistencia — pp. 41–43

- Vender el beneficio del cambio, no negar su coste/riesgo.
- Apoyarse en producto, SPoC/key users y sponsor.
- Involucrar a la persona resistente: preguntas y pruebas pueden producir mayor preparación que aceptación pasiva.
- Caso Casual Cushions, p. 43: la contadora crítica llegó mejor preparada que el equipo inicialmente entusiasta.

### Mantener simplicidad y expectativas — pp. 44–45

- Proponer una solución principal; mostrar alternativas sólo si hace falta.
- Evitar cadenas lentas de validación y aplazamiento de decisiones.
- Usar peer review en decisiones críticas.
- Explicar desde el principio que habrá dificultad e incidentes y qué apoyo se espera del sponsor.

### Buena especificación — pp. 45–46

1. Necesidad y justificación breve (`qué/por qué`).
2. Solución funcional en Odoo, preferiblemente visual (`cómo`).
3. Pistas y restricciones técnicas para el Developer.

Completar con escenarios de prueba, como se indica en p. 32.

### Historial de datos — pp. 46–48

- Preguntar si puede conservarse en el sistema anterior/exportación, frecuencia y propósito de consulta, y valor estratégico futuro.
- Si el cliente no demuestra beneficio suficiente, rechazar o diferir hasta después del go-live.
- Caso Ibbeo: maestros y saldos iniciales permitieron iniciar tres compañías rápidamente; el historial nunca se necesitó en los meses observados. No generalizar esa experiencia a obligaciones fiscales o de auditoría.

### Documentación del cliente — p. 48

- El Project Leader evita repetir documentación estándar; el cliente redacta procedimientos propios porque conoce procesos/terminología y hacerlo valida comprensión.
- Pequeños proyectos pueden apoyarse sólo en documentación/eLearning estándar.

### Solicitudes específicas y desarrollo — pp. 49–55

Árbol de decisión:

1. ¿Es necesario para operar o ya se operaba sin ello?
2. ¿El beneficio compensa construcción, pruebas, retraso, mantenimiento y actualización?
3. ¿El volumen hace significativo el ahorro?
4. ¿Estándar, proceso, política, Studio o integración existente logran el objetivo?
5. Si aún es necesario, ¿debe estar antes de go-live o puede validarse después?

- Caso Magento, p. 50: operar primero con el método existente y decidir la integración con evidencia posterior.
- Caso reporte Excel, pp. 50–51: descubrir el KPI real permitió resolver con datos estándar.
- Caso automatización de tareas, pp. 51–52: comparar horas ahorradas al mes con días de desarrollo y mantenimiento.
- Caso calendario, p. 52: buscar un servicio/intermediario disponible antes de construir un conector.
- Caso Bioulvax, pp. 52–53: volver al estándar mejoró adopción tras personalizaciones guiadas por una sola persona.
- El manual estima la deuda técnica anual en torno al 25% del coste original (aprox. 17% mantenimiento + 8% upgrades); usar sólo como cifra histórica del documento.
- Caso Mecatis, p. 55: 4 módulos propios y 55 comunitarios fueron reemplazados por estándar; el relato reporta migración a Odoo Online sin desarrollo y fuerte reducción de coste.

### Política interna y dinámicas personales — pp. 56–59

- En una crisis, priorizar resolver y avanzar en vez de asignar culpa.
- Caso Minerex, pp. 56–57: imposición desde propietarios remotos sin adhesión del equipo local bloqueó el proyecto; presencia y demostración de beneficio destrabaron la adopción.
- Perfiles orientativos del SPoC:
  - `Do it now`: comprobar aprendizaje, comunicación y entrenamiento; involucrar resistentes.
  - `Do it right`: argumentar por valor y sumar pronto al App Expert.
  - `Do it harmoniously`: reforzar dominio del producto y formación.
  - `Do it together`: fijar qué/por qué del SPoC y cómo del Project Leader para contener cambios continuos.
- La confianza del Project Leader debe apoyarse en razonamiento, producto, revisión y evidencia; la experiencia ajena debe explicarse, no aceptarse como autoridad automática.

## 6. Quiz/casos de decisión — pp. 60–64

- Caso 1: mejora de cuatro horas semanales con dos semanas de desarrollo en proyecto de nueve meses -> backlog posterior al go-live.
- Caso 2: segunda aprobación de gastos en empresa pequeña -> política organizacional antes que desarrollo rígido.
- Caso 3: CFO objeta función no acordada -> volver al análisis/alcance, discutir aparte y diferir o intercambiar prioridad.
- Caso 4: reunión con diez representantes -> uno o dos Project Leaders; sumar expertos sólo por aprendizaje o necesidad concreta.
- Caso 5: CEO exige garantía de go-live sin problemas -> transparencia: habrá incidencias, respuesta rápida y apoyo ejecutivo; retrasar seis meses también aumenta riesgo.

Consulta [scenario-router.md](scenario-router.md) para aplicar estos precedentes sin convertirlos en reglas automáticas.

## 7. Medir progreso — pp. 66–69

El manual propone una autoevaluación lúdica de carrera por puntos: despliegues en tiempo/presupuesto, apps en producción, independencia, certificación, industrias, migraciones y escala de usuarios. Es un instrumento formativo interno e histórico, no un modelo moderno de desempeño ni un SLA. No uses regalos de clientes, velocidad extrema o ahorro bajo presupuesto como KPIs aislados.

## 8. Metodología comercial — pp. 70–75

- Vendedores con dominio de demos, producto, certificación y práctica frecuente.
- Llegar pronto a la demo, guiar el proceso de compra, descubrir necesidades y decisores, reducir complejidad y no sobreprometer.
- Empezar pequeño y crecer después; mantener agenda y requisitos prioritarios; estándar primero; limitar interlocutores directos.
- Pequeñas empresas: producto/demostración desde la primera interacción. Proyectos grandes: primero preferencia por Odoo, luego ROI Analysis, después implementación completa.
- Transparencia en precio, producto, metodología, dificultades y términos como diferenciador.
- La afirmación histórica de precio “7x menor” no debe repetirse como hecho vigente sin verificación comercial actual.

## 9. Referencias y plantillas — pp. 76–80

| Recurso del manual | Uso | Enlace abreviado |
|---|---|---|
| ROI Kick-Off | Entrevista inicial con SPoC y decisores | https://www.odoo.com/r/roi_kickoff |
| ROI Key-user Interview | Personas, procesos, tiempo, volúmenes y dolor | https://www.odoo.com/r/roi_key_user_intw |
| ROI Analysis Tool | Cobertura, retornos e inversiones | https://www.odoo.com/r/roi_analysis |
| ROI Closing / GAP Closing | Presentación a decisores | https://www.odoo.com/r/roi_closing y https://www.odoo.com/r/gap_closing |
| Progress Report | Oportunidades posteriores | https://www.odoo.com/r/progress_report |
| Change Management | Enfoque de adopción | https://www.odoo.com/r/change_management |
| Specification example | Especificación funcional | https://www.odoo.com/r/Spec_example |

Verifica cada redirección antes de depender de una plantilla: los enlaces abreviados pueden cambiar, requerir autenticación o apuntar a una versión posterior.

## Inconsistencias y advertencias internas

- Nombre publicado 2024/v06 vs. contenido y metadatos de 2020.
- Kick-Off: 5% en la tabla de p. 23 vs. “al menos 10%” en p. 27.
- ROI Analysis y GAP Analysis aparecen usados como términos próximos o intercambiables en varios pasajes/plantillas.
- La introducción cita resultados y estadísticas sin metodología de medición visible en el manual.
- Cifras de deuda técnica, precios, tiempos y porcentaje de desarrollos descartados son históricas y contextuales.
- Algunas formulaciones son deliberadamente tajantes; aplícalas junto con obligaciones legales, contractuales y de control del proyecto.
