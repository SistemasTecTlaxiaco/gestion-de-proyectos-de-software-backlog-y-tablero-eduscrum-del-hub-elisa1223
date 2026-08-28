# HU-04: Consultar el estado de una incidencia de agua

## Problemática relacionada

PROB-02: Seguimiento y atención de incidencias relacionadas con el servicio de agua.

## Historia de usuario

**Como usuario que reportó una incidencia del servicio de agua, quiero consultar el estado de mi reporte, para conocer si fue recibido y qué acciones se han realizado para atenderlo.**

## Rol

Usuario del servicio de agua potable.

## Criterios de aceptación

- [ ] El usuario puede consultar su reporte mediante un identificador.
- [ ] El sistema muestra el estado actual.
- [ ] El sistema muestra la fecha de la última actualización.
- [ ] El sistema muestra las acciones registradas.
- [ ] El sistema informa cuando el reporte no existe.
- [ ] La información mostrada corresponde al reporte consultado.

## Alcance

La historia contempla la consulta del estado y seguimiento de una incidencia. No permite al usuario modificar las acciones realizadas por la autoridad.

## Consideración tecnológica

Los cambios realizados sobre una incidencia deberán conservar un historial que permita conocer su evolución. Se evaluará posteriormente la tecnología más adecuada para garantizar la confiabilidad de dicho historial.
