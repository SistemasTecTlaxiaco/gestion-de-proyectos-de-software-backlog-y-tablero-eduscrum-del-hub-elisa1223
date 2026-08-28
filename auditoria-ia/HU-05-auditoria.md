# Auditoría IA — HU-05

## 1. Historia original

**Como habitante de Tlaxiaco o de una comunidad de la región Mixteca, quiero consultar información sobre los servicios de salud disponibles, para identificar dónde puedo recibir atención de acuerdo con mis necesidades.**

## 2. Prompt utilizado

> Actúa como auditor de historias de usuario para un proyecto de software. Analiza la siguiente historia utilizando los criterios Como/Quiero/Para, rol real, claridad, alcance y criterios de aceptación verificables. Identifica ambigüedades, información faltante y posibles problemas de alcance. Considera especialmente privacidad y límites de la información.

## 3. Hallazgos

1. El rol está claramente identificado.
2. La acción principal es consultar información.
3. El beneficio está relacionado con localizar servicios.
4. Debe identificarse el origen de la información.
5. Es importante indicar la fecha de actualización.
6. Debe evitarse convertir la herramienta en un sistema de diagnóstico médico.

## 4. Decisiones del equipo

### Observaciones aceptadas

Se acepta identificar la institución responsable de la información y la fecha de actualización.

También se acepta establecer que la solución no proporciona diagnósticos.

### Observaciones rechazadas

Se rechaza almacenar expedientes médicos como parte de esta historia.

**Justificación:** no son necesarios para resolver la necesidad identificada y aumentarían los riesgos de privacidad.

## 5. Historia corregida

**Como habitante de Tlaxiaco o de una comunidad de la región Mixteca, quiero consultar información sobre los servicios de salud disponibles, para identificar dónde puedo recibir atención de acuerdo con mis necesidades.**

## 6. Criterios de aceptación

- [ ] El usuario puede consultar los servicios disponibles.
- [ ] Se muestra la institución responsable.
- [ ] Se muestra información básica del servicio.
- [ ] Se indica la fecha de actualización.
- [ ] La información proviene de una fuente institucional.
- [ ] El sistema no proporciona diagnósticos médicos.

## 7. Conclusión

La historia fue considerada adecuada después de delimitarla a información pública y establecer criterios relacionados con confiabilidad y privacidad.
