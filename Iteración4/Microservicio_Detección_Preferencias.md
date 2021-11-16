# {Microservicio de Preferencias de Compra}

* Status: {accepted}
* Deciders: {ASS Grupo 2}
* Date: {2021-11-16}

Technical Story: {Funcionalidad de Preferencias de Usuario}

## Context and Problem Statement

{Se requiere de una funcionalidad que nos permita almacenar las preferencias de usuario.}

## Decision Drivers

* {RF05}

## Considered Options

* {Microservicio de Preferencias de Usuario}

## Decision Outcome

Chosen option: "{Microservicio de Preferencias de Usuario}", because {se necesitan microservicios para mantener el diseño de la arquitectura débilmente acoplado}.

### Positive Consequences

* {La funcionalidad de detección de preferencias sólo se desarrolla en el microservicio.}
* {Si el microservicio falla se puede usar el resto de funcionalidades hasta que vuelva a estar operativo gracias.}
* {Se mantiene una arquitectura débilmente acoplada ("loosely coupled").}

### Negative Consequences

* {El rendimiento de la aplicación es menor al hacer una petición al microservicio.}
