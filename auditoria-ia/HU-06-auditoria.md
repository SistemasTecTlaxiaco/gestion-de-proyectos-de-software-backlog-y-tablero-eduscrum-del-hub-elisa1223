# Auditoría IA — HU-06

## 1. Historia original

**Como habitante de la región Mixteca, quiero consultar las campañas y jornadas de salud disponibles, para conocer las fechas, lugares y servicios que pueden estar disponibles para la población.**

## 2. Prompt utilizado

> Actúa como auditor de historias de usuario para un proyecto de software. Analiza la siguiente historia utilizando los criterios Como/Quiero/Para, rol real, claridad, alcance y criterios de aceptación verificables. Identifica ambigüedades, información faltante y posibles problemas de alcance.

## 3. Hallazgos

1. La estructura de la historia es correcta.
2. El rol es identificable.
3. La consulta de campañas está claramente delimitada.
4. Debe incluirse fecha y lugar.
5. Debe identificarse la institución responsable.
6. Es conveniente mostrar cuándo se actualizó la información.

## 4. Decisiones del equipo

### Observaciones aceptadas

Se acepta incluir fecha, lugar, institución responsable y fecha de actualización.

### Observaciones rechazadas

Se rechaza incluir la inscripción automática de pacientes.

**Justificación:** esa función no es necesaria para la necesidad inicial y aumentaría el alcance del proyecto.

También se rechaza almacenar información médica.

**Justificación:** la historia busca facilitar la consulta de información pública y no administrar información clínica.

## 5. Historia corregida

**Como habitante de la región Mixteca, quiero consultar las campañas y jornadas de salud disponibles, para conocer las fechas, lugares y servicios que pueden estar disponibles para la población.**

## 6. Criterios de aceptación

- [ ] El usuario puede consultar campañas y jornadas disponibles.
- [ ] Cada actividad muestra su fecha.
- [ ] Cada actividad muestra el lugar.
- [ ] Se muestra información básica sobre los servicios ofrecidos.
- [ ] Se identifica la institución responsable.
- [ ] Se muestra la fecha de actualización.

## 7. Conclusión

La historia se mantiene enfocada en la consulta de información pública y evita funciones que incrementarían innecesariamente el alcance y los riesgos de privacidad.
