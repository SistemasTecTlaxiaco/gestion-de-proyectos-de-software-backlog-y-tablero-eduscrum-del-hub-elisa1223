# Mapa conceptual — Problemáticas, necesidades e historias de usuario

## Objetivo

Relacionar las problemáticas identificadas en la región Mixteca con las necesidades detectadas, las historias de usuario y las fases propuestas para el análisis del proyecto.

## Relación general

```mermaid
flowchart TD

A[Problemáticas de la región Mixteca]

A --> B[Gestión y seguimiento de residuos]
A --> C[Servicio de agua]
A --> D[Información sobre servicios de salud]

B --> B1[Registrar solicitud]
B --> B2[Consultar estado de solicitud]

C --> C1[Reportar incidencia]
C --> C2[Consultar estado de incidencia]

D --> D1[Consultar servicios de salud]
D --> D2[Consultar campañas y jornadas]

B1 --> HU1[HU-01]
B2 --> HU2[HU-02]

C1 --> HU3[HU-03]
C2 --> HU4[HU-04]

D1 --> HU5[HU-05]
D2 --> HU6[HU-06]

HU1 --> F1[Análisis y validación]
HU2 --> F1
HU3 --> F1
HU4 --> F1
HU5 --> F1
HU6 --> F1

F1 --> F2[Comparación de alternativas]
F2 --> F3[Selección de problemática]
F3 --> F4[Definición del proyecto]
