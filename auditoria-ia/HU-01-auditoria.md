# Auditoría IA — HU-01

## 1. Historia original

**Como ciudadano de Tlaxiaco, quiero registrar una solicitud de recolección de residuos indicando la ubicación y una descripción del problema, para que la autoridad correspondiente pueda conocer y dar seguimiento a la solicitud.**

## 2. Prompt utilizado

Se utilizó el siguiente prompt:

> Actúa como auditor de historias de usuario para un proyecto de software. Analiza la siguiente historia utilizando los criterios Como/Quiero/Para, rol real, claridad, alcance y criterios de aceptación verificables. Identifica ambigüedades, información faltante y posibles problemas de alcance. No propongas tecnología específica a menos que sea necesario. Después proporciona recomendaciones concretas para mejorar la historia.

Historia:

> Como ciudadano de Tlaxiaco, quiero registrar una solicitud de recolección de residuos indicando la ubicación y una descripción del problema, para que la autoridad correspondiente pueda conocer y dar seguimiento a la solicitud.

## 3. Hallazgos de la auditoría

La revisión identificó los siguientes aspectos:

1. La historia tiene correctamente la estructura Como/Quiero/Para.
2. El rol de ciudadano es identificable.
3. La acción principal está delimitada al registro de una solicitud.
4. La ubicación y descripción son datos necesarios para el reporte.
5. Se recomienda establecer con mayor precisión qué ocurre después del registro.
6. Los criterios de aceptación deben indicar resultados que puedan comprobarse.

## 4. Decisiones del equipo

### Observaciones aceptadas

Se acepta mejorar los criterios de aceptación para que puedan comprobarse mediante pruebas.

También se acepta aclarar que después del registro debe generarse un identificador de solicitud y una confirmación.

### Observaciones rechazadas

No se considera necesario agregar la asignación automática de personal como parte de esta historia.

**Justificación:** dicha función aumentaría el alcance y corresponde a una historia diferente relacionada con la gestión interna de las solicitudes.

Tampoco se considera necesario especificar una tecnología concreta en la historia.

**Justificación:** la tecnología será analizada posteriormente de acuerdo con la viabilidad y las necesidades del proyecto.

## 5. Historia corregida

**Como ciudadano de Tlaxiaco, quiero registrar una solicitud de recolección de residuos indicando la ubicación y una descripción del problema, para que la autoridad correspondiente pueda recibirla y darle seguimiento.**

## 6. Criterios de aceptación corregidos

- [ ] El usuario puede registrar una solicitud.
- [ ] El sistema solicita la ubicación de la solicitud.
- [ ] El usuario puede ingresar una descripción del problema.
- [ ] El sistema genera un identificador único.
- [ ] El sistema confirma que la solicitud fue registrada.
- [ ] La solicitud queda disponible para su seguimiento.

## 7. Conclusión de la auditoría

La historia fue considerada adecuada después de realizar ajustes menores en sus criterios de aceptación y delimitar su alcance.
