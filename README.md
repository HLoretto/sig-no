# SIG-NO · Expediente OpenUP

Expediente de gestión del **Sistema de Información Gerencial para Trazabilidad y Calidad (SIG-NO)** de NutriOriente Alimentos, C.A., organizado con el método **OpenUP**.

> Práctica demostrativa de Ingeniería de Software · Maestría en Informática Gerencial · Universidad de Oriente, Núcleo de Monagas · Noviembre 2026.  
> Este repositorio contiene **documentos de diseño y de procedimiento**. No contiene código de aplicación: el ejercicio no desarrolla el sistema.

## Problema del caso

La línea de pulpas y néctares (18.000 L/día, ≈ 68 % de los ingresos) se dirige con información atrasada 12–18 días, diferencia de inventario 12–18 %, merma ≈ 9 % y OTIF 87 % frente a un compromiso de 95 %.

## Metas del diseño 2026–2028

| Meta | Indicador |
| --- | --- |
| Exactitud de inventario ≥ 98 % | Conteo cíclico vs. sistema |
| Merma ≤ 3 % | Kilos perdidos / kilos recibidos |
| OTIF ≥ 95 % | Pedido completo y a tiempo |
| Tablero al día siguiente | Horas hasta el tablero |
| Cero retiros sanitarios | Genealogía del lote + pH + bloqueo |

## Fases OpenUP y responsables

| Fase | Rama | Responsable | Hito |
| --- | --- | --- | --- |
| Inicio | `docs/inicio` | Olvis Leonett | M1 Objetivos del ciclo de vida |
| Elaboración | `docs/elaboracion` | Augusta López | M2 Arquitectura del ciclo de vida · `v1.0-linea-base` |
| Construcción | `docs/construccion` | Oriana Carvajal | M3 Capacidad operativa inicial |
| Transición | `docs/transicion` | José Cedeño | M4 Liberación del producto |
| Gestión | `docs/gestion` | Heickel Loreto | Plantillas, tablero y AGENTS.md |

## Estructura

```text
sig-no/
├── README.md
├── AGENTS.md
├── docs/
│   ├── 01-inicio/
│   ├── 02-elaboracion/
│   ├── 03-construccion/
│   ├── 04-transicion/
│   ├── decisiones/
│   └── gestion/
└── .github/
    ├── ISSUE_TEMPLATE/actividad-openup.md
    └── PULL_REQUEST_TEMPLATE.md
```

## Issues

Son **24 issues** (SIGNO-01 a SIGNO-24): 19 actividades OpenUP, 4 revisiones de hito y 1 registro de decisión (SIGNO-24).

- **Elaboradas (Inicio y Elaboración):** artefactos ya existentes en los documentos del equipo → columna **Terminado**.
- **Diseñadas (Construcción y Transición):** se demuestran con su diseño → recorren el tablero.

## Tablero

Columnas: **Por hacer** → **En agente** → **En revisión humana** → **Terminado**.

Regla: el agente propone; la persona responsable de la fase decide.

## Documentos base del equipo

1. Diseño de un sistema de información gerencial para NutriOriente Alimentos, C.A.
2. Informe de Ingeniería de Requisitos y Modelado.
3. Plan de Auditoría de Seguridad, Pruebas y Calidad.
4. Procedimiento y cuadro de actividades por fases OpenUP.

## Equipo

Olvis Leonett · Augusta López · Oriana Carvajal · José Cedeño · Heickel Loreto · Douglas Rico
