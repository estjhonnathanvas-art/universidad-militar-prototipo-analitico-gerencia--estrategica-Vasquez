# Tablero de Priorización de Hipótesis

## Estructura de la tabla

| # | Columna | Descripción / Instrucción |
|---|---------|--------------------------|
| 1 | **Causa** | ¿Qué crees que está pasando "detrás" del síntoma? Debe sonar a mecanismo, no a queja. |
| 2 | **Fase DT origen (E/D/I)** | ¿De qué momento de Design Thinking salió? |
| 3 | **Insight de empatía** | Una observación/cita corta que te inspiró la causa. |
| 4 | **Supuesto central** | ¿Qué crees que une la causa con el resultado? Es la "apuesta". |
| 5 | **Pregunta analítica** | Forma neutra y medible de la causa. Debe admitir "Sí/No" o "Mayor/Menor". |
| 6 | **Variables (nombres exactos)** | Columnas que usarás tal cual aparecen en la base (no inventes nombres). |
| 7 | **Tipo (Outcome / Explic / Control / Segmento)** | Etiqueta cada variable: 1. Outcome: lo que quieres explicar (ej. recompra_30d). 2. Explic (explicativa): lo que crees que causa (ej. comentario_malestar). 3. Control: cosas que pueden distorsionar (ej. canal). 4. Segmento: variable para cortar resultados (ej. canal, zona). |
| 8 | **Cálculo / Transformación** | Operaciones necesarias antes de la métrica final. |
| 9 | **Métrica (nombre + fórmula)** | Nombre corto + cómo se calcula. |
| 10 | **Periodo / Segmento** | Rango temporal y cortes. |
| 11 | **Patrón esperado (si cierta)** | La condición numérica que esperas ver si tu causa es real. |
| 12 | **Condición refutación** | El rango / comparación que tiraría tu hipótesis. Debe ser diferente (no repetir con "no"). |
| 13 | **Valor esperado para usuario/ciudadano** | Beneficio concreto si confirmas la hipótesis (en lenguaje humano). Clavo: debería sonar a mejora perceptible, no a KPI interno. |
| 14 | **Riesgo si falsa** | Qué perderías si sigues insistiendo en esta causa equivocada. Esto ayuda a priorizar falsar rápido. |
| 15 | **Acción si confirma** | Movimiento específico inmediato (no "optimizar estrategia"). Debe ser ejecutable en la organización. |
| 16 | **Acción si refuta** | Ruta alternativa (no repetir la de confirmar). |
| 17 | **Experimento analítico mínimo (query + visual 1 línea)** | Qué harás para probarla en pequeño. |
| 18 | **Estado (V/A/R)** | Semáforo: V (Verde) = todos los campos listos (se puede correr hoy). A (Amarillo) = falta 1 cosa (umbral, nombre exacto o acción). R (Rojo) = falta variable clave o patrón; no avanzar. |

---

## Registro 1

| Columna | Valor |
|---------|-------|
| **Causa** | Limitación SECOP II / SIIF Nación. |
| **Fase DT origen (E/D/I)** | Definir |
| **Insight de empatía** | Los sistemas de información no se conectan entre sí y SECOP no tiene estandarización en su cargue de información. |
| **Supuesto central** | Si habilitamos un canal de consolidación digital de datos integrado para el ciclo contractual y de adquisiciones, entonces disminuye el número de horas semanales que el analista dedica a la validación manual de registros. |
| **Pregunta analítica** | ¿El uso de un canal de consolidación integrado genera una variación a la baja en el tiempo de procesamiento y validación de registros contractuales por parte del analista? |
| **Variables (nombres exactos)** | 1. ID de la necesidad · 2. Objeto · 3. Modalidad · 4. Fecha de inicio · 5. Fecha Fin · 6. Valor estimado · 7. Clasificación del gasto · 8. ¿Requiere contrato? · 9. Valor VF si aplica · 10. Valor total de la necesidad · 11. Dependencia · 12. Proyecto de inversión (si aplica) · 13. Actividad de la cadena de valor · 14. Fuente de recurso · 15. Clasificación en el catálogo presupuestal · 16. Rubro presupuestal · 17. Tipo de Recurso · 18. Código de recurso · 19. Sub unidad ejecutora · 20. Destinación de gasto · 21. Id proceso · 22. Nombre del proceso · 23. Id contrato · 24. Número del contrato · 25. Tipo de contrato · 26. CDP · 27. Fecha de expedición del CDP · 28. Valor CDP Actual · 29. Valor CDP disponible · 30. RP · 31. Fecha de Expedición del RP · 32. Valor del RP Actual · 33. Valor del RP disponible · 34. Id tercero · 35. Nombre del tercero · 36. Id de la obligación |
| **Tipo (Outcome / Explic / Control / Segmento)** | 1-CONTROL · 2-CONTROL · 3-SEGMENTO · 4-CONTROL · 5-CONTROL · 6-CONTROL · 7-SEGMENTO · 8-CONTROL · 9-CONTROL · 10-CONTROL · 11-SEGMENTO · 12-CONTROL · 13-CONTROL · 14-SEGMENTO · 15-CONTROL · 16-CONTROL · 17-CONTROL · 18-CONTROL · 19-SEGMENTO · 20-CONTROL · 21-CONTROL · 22-CONTROL · 23-CONTROL · 24-CONTROL · 25-SEGMENTO · 26-CONTROL · 27-CONTROL · 28-CONTROL · 29-OUTCOME · 30-CONTROL · 31-CONTROL · 32-CONTROL · 33-OUTCOME · 34-CONTROL · 35-CONTROL · 36-CONTROL |
| **Cálculo / Transformación** | *(pendiente)* |
| **Métrica (nombre + fórmula)** | **Tasa de Reducción del Tiempo Operativo (TRTO)** = Horas semanales de validación manual histórica − Horas semanales con canal integrado |
| **Periodo / Segmento** | Semanal |
| **Patrón esperado (si cierta)** | Reducción mínima del 25% en el tiempo invertido durante el primer mes de uso (es decir, bajar a un máximo de 30 horas semanales de carga operativa). |
| **Condición refutación** | Si tras implementar la herramienta la reducción de horas no llega ni al 5% o, por el contrario, el tiempo de procesamiento aumenta debido a fricciones del sistema, la hipótesis se declara refutada y la idea de negocio se descarta automáticamente. |
| **Valor esperado para usuario/ciudadano** | *(pendiente)* |
| **Riesgo si falsa** | *(pendiente)* |
| **Acción si confirma** | *(pendiente)* |
| **Acción si refuta** | *(pendiente)* |
| **Experimento analítico mínimo (query + visual 1 línea)** | *(pendiente)* |
| **Estado (V/A/R)** | *(pendiente)* |
