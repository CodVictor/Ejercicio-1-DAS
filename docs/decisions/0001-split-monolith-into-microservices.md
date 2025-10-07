# 1. Elección del estilo arquitectónico

## Context and Problem Statement

## Decisión
Selección de estilo arquitectónico MVC

## Estado
Propuesta

## Context and Problem Statement:
Se quiere adaptar una arquitectura monolítica a una de microservicios, para lo que es necesario escoger un estilo arquitectónico adecuado.

## Consecuencias
- Positivo: Modularización del sistema
- Negativo: Migración de toda la arquitectura

## Considered Options

* Estilo por capas

## Decision Outcome

Chosen option: "MVC", because tenemos tres principales módulos, uno que contiene la inerfaz de usuario (vista), otro con la lógica de negocio (controlador) y otro que permite acceder a la base de datos (modelo). Esto encaja con el estilo arquitectónico MVC.
