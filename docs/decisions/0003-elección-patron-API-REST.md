## Elección patrón de diseño para comunicar el componente Gateway con los microservicios

* Status: proposed
* Date: 2025-10-18

## Context and Problem Statement
Comunicar el componente Gateway mediante API REST a los diferentes microservicios para clientes Web y vía movil.

## Considered Options
-Patrón facade
-Patrón proxy


## Chosen option
Patrón facade

## Decision Outcome
Chosen option: "Patrón facade", porque queremos simplificar el punto de entrada del Gateway a los diferentes microservicios.