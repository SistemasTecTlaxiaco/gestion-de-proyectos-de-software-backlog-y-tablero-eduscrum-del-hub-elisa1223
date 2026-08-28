# Auditoría IA — HU-02

## 1. Historia original

**Como ciudadano que realizó una solicitud de recolección, quiero consultar el estado de mi solicitud, para conocer si fue recibida, está en proceso de atención o ya fue atendida.**

## 2. Prompt utilizado

> Actúa como auditor de historias de usuario para un proyecto de software. Analiza la siguiente historia utilizando los criterios Como/Quiero/Para, rol real, claridad, alcance y criterios de aceptación verificables. Identifica ambigüedades, información faltante y posibles problemas de alcance. No propongas tecnología específica a menos que sea necesario. Después proporciona recomendaciones concretas para mejorar la historia.

## 3. Hallazgos de la auditoría

1. La estructura Como/Quiero/Para es correcta.
2. El rol corresponde a un usuario real.
3. El objetivo de consultar el estado está claramente definido.
4. Es necesario especificar cómo se identifica la solicitud.
5. Los estados deben ser comprensibles y verificables.
6. Debe contemplarse el caso de una solicitud inexistente.

## 4. Decisiones del equipo

### Observaciones aceptadas

Se acepta utilizar un identificador único para localizar la solicitud.

También se acepta incluir criterios para mostrar la fecha de actualización y manejar solicitudes inexistentes.

### Observaciones rechazadas

Se rechaza agregar funciones para modificar directamente el estado por parte del ciudadano.

**Justificación:** el ciudadano solamente necesita consultar la información; la modificación del estado corresponde a la autoridad responsable.

## 5. Historia corregida

**Como ciudadano que realizó una solicitud de recolección, quiero consultar el estado de mi solicitud mediante su identificador, para conocer si fue recibida, está en proceso de atención o ya fue atendida.**

## 6. Criterios de aceptación corregidos

- [ ] El usuario puede ingresar el identificador de su solicitud.
- [ ] El sistema muestra la solicitud correspondiente.
- [ ] El sistema muestra el estado actual.
- [ ] El sistema muestra la fecha de la última actualización.
- [ ] El sistema muestra el historial disponible de seguimiento.
- [ ] Si la solicitud no existe, el sistema informa al usuario.

## 7. Conclusión

La historia fue mejorada mediante una delimitación más clara de la consulta y criterios de aceptación verificables.
