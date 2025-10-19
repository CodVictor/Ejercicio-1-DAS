## Elección patrón de diseño para limitar el modulo de pago a 3 intentos

* Status: proposed
* Date: 2025-10-10

## Context and Problem Statement
El modulo de págo debe limitarse a tres intentos de compra

## Considered Options
-Patrón state
-Patrón decorator


## Chosen option
Patrón state

## Decision Outcome
Chosen option: "Patrón state", porque cuando el cliente intente comprar 3 veces, el estado cambiará impidiendole comprar.