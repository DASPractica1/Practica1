# {Microservicios}

* Status: [proposed]
* Deciders: [ASS Grupo 2]
* Date: [2021-10-27] 


Technical Story: {Implementación de una arquitectura predominante} 

## Context and Problem Statement

{Se necisita decidir una arquitectura la cual sea capaz de reflejar las diferentes funcionalidades de nuestro sistma}

## Decision Drivers 
*[RF_01]
*[RF_02]
*[RF_04]
*[RF_05]
*[RF_06]
*[RF_08]
*[RF_09]
*[RF_10]
*[RF_11]


## Considered Options

* {Implementación de una Arquitectura Microservicios}


## Decision Outcome

Chosen option: "{Implementar de una Arquitectura Microservicios}", because { es la opción mayor escalabilidad que nos ofrece.}

### Positive Consequences <!-- optional -->

*{Alta escalabilidad: Los Microservicios es un estilo arquitectónico diseñado para ser escalable, pues permite montar
numerosas instancias del mismo componente y balancear la carga entre todas las instancias.}
*{Reusabilidad: La reusabilidad es la médula espinal de la arquitectura de Microservicios, pues se basa en la creación 
de pequeños componentes que realice una única tarea, lo que hace que sea muy fácil de reutilizar por otras aplicaciones o 
Microservicios.}
*{Interoperabilidad: Debido a que los Microservicios utilizan estándares abiertos y ligeros para comunicarse, 
hace que cualquier aplicación o componente pueda comunicarse con ellos, sin importar en que tecnología está desarrollado.}



### Negative Consequences 

* {Múltiples puntos de falla: La arquitectura distribuida de los Microservicios hace que los puntos de falla de una 
aplicación se multipliquen, pues cada comunicación entre Microservicios tiene una posibilidad de fallar, lo cual hay 
que gestionar adecuadamente.}
*{Rendimiento: La naturaleza distribuida de los Microservicios agrega una latencia significativa que puede ser un 
impedimento para aplicaciones donde el performance es lo más importante, por otra parte, la comunicación por la red 
puede llegar a ser incluso más tardado que el proceso en sí.}

