# Auditoría IA — HU-03

## 1. Historia original

**Como usuario del servicio de agua potable, quiero reportar una incidencia indicando su ubicación y descripción, para que la autoridad responsable pueda conocer el problema y darle seguimiento.**

## 2. Prompt utilizado

> Actúa como auditor de historias de usuario para un proyecto de software. Analiza la siguiente historia utilizando los criterios Como/Quiero/Para, rol real, claridad, alcance y criterios de aceptación verificables. Identifica ambigüedades, información faltante y posibles problemas de alcance. No propongas tecnología específica a menos que sea necesario.

## 3. Hallazgos

1. La estructura de la historia es correcta.
2. El rol corresponde a un usuario real.
3. La ubicación es importante para identificar el problema.
4. La descripción permite explicar la incidencia.
5. Es necesario confirmar el registro de la incidencia.
6. Debe generarse un identificador para facilitar el seguimiento.

## 4. Decisiones del equipo

### Observaciones aceptadas

Se acepta agregar un identificador único y una confirmación del registro.

### Observaciones rechazadas

Se rechaza agregar la reparación automática de la incidencia.

**Justificación:** la reparación es una actividad operativa que queda fuera del alcance de la historia.

## 5. Historia corregida

**Como usuario del servicio de agua potable, quiero reportar una incidencia indicando su ubicación y descripción, para que la autoridad responsable pueda recibir el reporte y darle seguimiento.**

## 6. Criterios de aceptación

- [ ] El usuario puede registrar una incidencia.
- [ ] El sistema solicita la ubicación.
- [ ] El usuario puede describir el problema.
- [ ] El sistema genera un identificador.
- [ ] El sistema confirma el registro.
- [ ] La incidencia queda disponible para seguimiento.

## 7. Conclusión

La historia mantiene un alcance limitado al registro de incidencias y cuenta con criterios verificables.
