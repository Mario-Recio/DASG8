# ADR-01.Arquitectura cliente-servidor

* Status: deprecated
* Deciders: ASS,ASC
* Date: 2022-11-04

Technical Story: Architecture Decision

## Context and Problem Statement

Se requiere una base de datos interna para gestionar todo el espacio de almacenamiento de los datos que producen los sensores y otros dispositivos.

## Decision Drivers

* Se necesita una base de datos relacional que conecte con el sistema interno para poder guardar toda la información que se quiera consultar o enviar a los clientes a posteriori.

## Considered Options

* ADR-01
* ADR-01.1

## Decision Outcome

Chosen option: "ADR-01", because Se ha escogido esta opción porque es conveniente para persistir datos dentro del sistema interno de recogida de información de los sensores.
