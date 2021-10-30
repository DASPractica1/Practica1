# {Estilo por Capas}

* Status: [proposed]
* Deciders: [ASS Grupo 2]
* Date: [2021-10-27] 


Technical Story: {Se necsita un estilo para la organización de los diferentes componentes de la arquitectura} 

## Context and Problem Statement

{Se necesita una estilo para poder mantener un correcto flujo de datos y así dar soporte a las peticiones de la web }

## Decision Drivers <!-- optional -->
*[RF_03]
*[RF_13]
*[RF_14]
*[RF_15]
*[RF_16]
*

## Considered Options
*{Implementar una Arquitectura por Capas}


## Decision Outcome

Chosen option: "{Implementar una Arquitectura por Capas}", because {es la opcion que nos permite dar el soporte para la gestion de las capas que se solicitan}

### Positive Consequences 


* {Fácil de mantener, ya que permite la separación de responsabilidades y por lo tanto corregir los errores y bugs más rápidamente al tenerlo todo separado por capas}

* {La separación de capas permite el aislamiento de los servidores en subredes diferentes, lo que hace más difícil realizar ataques.}



### Negative Consequences
* { Al tener la capacidad de escalabilidad, tenemos como contra el problema de la organizacion o capacidad: Las aplicaciones que implementan este patrón
por lo general tienda a ser monolíticas, lo que hace que sean difíciles de escalar, aunque es posible replicar la aplicación completa en varios nodos, lo que provoca un escalado monolítico.}


* {Tolerancia a los fallos: Si una capa falla, todas las capas superiores comienzan a fallar en cascada.}

* {Complejidad de despliegue: En este tipo de arquitecturas es necesarios desplegar los componentes de abajo arriba, lo que crea una dependencia en el despliegue, además, si la aplicación tiende a lo monolítico, un pequeño cambio puede requerir el despliegue completo de la aplicación.}



