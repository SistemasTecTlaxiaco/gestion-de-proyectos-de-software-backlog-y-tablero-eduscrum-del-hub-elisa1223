# Mapa conceptual — Problemáticas, necesidades e historias de usuario

## Objetivo

Relacionar las problemáticas candidatas identificadas en la región Mixteca con las necesidades detectadas, las historias de usuario y el proceso utilizado para seleccionar la problemática que dará origen al proyecto.

## Relación general

```mermaid
flowchart TD

A[Problemáticas candidatas de la región Mixteca]

A --> B[Gestión y seguimiento de residuos]
A --> C[Servicio de agua]
A --> D[Preservación y transmisión de la lengua materna]

B --> B1[Consultar reportes de residuos]
B --> B2[Dar seguimiento a reportes de residuos]

C --> C1[Registrar incidencia del servicio de agua]
C --> C2[Consultar seguimiento de una incidencia de agua]

D --> D1[Consultar palabras y expresiones]
D --> D2[Escuchar pronunciaciones]

B1 --> HU1[HU-01]
B2 --> HU2[HU-02]

C1 --> HU3[HU-03]
C2 --> HU4[HU-04]

D1 --> HU5[HU-05]
D2 --> HU6[HU-06]

HU1 --> F1[Análisis y auditoría]
HU2 --> F1
HU3 --> F1
HU4 --> F1
HU5 --> F1
HU6 --> F1

F1 --> F2[Comparación de alternativas]
F2 --> F3[Selección de problemática]
F3 --> F4[Definición del proyecto]

F3 --> E[PROB-03 Lengua materna — ELEGIDA]
