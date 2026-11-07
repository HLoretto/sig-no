# AGENTS.md — Reglas permanentes para agentes

Este archivo instruye a los agentes de inteligencia artificial que trabajan en issues del repositorio `sig-no`. Los agentes son **roles de trabajo**, no personas. Cada integrante del equipo sigue siendo responsable de su fase.

## Reglas (obligatorias)

1. Cada agente trabaja en **un issue a la vez**. Si el encargo no es claro, pregunta en el issue y espera respuesta.
2. Solo cita los **cuatro documentos del equipo**:
   - Diseño de un sistema de información gerencial para NutriOriente Alimentos, C.A.
   - Informe de Ingeniería de Requisitos y Modelado.
   - Plan de Auditoría de Seguridad, Pruebas y Calidad.
   - Procedimiento y cuadro de actividades por fases OpenUP.  
   Si un dato no está en esas fuentes, lo marca como **faltante**.
3. Escribe en la carpeta de la fase e indica el **estado** (`elaborada` o `disenada`) en la primera línea del documento.
4. Abre una solicitud de integración con el código **SIGNO** en el título. **Nunca** integra sus propios cambios en `main`.
5. En los issues diseñados, presenta las cifras del plan de pruebas (tiempos, terminales, pérdida de paquetes) como **umbrales** o como **comportamiento anticipado**, nunca como mediciones ejecutadas.
6. El agente de seguridad entrega la matriz de roles y la lista de controles. **No** describe cómo explotar una vulnerabilidad.
7. El agente documentador mantiene el índice y prepara las listas de verificación de los hitos.

## Agentes y función

| Agente | Función | Issues típicos |
| --- | --- | --- |
| Analista | Metas, FODA y requisitos | 02, 03, 07 |
| Arquitecto | Portafolio, UML, módulos y arquitectura | 05, 09, 11, 13 |
| Datos | Modelo, diccionario y registro de decisión | 10, 24 |
| Calidad | Umbrales, casos de prueba, pH y red | 08, 14, 15, 16 |
| Seguridad | Roles, controles y marco normativo | 17, 21 |
| Continuidad | Oleadas, capacitación y recuperación | 19, 20, 22 |
| Documentador | Índice y revisiones de hito | 01, 04, 06, 12, 18, 23 |

## Definición de terminado

1. El issue tiene fase, estado, fuente, agente y responsable.
2. El documento está en la carpeta correcta.
3. Cada punto del criterio de aceptación se puede verificar.
4. La persona responsable aprobó la solicitud de integración.
5. El estado escrito coincide con la etiqueta del issue (`elaborada` o `disenada`).
6. Si es un issue diseñado, el documento lo declara así en la primera línea.

## Regla de oro

**El agente propone. La persona responsable de la fase decide.**
