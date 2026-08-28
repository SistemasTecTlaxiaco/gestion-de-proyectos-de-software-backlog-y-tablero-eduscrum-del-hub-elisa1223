# Auditoría IA — HU-04

## 1. Historia original

**Como usuario que reportó una incidencia del servicio de agua, quiero consultar el estado de mi reporte, para conocer si fue recibido y qué acciones se han realizado para atenderlo.**

## 2. Prompt utilizado

> Actúa como auditor de historias de usuario para un proyecto de software. Analiza la siguiente historia utilizando los criterios Como/Quiero/Para, rol real, claridad, alcance y criterios de aceptación verificables. Identifica ambigüedades, información faltante y posibles problemas de alcance.

## 3. Hallazgos

1. La historia presenta correctamente el rol, acción y beneficio.
2. Se requiere un mecanismo para localizar el reporte.
3. Debe mostrarse el estado actual.
4. Debe contemplarse la fecha de actualización.
5. Debe existir una respuesta cuando el reporte no sea encontrado.

## 4. Decisiones del equipo

### Observaciones aceptadas

Se acepta utilizar el identificador del reporte para realizar la consulta.

También se acepta mostrar la fecha de última actualización.

### Observaciones rechazadas

Se rechaza permitir que el usuario modifique directamente el estado.

**Justificación:** la actualización corresponde a la autoridad encargada de atender la incidencia.

## 5. Historia corregida

**Como usuario que reportó una incidencia del servicio de agua, quiero consultar el estado de mi reporte mediante su identificador, para conocer si fue recibido y qué acciones se han registrado para atenderlo.**

## 6. Criterios de aceptación

- [ ] El usuario puede ingresar el identificador.
- [ ] El sistema muestra el reporte correspondiente.
- [ ] Se muestra el estado actual.
- [ ] Se muestra la fecha de actualización.
- [ ] Se muestran las acciones registradas.
- [ ] El sistema informa si el reporte no existe.

## 7. Conclusión

La historia fue delimitada a la consulta del seguimiento y se agregaron criterios comprobables.
