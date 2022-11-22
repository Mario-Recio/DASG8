# ADR-01.1.Arquitectura REST

* Status: deprecated
* Deciders: ASS,ASC
* Date: 2022-11-04

Technical Story: Architecture Decision

## Context and Problem Statement

Se requiere una arquitectura REST para poder comunicar entre un sistema interno (back end) y un sistema frontal (front-end) donde los clientes puedan hacer peticiones al sistema y de esta forma tener acceso a la información.

## Decision Drivers

* Para poder conectar los clientes con un sistema interno que gestionará todas las comunicaciones entre sensores.

## Considered Options

* ADR-01
* ADR-01.1

## Decision Outcome

Chosen option: "ADR-01", because Se ha rechazado esta opción porque se considera mucho más adecuada una arquitectura por eventos que permita gestionar a los clientes como se detalla en el ADR-01.
